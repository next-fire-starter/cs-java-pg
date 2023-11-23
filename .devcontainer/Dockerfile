FROM mcr.microsoft.com/devcontainers/base:ubuntu22.04

RUN sudo apt install -y curl wget
RUN curl -s "https://get.sdkman.io?rcupdate=true" | bash
RUN bash -c "source /root/.sdkman/bin/sdkman-init.sh && sdk install java 21.0.1-graal"
RUN bash -c "source /root/.sdkman/bin/sdkman-init.sh && sdk install gradle 8.4"
RUN echo "source /root/.sdkman/bin/sdkman-init.sh" >> /root/.bashrc
# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment this line to install global node packages.
# RUN su vscode -c "source /usr/local/share/nvm/nvm.sh && npm install -g <your-package-here>" 2>&1
