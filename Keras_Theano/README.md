### Theano backend with Keras

cd into your root directory

create a folder named ".keras"

cd into the folder and create a file named "keras.json"

Edit the file with vim: vim keras.json

Paste the following code: 

{
    "image_dim_ordering": "th",
    "epsilon": 1e-07,
    "floatx": "float32",
    "backend": "theano"
}

Press "Esc" Button

To Save & Exit: :x




For Tensorflow Backend:

{
    "image_data_format": "channels_last",
    "epsilon": 1e-07,
    "floatx": "float32",
    "backend": "tensorflow"
}


### Alternately: - 

KERAS_BACKEND=theano python mymodel.py (In your CLI)
