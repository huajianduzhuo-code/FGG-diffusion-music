---
title: Interactive Symbolic Music Demo
emoji: 🖼
colorFrom: purple
colorTo: red
sdk: gradio
sdk_version: 4.42.0
app_file: app.py
pinned: false
python_version: 3.9.19
license: mit
---

Check out the configuration reference at https://huggingface.co/docs/hub/spaces-config-reference

Please find mido.MidoFile inside the pretty_midi package, and set all arg "clip" to clip=True

use set_seed(42) in sampler_sdf.py, generation result from chord slice (index = 2) is a good example (a wrong note is shifted to a correct one)

# Music Generation Demo Page

This repository contains the source code for the demo page showcasing our work on Efficient Fine-Grained Guidance for Diffusion-Based Symbolic Music Generation.

## Project Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── samples/           # Directory containing audio and image samples
│   ├── diy_examples/
│   ├── different_styles/
│   └── ablation/
└── README.md          # This file
```

## Setting Up GitHub Pages

1. Create a new repository on GitHub
2. Push these files to your repository
3. Go to your repository's Settings
4. Scroll down to the "GitHub Pages" section
5. Under "Source", select "main" branch
6. Click "Save"

Your site will be published at `https://<your-username>.github.io/<repository-name>/`

## Local Development

To test the site locally:

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

2. Open `index.html` in your web browser

## Required Assets

Make sure to include all the necessary audio and image files in the `samples` directory:

- Audio files (`.wav`)
- Image files (`.jpg`)
- Music sheet images

## Browser Compatibility

The demo page is compatible with modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to submit issues and enhancement requests!