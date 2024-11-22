### Computer Vision Group - RWTH

1. S3DIS dataset can be downloaded <a href="https://goo.gl/forms/4SoGp4KtH1jfRqEj2">here (4.8 GB)</a>. 
Download the file named `Stanford3dDataset_v1.2.zip`, uncompress the data and move it to `../../Data/S3DIS`. If you want to place your data anywhere else, you just have to change the variable 
`self.path` of `S3DISDataset` class ([here](https://github.com/HuguesTHOMAS/KPConv-PyTorch/blob/afa18c92f00c6ed771b61cb08b285d2f93446ea4/datasets/S3DIS.py#L88)).

2. Create a virtual environment and activate it:

        virtualenv .venv
        source .venv/bin/activate

3. Install the dependencies:
     
        pip install -r requirements.txt

4. Compile the CPP wrappers:

        cd cpp_wrappers
        bash compile_wrappers.sh

Note: Right now only integrated for S3DIS dataset