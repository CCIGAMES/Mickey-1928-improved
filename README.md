---
license: cc0-1.0
tags:
- text-to-image
- stable-diffusion
- lora
- diffusers
base_model: stabilityai/stable-diffusion-xl-base-1.0
instance_prompt: Mickey
widget:
- text: "drawing of Mickey, theater in background"
  output:
    url: "mickey_theater.jpg"
- text: "drawing of Mickey inspiring the communist revolution"
  output:
    url: "communist_mickey.jpg"
- text: "pop-art painting of Mickey walking in Paris"
  output:
    url: "mickey_paris.jpg"
pipeline_tag: text-to-image
datasets:
- chaphi/mickey1928extra
---

**Mickey-1928-improved** is a modified version of Mickey-1928, a fine-tuned version of Stable-Diffusion-xl trained on various stills in the public domain from 1928.

<Gallery />

Mickey-1928 can generate images of Mickey, Minnie and, to a much lesser extent, Pete.

## Dataset

Since 2024, the first three cartoons of Mickey are in the public domain. The final dataset includes:
- 40 stills from *Gallopin' Gaucho* (in color)
- 25 stills from *Plane Crazy* (3 in colour)
- 35 stills from *Steamboat Willie* (1 from the non-affiliated colourisation project).
- 1 still from an *Oswald short*
- 2 stills from *The Mad Doctor*
- 3 stills from *The Plowboy*
- 1 still from *Get a horse*
- various posters, cels and sketches from the time
- the best images made by the original model (as well as soom bad ones edited to look better)
- and some self made replications of the style

Now, you are probably wondering "Get a Horse and Plowboy arent public domain? whats going on?", well, Get a Horse and The Plowboy both use the 1928 Mickey design with very little difference (other than gloves in the plowboy but they are also public domain), There is a still featuring horace horsecollar at the time of making this readme but that will be removed once the models dataset is full.


The stills are not currently available in high quality and you should not expect consistently good results from Mickey-1928. The color images from *Gallopin' Gaucho* are in 360x360 pixels. Hopefully with the cartoons now being part of the public domain, higher definition versions should be available.

The generated images aim to adhere to the 1928 design in order to have Mickey, Minnie and Pete in the public domain. This is still a work in progress: while the model is in development, generated images should be checked to ensure they really are in the public domain design.
