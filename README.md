# Diffusion tflite models

This is a repo that contains a colab notebook which demonstrates the usage of Diffusion models, conversion to .tflite files and final inference with image generation. The original models have been cloned from [this](https://huggingface.co/keras-sd) repo and more info can be found [here](https://github.com/deep-diver/keras-sd-serving).

IMPORTANT = Use TensorFow version 2.9.2 to convert the models inside the notebook as I see that version 2.11.0 creates .tflite files that cannot be used inside android.

TODO = [Tokenizer](https://github.com/keras-team/keras-cv/blob/master/keras_cv/models/stable_diffusion/clip_tokenizer.py) has to be converted to a Java implementation so it can be used inside an android app.
