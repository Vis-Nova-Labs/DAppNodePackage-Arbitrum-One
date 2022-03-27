ARG UPSTREAM_VERSION

FROM offchainlabs/arb-node:${UPSTREAM_VERSION}

USER root
RUN mkdir -p /home/user/.arbitrum/mainnet \
 && chown -R user /home/user/.arbitrum/mainnet

USER user

ENTRYPOINT arb-node --l1.url=$ETH1_RPC_URL $EXTRA_OPTS
