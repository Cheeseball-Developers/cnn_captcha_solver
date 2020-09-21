# CNN Model for Solving 'Really Simple Captcha'

This project solves captchas provided by a popular wordpress plugin called [Really Simple Captcha](https://wordpress.org/plugins/really-simple-captcha/) which is used by nearly 1 million websites.

This project was inspired by a [Medium Article](https://medium.com/@ageitgey/how-to-break-a-captcha-system-in-15-minutes-with-machine-learning-dbebb035a710)

<img src="https://github.com/Cheeseball-Developers/cnn_captcha_solver/blob/master/README/captcha.png" alt="drawing" width="100"/> <img src="https://github.com/Cheeseball-Developers/cnn_captcha_solver/blob/master/README/captcha_letters.png" alt="drawing" width="100"/>

## Development

#### Generating Captchas and Extracting Letters

- For generating captchas we downloaded the source code of Really Simple Captcha, hacked the code a bit and made it generate 100k captchas.
- Using OpenCV in python, we extracted single letters from the generated captcha set and sorted the letters into folders of each letter.

#### Training the Model

- We used Scikit-learn to split the data into training and testing sets.
- For CNN model, we used Keras.

#### If you liked the project, please :star: the repo!
