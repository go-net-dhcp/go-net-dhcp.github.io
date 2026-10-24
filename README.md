# go-net-dhcp.github.io

The [Hugo](https://gohugo.io) landing page for
[go-net-dhcp](https://github.com/go-net-dhcp), published to
<https://go-net-dhcp.github.io> via GitHub Pages.

```bash
hugo server   # local preview at http://localhost:1313
```

## The design is not here

It comes from the shared Hugo module
[`go-fleettools/landingkit`](https://github.com/go-fleettools/landingkit),
pinned in `go.mod` (Renovate bumps it); `kit.go` keeps `go mod tidy` from
deleting that requirement. `[params.brand]` in `hugo.toml` is read from the logo by
`landingkit brand`. A file under `layouts/partials/` with the name of one of the
kit's would silently override it.
