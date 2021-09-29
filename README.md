# Object-Detection-with-TFJS

## Working Demo
A working demo can be found at [santhtadi.github.io](https://santhtadi.github.io/Object-Detection-with-TFJS)

# Introduction
This project show cases the use of Tensorflow JS, a JavaScript library released by Tensorflow, for Object Detection.

## Advantages
Tfjs addressed the most common problem with deployment of DL models - Setting up the environment.

With tfjs the model outputs can be shown right in the browser, making it available and easier to use for a larger demographic.

Leveraging the tfjs script we can run inferences on the client-side with virtually no setup.

## Disadvantages
Inconsistent User Experience (fps, internet speed) can become a problem for systems with various configurations, but that's the case with all websites and browser apps.

# Steps to use this Repo with Custom Object Detector

1. Train a MobileNet model from the references given below.
2. Freeze the model.
3. Convert to tfjs format (json and bin files).
4. Use a cloud service to provide the json and model files like IBM or AWS (I used the one hosted by google at https://storage.googleapis.com/tfjs-models/savedmodel/ssdlite_mobilenet_v2/model.json).
5. Use the script script.js to run inference

# References
The tutorial for generating a [MobileNet SSD model](https://www.youtube.com/watch?v=yqkISICHH-U)

The tutorial for inferencing in browser [Google codeLabs](https://codelabs.developers.google.com/codelabs/tensorflowjs-object-detection)

