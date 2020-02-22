## COLMAP

COLMAP is a state-of-the-art, free and open-source, Structure-from-Motion program. It was developed by Johannes L. Schönberger as a part of his PhD work at ETH Zürich.

Given a set of unordered and uncalibrated images, the program can build an accurate sparse model of the scene as well as recover the camera poses. The program can also build a dense model if a CUDA-enabled GPU is available.

### Getting started

- For Ubuntu 18.04+, simply run `sudo apt install colmap` to install. For other versions of Linux you might have to [build from source](https://colmap.github.io/install.html#build-from-source).

- For Windows/Mac, pre-built binaries are available [here](https://github.com/colmap/colmap/releases/tag/3.5).

- Open the app by running `colmap gui` from the command line. Alternatively, on Windows/Mac run COLMAP.bat/COLMAP.app to start the gui.

- Download the provided sample images from the `data` folder.

- Click `Reconstruction > Automatic Reconstruction` in the gui and select the dataset directory. Choose the options as necessary.

- Remember to select/Unselect `Dense` and `GPU` options based on CUDA-enabled GPU availability.

- Click Run. This can take up to 20 minutes on a Core i5 CPU with 8GB RAM.

- Controls:
    - Rotate model: Left-click and drag.
    - Shift model: Right-click or <CTRL>-click (<CMD>-click) and drag.
    - Zoom model: Scroll.

- Refer to the official [documentation](https://colmap.github.io/index.html) for a more comprehensive tutorial and the associated [paper](http://demuc.de/papers/schoenberger2016sfm.pdf).
