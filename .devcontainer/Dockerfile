FROM mcr.microsoft.com/devcontainers/base:ubuntu

ARG SONAR_SCANNER_VERSION=6.2.1.4610

RUN curl -sSLo /tmp/sonar-scanner-cli.zip \
      https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-${SONAR_SCANNER_VERSION}-linux-x64.zip \
    && unzip -o /tmp/sonar-scanner-cli.zip -d /opt \
    && ln -sf /opt/sonar-scanner-${SONAR_SCANNER_VERSION}-linux-x64/bin/sonar-scanner /usr/local/bin/sonar-scanner \
    && rm /tmp/sonar-scanner-cli.zip
