# scoop-mondo

[Scoop](https://scoop.sh) bucket for [**mondo**](https://github.com/zoltanf/mondo) — a power-user CLI for the monday.com GraphQL API.

## Install

```powershell
scoop bucket add mondo https://github.com/zoltanf/scoop-mondo
scoop install mondo
```

Update later with `scoop update mondo`; remove with `scoop uninstall mondo`.

## Maintenance

`bucket/mondo.json` is generated and pushed automatically by the
[`update-scoop`](https://github.com/zoltanf/mondo/blob/main/.github/workflows/release.yml)
job in the mondo release workflow on every stable tag. Don't edit it by hand.
