## Including Animations
In addition to the files in `raster` and `vector`, the presentation slide show also includes an animation of a proton-proton collision in the ATLAS detector which I have not placed under version control and is not available in this directory. At the time of writing, the original animation is available on the ATLAS Experiment's YouTube channel with the title [Proton Collision Event with Boosters and LHC](https://www.youtube.com/watch?v=NhXMXiXOWAA). If you want to replicate the original presentation exactly, download the animation from YouTube and modify the `media` directory's structure to read:
```
media/
├── animations/
│   ├── collision.mp4
│   ├── collision.ogv
│   └── collision.png
├── raster/
└── vector/
```
The file `collision.mp4` is an `mp4` video of the animation, while `collision.png` is a static `png` image of your choice used in the presentation slides. The file `collision.ogv` uses the rather obscure OGV video format, which is compatible with the `pdfpc` presentation software (while `mp4`, as far as my experiments showed, was not). If you aren't using `pdfpc` to present the slides, you probably don't need the `ogv` file. If you are, at the time of writing you can convert from `mp4` to `ogv` using the website [https://video.online-convert.com/convert-to-ogv](https://video.online-convert.com/convert-to-ogv).
