# LSTM-Generative-and-Descriminative

Using LSTM neural network model for accurate text generation.

In this project, I create 2 LSTM networks: A generative network and a descriminative one. The generative network simply creates text. The descriminative network is trained to tell the difference between the generated text and human-written text. The hope is that we can train the generative network to maximize the probability that the descriminative network thinks its generated text is human.

This is similar to the generative adversarial network (GAN) developed by Goodfello et al, 2014.

The generative model is written in generator.py. The descriminative model will be written in descriminator.py.
