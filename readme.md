```sh
yarn --offline && yarn upgrade dep-a@1.1.0 --offline
```
Fails with 
```
error /Users/pavelbirukov/work/sandbox/prune-offline-mirror/node_modules/dep-a: Command failed.
Exit code: 127
Command: sh
Arguments: -c foo
Directory: /Users/pavelbirukov/work/sandbox/prune-offline-mirror/node_modules/dep-a
Output:
sh: foo: command not found
```