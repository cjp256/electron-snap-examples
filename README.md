# electron-builder-hello-world

Example snapping electron apps using electron-builder:

```
# Build it.
cd electron-builder-hello-world
npm install
npm run dist

# Install it.
sudo snap install dist/*.snap --dangerous

# Run it.
electron-builder-hello-world
```

# electron-packager-hello-world

Example snapping electron apps using electron-packager:

```
# Build it.
cd electron-packager-hello-world
snapcraft

# Install it.
sudo snap install *.snap --dangerous
sudo snap connect electron-packager-hello-world:browser-sandbox

# Run it.
electron-packager-hello-world
```
