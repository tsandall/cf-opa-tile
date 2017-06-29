# OPA Cloud Foundry Tile

cf-opa-tile is a tile to deploy the [Open Policy Agent (OPA)](https://github.com/open-policy-agent/opa) in Cloud Foundry.

![Alt-text](installation.png?raw=true "Title")

## Usage

Clone this repository:

```bash
git clone https://github.com/tsandall/cf-opa-tile.git
```

Create virtualenv for tile-generator:

```bash
virtualenv tile-env
source tile-env/bin/activate
pip install tile-generator --upgrade
```

Build the tile:

```bash
cd cf-opa-tile
tile build
```
