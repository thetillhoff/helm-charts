# Package helm chart into <name-semver>.tgz
Chart has to be in current folder, like ./<chart-name>/
```
helm package <chart-name>
```

# Create repository index
```
helm repo index .
```
