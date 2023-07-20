# Automated Diagnosis of Membranous Nephropathy Using Convolutional Neural Networks with a Selective Mechanism of Model Evaluation
This repo is for submitted manuscript named "Automated Diagnosis of Membranous Nephropathy Using Convolutional Neural Networks with a Selective Mechanism of Model Evaluation"

According to the data and privacy management policy of the medical institute we are working with, while the manuscript is being reviewed, only validation scripts and data and trained model weights can be provided. After the paper is published, the entire training dataset will be released, along with other related scripts. 

For reviewers to reproduce the results in Figure 7, please follow the steps.


Before running the scripts, we first need to setup the environment.

1. Go to https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html, follow the instructions and install docker and nvidia-docker.
2. Download the docker image from (link), which is a .tar file, and put it in the root directory of the project.
3. Launch the terminal within the project folder and install the docker image with the command "docker load --input demo_docker.tar" (you may need to "sudo")
4. Launch the docker with the following command:

   "(to be filled)"

5. Type "jupyter notebook" and enter to launch the jupyter notebook server from within the docker.
6. Open a web browser and type in "localhost:8888" to access the interface of jupyter notebook.
7. Navigate to the root directory of the project and launch the scripts.

Before runing the scripts, the following preparation needs to be done:   

1. Download the dataset from (link), unzip the file into the root directory.
   
2. Download the trained model from (link), put it in the folder "ckpt/"
   
3. Run the script.
