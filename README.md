# MobileNeRF viewer for WebXR
> This project is **NOT** made by the people behind  MobileNeRF. For the original see: [Website](https://mobile-nerf.github.io/) | [Source](https://github.com/google-research/jax3d/tree/main/jax3d/projects/mobilenerf). Instead it's just a hacky adjustment to their viewer allowing the MobileNeRF demo scenes to be viewed in VR through WebXR.

Seeing MobileNeRF render at interactive framerates on mobile devices immediately gave me the urge to try and render them in VR. The result is this small hacky project, which is heavily based on the original viewer, and exclusively uses the same live demo scenes. All credit for the research, original viewer code and demo scene data goes to the [original authors](https://mobile-nerf.github.io/).

## Requirements
While it _can_ run on standalone headsets, it's really recommended that you use a VR headset connected to a PC with a dedicated graphics card.

And since the project uses WebXR, you'll need to use a browser with WebXR support.

## Known problems / limitations
* It's still very demanding and won't run smoothly on a standalone VR headset (like the Quest 2 or Pico Neo Link 3).
* Scale, position and floor height are not accurate
* Some scenes have a rotation to them, making it appear as if they are sloped.