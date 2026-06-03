# avishekb9.r-universe.dev

R-universe registry for [**avishekb9**](https://github.com/avishekb9).

The packages listed in [`packages.json`](packages.json) are built (source +
Windows/macOS binaries) and served as a CRAN-like repository at:

> **https://avishekb9.r-universe.dev**

## Install from this universe

```r
install.packages(
  c("sochcontagion", "contagionchannels", "ManyIVsNets"),
  repos = "https://avishekb9.r-universe.dev"
)
```

## Registered packages

| Package | Source |
|---------|--------|
| `sochcontagion` | https://github.com/avishekb9/sochcontagion |
| `contagionchannels` | https://github.com/avishekb9/contagionchannels |
| `ManyIVsNets` | https://github.com/avishekb9/ManyIVsNets |

To add a package, append an entry to `packages.json` (`package` = name in its
`DESCRIPTION`, `url` = its git repo; add `subdir` if the package is not at the
repo root). See https://docs.r-universe.dev.
