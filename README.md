# Azure Pipelines Agent For FreeBSD
FreeBSD builds of Azure Pipelines Agent
# Requirements:
- FreeBSD 13.2, 14.0
- `pkg install bash curl git icu libinotify libunwind node`
- Willingness to run unsupported app built from unsupported SDK

# Known Issues:
- `installdependencies.sh` has no idea what to do
- No auto update feature
- `DownloadPipelineArtifact@` fails due to unknown OS: https://github.com/microsoft/azure-pipelines-agent/pull/3266#issuecomment-941945362 and https://github.com/Thefrank/azure-pipelines-agent-freebsd/issues/1
- [No Code Coverage](https://github.com/microsoft/azure-pipelines-coveragepublisher/). 
