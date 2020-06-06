# Image Super Resolution Enhancer Using Autoencoders in Keras

We are not new to the cliche of movices involving “*experts*” examining videos and images, before exclaiming “**Enhance!**” to somehow create high-resolution images from low-resolution source images, and then suddenly discovering something earth-shattering to solve a mystery.

Perhaps such technology does not yet exist. But recent advnaces in computation power have brought this magical "*enhancing*" just a little closer to reality.

In this project, I have used **Keras** with **Tensorflow** as its backend to train an **autoencoder neural network**. Using a simple deep learning powered autoencoder, I was able to "*enhance*" the quality of images that traditionally required complex algorithms such as *bicubic interpolation* image processing.

## Instructions:

To train the model, store any high-resolution images in the `data/cars_train` folder.

Run the `Image_Super_Resolution.ipynb` Jupyter notebook to train and use the image "*enhancer*". Specify `just_load_dataset = False` in the `train_batches` function to train the model.

Otherwise, a pre-trained model can be loaded by specifying `just_load_dataset = True`.

## Installations:

```
pip3 install -r requirements.txt
```
* scipy
* skimage
* matplotlib 
* numpy
* tensorflow

## File Description:

* `encoder_weights.hdf5` - optimal encoder model weights
* `sr.img_net.mse.final_model5.no_patch.weights.best.hdf5` - optimal autoencoder model weights

## Licensing, Authors, and Acknowledgements:

The base code is provided by Coursera as part of a Guided Project.

[MIT License]()