The catalogue should be constructed in this way

![img.png](catalogue.png)

Environment setup:

```text
conda create --name name_of_env python=3.9
```

```text
pip install numpy opencv torch torchvision PIL tqdm matplotlib 
```

For svm, you can install cjlin from the link in assignment document.
or

```text
pip install libsvm-official==3.30.0
```

And I have tried these packages, they are the same, so the libsvm-official is preferred.
But the import approach have some different.

```text
# for libsvm-official
from libsvm.svm import svm_problem, svm_parameter
from libsvm.svmutil import svm_train, svm_predict
```

```text
# for cjlin
from libsvm.python.libsvm.svmutil import *
from libsvm.python.libsvm.svm import *
```

Run the code:
All the codes are implemented and run in Jupyter notebook.The results are already
saved and if you need to rerun the codes, just do that sequentially from top.

Note: remember to replace the path of PIE and own photos to the folder address on your
computer. If you do not install torchvision, just annotate the relevant code, they are used to test.

And if you want to change the experiment results, you can change variable 'seed', which ensure the experiment can be
reproduced.