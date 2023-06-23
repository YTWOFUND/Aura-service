<h1 align="center"> State-Sync Peer for Aura. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
a8206b951ca576c96810282341e7ff3dc0406dd6@188.172.228.225:11656
```
To add the peer, you can use the following instructions:
```
PEERS=a8206b951ca576c96810282341e7ff3dc0406dd6@188.172.228.225:11656
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.aura/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .aura/config/config.toml
```
Add the peer YTWOFUND to the "persistent_peers" line.
