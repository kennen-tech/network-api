# Nexus Network CLI

A high-performance command-line interface for contributing proofs to the Nexus network.


<figure>
    <img src="assets/images/nexus-network-image.png" alt="Nexus Network visualization showing a distributed network of interconnected nodes with a 'Launch Network' button in the center">
    <figcaption>
        <strong>Verifiable Computation on a Global Scale</strong><br>
        We're building a global distributed prover network to unite the world's computers and power a new and better Internet: the Verifiable Internet. Connect to the beta and give it a try today.
    </figcaption>
</figure>

## Quick Start

```bash
curl https://cli.nexus.xyz/ | sh
```

If you don't have Rust installed, you will be prompted to install it.

## Prerequisites

### Linux
```bash
sudo apt update && sudo apt upgrade
sudo apt install build-essential pkg-config libssl-dev git-all
```

### macOS
```bash
brew install git
```

### Windows
[Install WSL](https://learn.microsoft.com/en-us/windows/wsl/install) first, then follow Linux instructions.

## Terms of Use

Use of the CLI is subject to the [Terms of Use](https://nexus.xyz/terms-of-use). First-time users will be prompted to accept the terms. For non-interactive acceptance (e.g., CI environments), use:

```bash
NONINTERACTIVE=1 sh
```

## Current Limitations

- Only latest CLI version is supported
- No prebuilt binaries yet
- Email linking available on web only
- Proof cycle counting coming soon
- Program submission requires API key (contact growth@nexus.xyz)

## Get Help

- [Network FAQ](https://nexus.xyz/network#network-faqs)
- [Discord Community](https://discord.gg/nexus-xyz)
- Technical issues? [Open an issue](https://github.com/nexus-labs/network-api/issues)

## Repository Structure

```
network-api/
├── clients/
│   └── cli/      # Main CLI implementation
└── src/          # Shared network interface code
```

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for development setup and guidelines.
