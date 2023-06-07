# CLSNet
A demo implementation of the split FashionMNIST-10/5 experiment described in the submission, entitled **Complementary Learning Subnetworks for Parameter-Efficient Class-Incremental Learning**.

**Installation & Requirements**
The current version of the codes has been tested with Python 3.7.13 on both Windows and Linux operating systems with the following versions of requirements: numpy==1.17.0 scipy==1.5.0 scikit-learn==0.23.1 torch==1.10.2 torchvision==0.11.3

**How To Use**
Please create an environment to run the basic code: python main.py

**Note**
The default setting performs 5 random task-order runs, as reported in our experiments.
No pre-trained CNN feature extractor is used for FashionMNIST-10/5 as a simple model already generates very good results, as described in the manuscript.
