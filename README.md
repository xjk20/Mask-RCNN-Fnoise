# Mask-RCNN-Fnoise
Solved:

1.  Clone a repo containing detectron2 Mask-RCNN architecture. (Can change individual layers)
2.	Imported COCO dataset from a github repo and demonstrate that the chosen implementation is able to learn and perform inferences.

Unsolved:

3.	Change the network architecture of the Mask-RCNN implementation so that "F-Noise" (i.e. a noise that is proportional to the magnitude of the features in the latent space) is applied to the latent space of the backbone encoder network (the first encoder that is used to predict heat-maps of relevant features). This perturbation should only be applied during training. Bonus points: Visualise the perturbation on the latent space during training & inference.

What is F-noise (Pink noise)?

Pink noise or 1⁄f noise is a signal or process with a frequency spectrum such that the power spectral density (power per frequency interval) is inversely proportional to the frequency of the signal. In pink noise, each octave interval (halving or doubling in frequency) carries an equal amount of noise energy. Pink noise is one of the most common signals in biological systems. The name arises from the pink appearance of visible light with this power spectrum. This is in contrast with white noise which has equal intensity per frequency interval. 


Partially solved:


4.	Plot a side by side loss comparison between training with and without F-Noise.

Total Loss(without F-noise):

![loss](https://user-images.githubusercontent.com/64022189/138560047-f14ac20c-b3db-4bab-bded-bfb6c8f0ba3e.png)
