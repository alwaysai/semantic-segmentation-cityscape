# Semantic Segmentation Cityscape
Use [Semantic Segmentation](https://alwaysai.co/docs/application_development/core_computer_vision_services.html#semantic-segmentation) to determine a class for each pixel of an image. The classes of objects detected can be changed by selecting different models. This particular starter application uses a model trained on the [Cityscapes Dataset](https://www.cityscapes-dataset.com/). The Cityscapes Dataset focuses on semantic understanding of urban street scenes, and is a favorite dataset for building autonomous driving machine learning models.

## Requirements
* [alwaysAI account](https://alwaysai.co/auth?register=true)
* [alwaysAI Development Tools](https://alwaysai.co/docs/get_started/development_computer_setup.html)

## Usage
Once the alwaysAI tools are installed on your development machine (or edge device if developing directly on it) you can install and run the app with the following CLI commands:

To perform initial configuration of the app:
```
aai app configure
```

To prepare the runtime environment and install app dependencies:
```
aai app install
```

To start the app:
```
aai app start
```

Different images can be used by updating the files in the *images/* directory. Note that when developing for a remote device, removing images in the local *images/* directory won't remove images from the device. They can be removed using the `aai app install --clean` command.

To change the computer vision model, the engine and accelerator, and add additional dependencies read [this guide](https://alwaysai.co/docs/application_development/configuration_and_packaging.html).

## Support
* [Documentation](https://alwaysai.co/docs/)
* [Community Discord](https://discord.gg/z3t9pea)
* Email: support@alwaysai.co