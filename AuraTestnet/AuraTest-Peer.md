<h1 align="center"> State-Sync Peer for Aura. </h1>
To synchronize, you can use our peer by adding it to the config.toml file.

```
4a7ec293b4342c69b9ccb01ee7dae19963537077@188.172.228.225:22656
```
To add the peer, you can use the following instructions:
```
PEERS=4a7ec293b4342c69b9ccb01ee7dae19963537077@188.172.228.225:22656
sed -i.bak -e "s/^persistent_peers =./persistent_peers = "$PEERS"/" $HOME/.aura/config/config.toml
```

Alternatively, you can add it manually.
Open the config.toml file with the nano editor.
```
nano .aura/config/config.toml
```
Add the peer YTWOFUND to the "persistent_peers" line.
