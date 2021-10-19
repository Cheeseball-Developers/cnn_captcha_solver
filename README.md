# Convolutional Neural Network for Solving 'Really Simple Captcha'

A deep learning based approach to solve captchas provided by a popular wordpress plugin called [Really Simple Captcha](https://wordpress.org/plugins/really-simple-captcha/) which is used by nearly *1 million websites*.



<img src="https://github.com/Cheeseball-Developers/cnn_captcha_solver/blob/master/README/captcha.png" alt="drawing" width="100"/> <img src="https://github.com/Cheeseball-Developers/cnn_captcha_solver/blob/master/README/captcha_letters.png" alt="drawing" width="100"/>

## Development

#### Generating Captchas and Extracting Letters

- For generating captchas we downloaded the source code of Really Simple Captcha, hacked the code a bit and made it generate 100k captchas for training our model.
- Using OpenCV in python, we followed some image pre-processing steps and extracted single letters from the generated captcha set and sorted the letters into folders of each letter.

#### Training the Model

- Develeoped and trained a Deep Convolutional Neural Net using Keras.


This project was inspired by a [Medium Article](https://medium.com/@ageitgey/how-to-break-a-captcha-system-in-15-minutes-with-machine-learning-dbebb035a710)
#### If you liked the project, please :star: the repo!
