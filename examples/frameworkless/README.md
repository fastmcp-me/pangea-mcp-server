# Frameworkless example

An example app that demonstrates how to connect to the Pangea MCP server and
call its tools without any frameworks.

Running this requires all of the prerequisites of the MCP server and requires
building the MCP server (see instructions in the root `README.md`). The
following environment variables must be set as well:

- `PANGEA_VAULT_TOKEN`
- `PANGEA_VAULT_ITEM_ID`
- `PANGEA_AUDIT_CONFIG_ID`
- `ANTHROPIC_API_KEY` — An Anthropic API key.

Then run the following from this directory:

```shell
$ npm run build

$ node dist/index.js --input "where are these IP addresses located?: 89.187.191.12, 78.46.209.220, and 185.73.44.89"
```
