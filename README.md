# AgentPing releases

Builds of the AgentPing companion, which stops AI coding agents from sending
secrets and personal data to models and tools. This repository holds release
files and the Homebrew cask only.

## Install

macOS and Linux:

```sh
curl -fsSL https://github.com/madsquarebs/homebrew-agentping/releases/latest/download/install.sh | sh
```

Homebrew:

```sh
brew install --cask madsquarebs/agentping/agentping
```

Windows (PowerShell):

```powershell
irm https://github.com/madsquarebs/homebrew-agentping/releases/latest/download/install.ps1 | iex
```

Update with `agentping update`.

## Verifying a download

Each release has `checksums.txt` and its signature `checksums.txt.sig`. The
install scripts check the archive against `checksums.txt`, and
`agentping update` also verifies the signature with the key built into the
installed binary before replacing it.
