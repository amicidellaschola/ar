
### Loading audio files

[Docs](https://aframe.io/docs/1.1.0/core/asset-management-system.html)

### Make an entity interactive

[Docs example](https://aframe.io/docs/1.1.0/components/cursor.html#example)

### Integrate with React

[source](https://aframe.io/docs/1.1.0/introduction/installation.html)
The most important difference between a browser environment and a Cordova environment is waiting for the deviceready event before rendering your scene.

The sample above shows a pure DOM+JS approach, but you can also use a framework like React:

document.addEventListener('deviceready', () => {
  ReactDOM.render(<Root />, document.getElementById('root'))
})

### Tutorials

- https://medium.com/chialab-open-source/build-your-location-based-augmented-reality-web-app-c2442e716564

## 3D models compresstion

### Draco

#### Install on Ubuntu

See [this official guide](https://codelabs.developers.google.com/codelabs/draco-3d/index.html#0).
Run the following commands:

- `git clone git@github.com:google/draco.git`
- `cd draco`
- `mkdir build`
- `cd build`
- `cmake ../` (install cmake form `snap`)
- `make`
