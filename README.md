# APT Repository

APT package repository for Sworld's projects.

## Available

| Package | Description |
|---------|-------------|
| easy-nats | Desktop GUI client for NATS |

## Usage

```bash
echo "deb [trusted=yes] https://mcthesw.github.io/sworld-apt stable main" | \
  sudo tee /etc/apt/sources.list.d/mcthesw.list
sudo apt update
sudo apt install <package>
```
