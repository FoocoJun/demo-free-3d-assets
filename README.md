# Demo Free 3D Assets

Free 3D game assets in GLB and FBX formats.

## Download

All models are available in the [Releases](../../releases) section.

- **GLB**: Universal format, works with Three.js, Babylon.js, model-viewer
- **FBX**: Rigged models with animations for game engines

## Catalog

See `catalog.json` for the full list of available models with metadata.

## Categories

- `props` - Game props and objects
- `coins` - Coins and currency
- `ammo` - Ammunition and weapons
- `small-assets` - Small decorative items
- `food` - Food items
- `rigged` - Rigged character models with FBX

## Usage

```javascript
// Using model-viewer
<model-viewer src="https://github.com/FoocoJun/demo-free-3d-assets/releases/download/v1.0.0/model-name.glb" camera-controls auto-rotate></model-viewer>

// Using Three.js
import { GLTFLoader } from 'three/examples/jsm/loaders/GLTFLoader';
const loader = new GLTFLoader();
loader.load('https://github.com/FoocoJun/demo-free-3d-assets/releases/download/v1.0.0/model-name.glb', (gltf) => {
  scene.add(gltf.scene);
});
```

## License

These assets are free for personal and commercial use.
