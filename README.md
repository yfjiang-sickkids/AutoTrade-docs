# AutoTrade docs assets

Public docs companion to the (private) [AutoTrade](https://github.com/yfjiang-sickkids/AutoTrade) trading bot project.

## Contents

- `images/brooks/` — synthetic K-line illustrations of Brooks price-action patterns. Used by the Notion encyclopedia (Al Brooks page) via raw GitHub URL embeds. All images are original synthetic OHLC data + matplotlib output (no third-party material).

## Why a separate public repo

The main AutoTrade repo is private (contains broker integration, strategy parameters). Notion's image embed needs anonymous public URLs. This repo holds only doc assets so private code stays private while images stay reachable.

## Generation

Source script lives in the private repo: `scripts/gen_brooks_diagrams.py`. Run there, then copy the PNG output into this repo and push.
