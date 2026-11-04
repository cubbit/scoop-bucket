# cubbit/scoop-bucket

Scoop bucket for Cubbit projects.

## Usage

```powershell
scoop bucket add cubbit https://github.com/cubbit/scoop-bucket
scoop install cubbit/<app>
```

## Available Apps

### DittoFS

A modular virtual filesystem with pluggable storage backends. [Repository](https://github.com/cubbit/dittofs)

| App | Description |
|-----|-------------|
| `dfs` | DittoFS server daemon |
| `dfsctl` | DittoFS CLI client for remote server management |

```powershell
scoop install cubbit/dfs
scoop install cubbit/dfsctl
```
