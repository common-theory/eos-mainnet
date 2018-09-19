# eos-mainnet [![CircleCI](https://circleci.com/gh/common-theory/eos-mainnet.svg?style=shield)](https://circleci.com/gh/common-theory/eos-mainnet)
An EOS mainnet docker image

## About

The `--data-dir` of the nodeos daemon is mapped to `/data` in the filesystem. If `/data/blocks` is not present the `--genesis-json` option is supplied with [`/genesis.json`](https://github.com/common-theory/eos-mainnet/blob/master/genesis.json).
