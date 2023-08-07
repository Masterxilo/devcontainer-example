FROM ubuntu

# without these, the devcontainers extension will not copy your .gitconfig into the container, see
# https://code.visualstudio.com/remote/advancedcontainers/sharing-git-credentials
RUN apt-get update && apt-get install -y git ssh
# by doing this, the ssh-agent and cat ~/.gitconfig should be automatically copied from the host...
