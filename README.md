# ParallaxMapping
This plugin is simulating 3D floor, wall, bricks models, by doing simple parallax mapping or parallax occlusion mapping.

## How to use it in other scripts
You need to create SceneParallaxContext, to create it click right mouse button in hierarchy, then ParallaxMapping/SceneParallaxContext.
Then to change parallax values, use this.

-----

change parallax scale - SceneParallaxContext.Instance.ChangeParallaxScale("Here's type float amount");
change textures count - SceneParallaxContext.Instance.ChangeTexturesCount("the same here's type float amount");
