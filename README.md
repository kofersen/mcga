# mcga
Privacy and security hardening for stock Chromium without recompiling

## Installation

```bash
# Flags config
cp chromium-flags.conf ~/.config/chromium-flags.conf

# Enterprise policy (any Linux)
sudo mkdir -p /etc/chromium/policies/managed
sudo cp privacy.json /etc/chromium/policies/managed/privacy.json
```

## Verify

Restart Chromium, then check:
- `chrome://version` flags in Command Line section
- `chrome://policy` applied policies

## License

CC0
