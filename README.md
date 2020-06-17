# Steps to generate dataset:

1. First run all the cells of Dataset_Generation.ipynb notebook, It will save multiple numpy arrays in the local directory.
2. Move all the generated numpy arrays to a new folder, which doesn't have any file or folder before.
3. In Draw.py, change the dataset_path variable to this new folder (where all the numpy arrays are present).
4. Run Draw.py, It will generate images and store them in respective folders.
