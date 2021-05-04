# Android App Pakistani Currency Detector App using TensorFlow Lite image classification

## Overview

This is an example application for [TensorFlow Lite](https://tensorflow.org/lite)
on Android. It uses
[Image classification](https://www.tensorflow.org/lite/models/image_classification/overview)
to continuously classify whatever it sees from the device's back camera.
Inference is performed using the TensorFlow Lite Java API. The demo app
classifies frames in real-time, displaying the top most probable
classifications. It allows the user to choose between a floating point or
[quantized](https://www.tensorflow.org/lite/performance/post_training_quantization)
model, select the thread count, and decide whether to run on CPU, GPU, or via
[NNAPI](https://developer.android.com/ndk/guides/neuralnetworks).

These instructions walk you through building and
running the demo on an Android device. For an explanation of the source, see
[TensorFlow Lite Android image classification example](https://www.tensorflow.org/lite/models/image_classification/android).

<!-- TODO(b/124116863): Add app screenshot. -->

### Model
Inside Assests folder zip file is there.

Teachable ML

## Requirements

*   Android Studio 4.1.1 (installed on a Linux, Mac or Windows machine)

*   Android device in
    [developer mode](https://developer.android.com/studio/debug/dev-options)
    with USB debugging enabled

*   USB cable (to connect Android device to your computer)

## Build and run

