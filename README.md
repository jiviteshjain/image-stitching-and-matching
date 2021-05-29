# Image Mosaicing and Stereo Correspondences

This software stitches together images taken from the same spot with different camera orientations by estimating a homography between them. This is roughly how your phone takes a panorama. Further, it explores the stereo-matching problem, trying out approaches and comparing results. See the notebook for more details.

<p align="center">
<img src="https://user-images.githubusercontent.com/43912285/120064582-8556a500-c08a-11eb-94ab-ea78692f9f3a.png" width=300/>
</p>

## To run
*All commands to be run from the repository root.*  

1. Install python packages from the Python Package Index (preferably in a virtual environment).
   ```(shell)
   python3 -m venv env && source env/bin/activate # optional
   pip install -r requirements.txt
   ```
2. Run the notebook on a jupyter server.
   ```(shell)
   jupyter notebook
   ```
   Open `src/matching.ipynb` in the web browser window.

