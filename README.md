# Tamil Kolam: JSON Prompting for Images and Video

> Structured JSON prompts give consistent, controllable results in image and video generators.

 ![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## Overview

Instead of a free-text prompt, `tamil_prompt.json` describes the subject, style, colours, composition and motion as structured fields. The same JSON was used to generate three traditional **Tamil kolam** images and a 10-second video, showing how JSON prompting keeps outputs consistent.

## Demo

![Kolam 1](tamil_kolam_image_1.png)
![Kolam 2](tamil_kolam_image_2.png)
![Kolam 3](tamil_kolam_image_3.png)

## Project structure

```text
.
├── tamil_prompt.json        # the JSON prompt
├── tamil_kolam_image_*.png  # generated images
└── tamil_kolam_video.mp4    # generated 10-second video
```

## Usage

Validate the JSON (`python -m json.tool tamil_prompt.json`), then paste it into an image or video model that accepts structured prompts.

## License

Released under the [MIT License](LICENSE).

## Author

**Prasanth Sundararajan**, Senior SRE and AI Engineer  
[LinkedIn](https://www.linkedin.com/in/prasanth-s-a093a7109/) · [GitHub](https://github.com/prasanth-sundararajan)
