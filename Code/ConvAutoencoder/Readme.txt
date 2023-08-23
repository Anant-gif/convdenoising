Setup/Installation instructions:

Method 1
1. Create a virtual environment using Python 3.7 or higher.
    '''
    virtualenv conv
    ''' 
2. Activate the virtual environment.
    '''
     source conv/bin/activate
    '''
3. Install the required libraries using the following command:
    ```
    pip install -r requirements.txt
    ```
4. Run the `gaussian_denoising_autoencoder.ipynb` notebook to train and test the denoising autoencoder.

Files in the 'ConvAutoencoder' folder:
- `gaussian_denoising_autoencoder.ipynb`: Main script containing the implementation of the denoising autoencoder model, training, testing, and visualization of results.
- `requirements.txt`: Lists the required libraries.

Method 2 

1. Open the notebook file in Google Colab.

2.Run the following command first
    pip install pytorch_msssim

3.Run the notebook 'gaussian_denoising_autoencoder.ipynb'.