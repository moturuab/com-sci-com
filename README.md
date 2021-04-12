# Computer Science Communication

- Student Name: Abhishek Moturu
- Student #: 1001019925

## Sharing

I will post the image along with an explanation on my personal twitter [@AbhishekMoturu](https://twitter.com/AbhishekMoturu) and am comfortable being retweeted by [@ProbablyLearn](https://twitter.com/ProbablyLearn).

## Generative Adversarial Networks (GANs)

![](./gan-horse.png)

Source: [Meme Generator](https://imgflip.com/i/558lk5)

This image is a representation of how the minimax two-player game between the Generator and Discriminator in a GAN (in this case, trained using a dataset of pencil sketches of horses) looks like. The Generator initially performs very poorly and the Discriminator can easily tell the difference between a real image (from the training data distribution) and a fake image (created by the Generator, which maps from a latent space to an image space). Over time, as we train the GAN, the images generated by the Generator become essentially indistinguishable from those in the training data distribution, i.e. the Discriminator can no longer tell the difference between a real image and a fake image. We see this depicted above as the horse drawing improves over time.

![](./gan-office.png)

Source: [Meme Generator](https://imgflip.com/i/559d8n) (My thanks to Sasha Doubov for inspiring me.)

In a similar line of thought as in the previous image, this image is a representation of the state of a GAN after successful training, once a unique solution is found. The Generator is able to generate images that perfectly match those in the training data distribution. So, at the end, the Discriminator will no longer be able to tell the difference between a real image (from the training data distribution) and a generated image (from the Generator). We see this depicted above as the real image and the generated image being "the same picture".

The following is a technical explanation of GANs:



Source: [Generative Adversarial Nets](https://arxiv.org/abs/1406.2661)
