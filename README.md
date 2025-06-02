# Synapse + Matrix-Telegram Bridge Setup

This short guide describes how to set up a Matrix Synapse server and bridge it with Telegram using matrix-appservice-telegram.

---

## 1. Synapse Setup

## 🚀 Prerequisites

- Docker
- Python 3.10+
- PostgreSQL


The Synapse documentation describes how to 
[to install Synapse](https://matrix-org.github.io/synapse/develop/setup/installation.html/).
In synapse folder, you can find examples of docker-compose and homeserver files.



## 2 Setup matrix-telegram bridge

## 🚀 Prerequisites

- Docker
- Python 3.10+
- Matrix homeserver that supports application services (e.g. Synapse)
- PostgreSQL
- Telegram app ID and hash (get from my.telegram.org).
- Telegram bot token (for bridging)


The documentation describes how to 
[to install setup telegram bridge](https://docs.mau.fi/bridges/python/setup.html?bridge=telegram/).
In mautrix-telegram folder, you can find examples of docker-compose and config files.
