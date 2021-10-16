# azure-pipelines-agent-freebsd
FreeBSD builds of Azure Pipelines Agent
# Requirements:
- FreeBSD 12.2+, 13.0+
- `pkg install bash curl git icu libinotify libunwind node`
- Willingness to run unsupported app built from unsupported SDK

# Known Issues:
- `installdependencies.sh` has no idea what to do
- `DownloadPipelineArtifact@` fails due to unknown OS: https://github.com/microsoft/azure-pipelines-agent/pull/3266#issuecomment-941945362
