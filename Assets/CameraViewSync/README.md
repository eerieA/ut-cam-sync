# CamViewSync – Camera Piloting for Unity Scene View

CamViewSync is a lightweight Unity Editor extension that lets you **pilot any selected camera using the Scene View**. This gives you intuitive control over camera positioning, inspired by Unreal Engine's camera piloting system.


## Features

- Sync Scene View to a selected in-scene Camera
- Real-time transform updates while you move around
- Undo/redo support for camera movement
- State persists between domain reloads and editor restarts

## How to Use

1. Select a GameObject with a `Camera` component.
2. Go to `Tools → Camera View Sync → Start Piloting`.
3. Move around in the Scene view, and the selected camera will follow.
4. To stop piloting, use `Tools → Camera Pilot → Stop Piloting`.

## Compatibility

- Unity **6.1**
- Editor-only (no runtime dependencies)
- No additional input system required

## Known Limitations

- Piloting works only in the Scene View (not Game View or Play mode).
- Does not support piloting multiple cameras at once.
- Transform syncing only happens during editor camera movement.

## License

This asset is distributed under the [Unity Asset Store EULA](https://unity3d.com/legal/as_terms).  
License type: **Extension Asset**
