Hands-On Machine Learning
=================================

Collection of jupyter notebooks following the third edition of the O'Reilly book [Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow (3rd edition)](https://homl.info/er3):

<a href="https://homl.info/er3"><img src="https://learning.oreilly.com/library/cover/9781098125967/300w/" title="book" width="150" border="0" /></a>

## Quick Start
1. Navigate to the one of the chapter directories
2. Run the following

```bash
# Create environment from environment.yml
conda env create -f environment.yml

# Activate the environment
conda activate <env>

# Register the environment as a Jupyter kernel
python -m ipykernel install --user --name <env>-kernel --display-name "Python (<env>)"
```

*note: In some cases the input data may be too large to include in the repository. I'll add a comment at the top of those notebooks on how to retrieve the data.*