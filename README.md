Explanation for the various notebooks:

0. In the first notebook you will be exploring the capabilities of the model downloaded from huggingface - this is a step to evaluate the model from their API and understand the capabilities and to check the result after.
1. In the second notebook you will clone the model from huggingface and save it to a local repository "my_folder/"
2. In order to test the model, you will check if the result on the same picture equals the result from the first step.
3. Then the notebook will be stored in S3 storage for easier access from different notebooks with permission for this storage.
4. Here we are testing if the saved model is correctly inferenced even from S3 storage.
5. We are serving the model here from OVMS to understand if the result is the same from an API request. Compare with the results from step 0. 

To be cloned in JupyterLab after deployment of the RHOAI demo pack from https://github.com/mamurak/os-mlops.
