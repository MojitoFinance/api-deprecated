# MojitoSwap API

The MojitoSwap API is a set of endpoints used by market aggregators (e.g. coinmarketcap.com) to surface 
MojitoSwap liquidity and volume information. All information is fetched from the underlying subgraphs.

The API is designed around the CoinMarketCap
[requirements document](https://docs.google.com/document/d/1S4urpzUnO2t7DmS_1dc4EL4tgnnbTObPYXvDeBnukCg).

Prefer the MojitoSwap subgraph for any MojitoSwap queries whenever possible. The respective subgraphs will always have more
recent data.

## V1 Documentation

The documentation of the `/v1/` endpoints is [here](./v1.md).

## V2 Documentation

The documentation of the `/v2/` endpoints is [here](./v2.md).

## Deploying the API

The API uses the [serverless framework](https://serverless.com) and can easily be deployed to any AWS account,
via the `yarn sls deploy` command.

In order to configure your AWS account as a target, 
see [the serverless docs](https://www.serverless.com/framework/docs/providers/aws/guide/credentials/).
