# Anodyne-API

Anodyne's API backend.

## run
### with nix
`nix develop`

### without nix
```shell
go build .
ln -s /anodyne-frontend/db.sqlite ./
tmux new-session -d -s anodyne-api './anodyne-api'
```
