# Cloud Foundry Python Buildpack


This buildpack supports running Django and Flask apps.

### Buildpack User Documentation


## Adding new dependencies

```yaml
python:
  lines:
    - line: 3.14.X
      deprecation_date: 2030-10-07
      link: https://peps.python.org/pep-0745/
```

The new dependency will be automatically added to the buildpack [manifest.yml](manifest.yml) file.

