This is a project which takes a butane file and generates a valid ignition file that can be used to deploy dylanmtaylor.com and all of the content and services running on it on a fresh installation of CoreOS by supplying the ignition file contents as userdata to a cloud instance.

# Generate ignition locally
```
podman run --interactive --rm quay.io/coreos/butane:release --pretty --strict < config.bu > config.ign
```
