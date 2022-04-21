# 3DARD python-tutorials
## Overview
Series of tutorials and assignments to learn how to use the 3dard dataset, and discover what are acquired point clouds, what can be done with this type of data, what are the challenges to processing them.

All the tutorials are coded using `python` language, and exposed as jupyter notebook. The goal is here to keep things simple for newcomers.
Even if we use python front-ends, most of the processing stages demonstrated in these tutorials are implemented in C++ and wrapped to python, so we still get decent performances.

Tools used in these tutorials:
 - 3dard: dataset of large-scale multimodel acquired point clouds. Python front-end: https://github.com/3D-ARD/python-module
 - open3d: 3d processing library: https://github.com/isl-org/Open3D

## How to contribute
Two options:
 - *Share your outcomes*: if you are happy about your results on a given tutorial, please share it by uploading your code to this repository (see instructions below).
 - *Write tutorials or assignments*: because many different things can be done, you may have found new way to teach how to process 3d data. Don't hesite to share your tutorial on this repository (again, see below). Same thing if you want to promote interesting processing tool available in python.

In any case, please share your results as jupyter notebooks if possible, so people can access them from github directly, and see what you did. If you don't want to use jupyter, python scripts are also ok.

### Share your outcomes
If you enjoyed a tutorial, and want to share your results, please follow this procedure:
 - fork this repository
 - in your fork: if it does not exist, create a folder with the same name than the tutorial you followed, e.g., `tutorial1` if for `tutorial1.ipynb`
 - add your notebook or script in this folder. Remember to add your personal details if you wish (e.g., name, link to github account) in the header. All results are meant to be shared with the same licence than the repository (https://github.com/3D-ARD/3d-ard-python-tutorials/blob/main/LICENSE). Please keep your code readable and commented. Please also add images in the notebook, if relevant.
 - commit and push to your fork
 - open a pull-request, and follow the instruction of the reviewer, if needed.

### Write new tutorials or assignments
If you want to share a new tutorial, please follow this procedure:
 - fork this repository
 - in your fork: add your notebook at the root of the repository. Choose a comprehensive name. Remember to add your personal details if you wish (e.g., name, link to github account) in the header. All the tutorial are meant to be shared with the same licence than the repository (https://github.com/3D-ARD/3d-ard-python-tutorials/blob/main/LICENSE). Please keep your $
 - commit and push to your fork
 - open a pull-request, and follow the instruction of the reviewer, if needed.

