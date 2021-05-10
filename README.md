# io-core-metarepo
A development metarepo for io-core team

Install lerna and meta as global dependencies with: 

```
sudo npm i -g meta
sudo npm i -g lerna
```

Bootstrap script needs `jq` installed, on macos install it with brew:

```
brew install jq
```
# Usage

From inside io-core-metarepo folder run:

```
sh bootstrap
```

You can operate on repos as usually, local repositories are linked by lerna. You can run meta commands to make git operations, and lerna commands to build any project with its referenced ones.

