# azure-pipelines-agent-freebsd
FreeBSD builds of Azure Pipelines Agent
# Requirements:
- FreeBSD 11.4+, 12.2+, 13.0+
- `pkg install bash curl git icu libinotify libunwind node`
- Willingness to run unsupported app built from unsupported SDK

# Known Issues:
- Must write your own service file or run as daemon
- Azure DevOps will have no idea what version this actually as it was built from script and not pipelines yaml
- `installdependencies.sh` has no idea what to do
