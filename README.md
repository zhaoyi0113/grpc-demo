How to setup

- Run `yarn install`.
- Open the repo in `vs code`.
- Click `Start debuggin` in `Debug` menu
- Search `Hello world` in the command menu
- You will see the full exception relates to `grpc` as below

```
1): Symbol not found: _GENERAL_NAME_free
extensionHostProcess.js:621
  Referenced from: /Users/joeyzhao/dev/bigcrunch/extension/grpc-demo/node_modules/grpc/src/node/extension_binary/node-v57-darwin-x64-unknown/grpc_node.node
  Expected in: flat namespace
```