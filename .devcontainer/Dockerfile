ARG VARIANT="6.0"
FROM mcr.microsoft.com/vscode/devcontainers/dotnet:0-${VARIANT}

# Clear the NUGET_XMLDOC_MODE env var so xml api doc files get unpacked, allowing a rich experience in Intellisense.
# See https://github.com/dotnet/dotnet-docker/issues/2790 for a discussion on this, where the prioritized use case
# was *not* devcontainers, sadly.
ENV NUGET_XMLDOC_MODE=