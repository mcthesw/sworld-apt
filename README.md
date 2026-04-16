# easy-nats APT repository

APT package repository for [easy-nats](https://github.com/mcthesw/easy-nats).

## Setup

```bash
# Add the repository
echo "deb [trusted=yes] https://mcthesw.github.io/easy-nats-apt stable main" | \
  sudo tee /etc/apt/sources.list.d/easy-nats.list

# Install
sudo apt update
sudo apt install easy-nats
```
