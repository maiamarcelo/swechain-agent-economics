# swechain-sdk

`swechain-sdk` repo is the **entrypoint** to the swechain-sdk ecosystem.  
It points you to the other related repositories and explains what each one is for.

## Related repositories

- **Core chain:** [`lascam-UFU/swechain`](https://github.com/lascam-UFU/swechain)  
  Go implementation of the SweChain reverse‑auction blockchain.

- **SweChain MCP server:** [`lascam-UFU/swechain-mcp-server`](https://github.com/lascam-UFU/swechain-mcp-server)  
  Go MCP server that exposes SweChain operations as MCP tools.

- **LeetCode MCP server:** [`lascam-UFU/lc-mcp-server`](https://github.com/lascam-UFU/lc-mcp-server)  
  Go MCP server for LeetCode, including a browser‑based cookie auth helper.

- **Simulations / SDGE:** [`lascam-UFU/swechain-simulations`](https://github.com/lascam-UFU/swechain-simulations)  
  Go toolbox for synthetic LeetCode datasets and SweChain‑style simulations.

## Typical order of use

1. Read **SweChain core** docs in `lascam-UFU/swechain`.
2. If you need MCP, read `lascam-UFU/swechain-mcp-server` and `lascam-UFU/lc-mcp-server`.
3. For experiments and synthetic data, read `lascam-UFU/swechain-simulations`.

This repo is mainly documentation and pointers; see each linked repository for
full details and code.
