# Neural-Networks-for-Image-Captioning-Problem
This repository presents a work where, with the help of CNN, RNN and transformer solving the Image Captioning problem on the flickr8k dataset


At the root of the repository there is the code for experiments with the "Show, Attend and Tell" architecture using CNN and Transformer as an encoder, and with various modifications of the decoder.
In the *metrics* folder there are metric changes during training for each architecture.
[Here](https://drive.google.com/drive/folders/1UcDIvNFfotIFpFr4hyg6Io0RPM6ywi0k?usp=sharing) you can download the checkpoints for each model.

[The link](https://github.com/ksana-kozlova/X-VLM) is a fork of the X-VLM repository, where the result folder contains a jupyter notebook with the results of this architecture on the flickr8k dataset. The repository also contains a prepared config for this dataset and json files for train, validation and test datasets. Checkpoints for this architecture are at the [link](https://drive.google.com/file/d/18ZCPAEU2rde4J3xFM5pw5rviXTWZy85h/view?usp=sharing).

Below there is a table of the results of experiments on the Flickr8k dataset.

<img src="https://github.com/ksana-kozlova/Neural-Networks-for-Image-Captioning-Problem/blob/master/results_table.PNG" alt="Table of results">