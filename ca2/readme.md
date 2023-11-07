The catalogue should be constructed in this way

![img.png](catalogue.png)

Environment setup:

conda create --name name_of_env python=3.9

pip install opencv

pip install torch

pip install SVMLib or pip install libsvm-official==3.30.0

(the SVMlib may have some bug in different version and operation system, so the libsvm-official is preferred)

Run the code:
All the codes are implemented and run in Jupyter notebook.The results are already
saved and if you need to rerun the codes, just do that sequentially from top.

Note: remember to replace the path of PIE and own photos to the folder address on your
computer. If you do not install torchvision, just annotate the relevant code, they are used to test.

And if you want to change the experiment results, you can change variable 'seed', which ensure the experiment can be reproduced.