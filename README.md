# Cloud Native Buildpacks on Concourse

```
fly -t ci sp -p pack -c pipeline.yml  -l vars.yml
fly -t ci up -p pack
fly -t ci tj -j pack/pack-build --watch
```