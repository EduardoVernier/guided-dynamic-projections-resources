---
title: Trails colored by time
---
# Trails

<img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/magma.png?raw=true" alt="-" style="width:20%">

{{< expand "1. cartolastd - 696 observations - 19 timesteps - 17 dimensions - 5 classes" "..." >}}
The dataset was scrapped from the Brazilian fantasy soccer platform Cartola and represents the second turn of the 2017 championship. The scrapper source can be found at https://github.com/henriquepgomide/caRtola. To make the dataset smoother, the dimensions were cumulatively averaged.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-pca_s1.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-AE_10f_10f_2f_50ep.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-VAE_10f_10f_2f_100ep.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-pca_s4.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
	<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-ctsne-p30.png?raw=true" alt="-" style="width:100%">
	<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-cumap.png?raw=true" alt="-" style="width:100%">
	<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-dtsne_100p_0-1l.png?raw=true" alt="-" style="width:100%">
  </tr>
	<tr width="100%" padding="0" margin="0">
	<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-pcadtsne-p30-l0_010000-le1.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cartolastd-ldtsne-p30-l0_2000-ge2-le4-krandom-n-PCA.png?raw=true" alt="-" style="width:100%">
  </tr>
</table>
{{< /expand >}}


{{< expand "2. cifar10cnn - 1000 observations - 30 timesteps - 10 dimensions - 10 classes" "..." >}}
I took the example CNN available at the keras website (https://keras.io/examples/cifar10_cnn/) and looked at the output of the last layer after each epoch for 1000 images of the validation set. After 30 epochs the CNN had an accuracy of 0.6950.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-pca_s1.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-AE_10f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-pca_s4.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-ctsne-p30.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-cumap.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-dtsne_30p_0-1l.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-pcadtsne-p30-l0_000010-le1-ls1_00.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-cifar10cnn-ldtsne-p30-l0_5000-ge4-le1-krandom-n-TSNE.png?raw=true" alt="-" style="width:100%">
  </tr>
</table>
{{< /expand >}}


{{< expand "3. esc50 - 320 observations - 108 timesteps - 128 dimensions - 8 classes" "..." >}}
Sound samples of 8 classes (brushing_teeth, chainsaw, crying_baby, engine, laughing, rain, siren, wind) compressed to 128 frequencies and smoothed over time. Collected from https://github.com/karoldvl/ESC-50 by K. J. Piczak.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-pca_s1.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-AE_10f_10f_2f_40ep.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">  
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-pca_s4.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
  </tr>
  <tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-ctsne-p30.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-cumap.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-dtsne_40p_0-05l.png?raw=true" alt="-" style="width:100%">
  </tr>
	<tr width="100%" padding="0" margin="0">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-pcadtsne-p30-l0_010000-le1-ls0_10.png?raw=true" alt="-" style="width:100%">
  <td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-esc50-ldtsne-p30-l0_3000-ge5-le1-krandom-n-PCA-1585573963.png?raw=true" alt="-" style="width:100%">
  </tr>
</table>
{{< /expand >}}


{{< expand "4. fashion - 1000 observations - 10 timesteps - 784 dimensions (28x28 pixels) - 10 classes" "..." >}}
100 images from each class (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot) were selected and added decreasing amounts of noise.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-AE_784f_500f_500f_2000f_2f_40ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-VAE_784f_2048f_1024f_512f_2f_0-25drop_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-ctsne-p30.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-dtsne_100p_0-1l.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
</tr>
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-pcadtsne-p30-l0_000100-le1-ls0_10.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-fashion-ldtsne-p30-l0_1000-ge4-le2-krandom-n-TSNE-1585735654.png?raw=true" alt="-" style="width:100%">
</table>
{{< /expand >}}


{{< expand "5. gaussians - 2000 observations - 10 timesteps - 100 dimensions - 10 classes" "..." >}}
Dataset from Rauber et. al's dt-sne paper. “We create the multivariate Gaussians dataset specifically as a controlled experiment for dynamic t-SNE. Firstly, we sample 200 observations from each of 10 distinct (isotropic) 100-dimensional multivariate Gaussian distributions with variance 0.1. We combine the resulting 2000 observations into a single dataset D[1]. Each multivariate Gaussian has a distinct mean, which is chosen uniformly between the standard basis vectors for R 100 . Given D[t], the dataset D[t + 1] is created as follows. Each observation x[t + 1] ∈ D[t + 1] corresponds to an observation x[t] ∈ D[t] moved 10% of the remaining distance closer to the mean of its corresponding multivariate Gaussian. In simple terms, each of the 10 clusters becomes more compact as t increases. We consider T = 10 datasets.”

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-AE_10f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-dtsne_70p_0-1l.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-ctsne-p30.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-pcadtsne-p30-l0_001000-le1-ls10_00.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-gaussians-ldtsne-p30--interactive-krandom-n-PCA.png?raw=true" alt="-" style="width:100%">
</tr>
</table>
{{< /expand >}}


{{< expand "6. nnset - 80 observations - 30 timesteps - 8070 dimensions - 8 classes" "..." >}}
This dataset represents the internal states (weights and biases) of a set of neural networks learning to classify MNIST with same architecture but using different optimizers, batch sizes, training data sizes. There doesn't seem to be a clear class separation in this dataset.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-AE_10f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-ctsne-p30.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-dtsne_60p_0-01l.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-pcadtsne-p30-l0_001000-le1-ls1_00.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-nnset-ldtsne-p30-l0_0200-ge8-le1-krandom-n-PCA-1585825808.png?raw=true" alt="-" style="width:100%">
</tr>
</table>
{{< /expand >}}


{{< expand "7. qtables - 180 observations - 40 timesteps - 1200 dimensions - 9 classes" "..." >}}
Each observation is an agent learning to move a car up a hill using the reinforcement learning algorithm Q-learning. The classes represent variations of learning rates and discounts. The car has 3 actions, and the decision space has 2 features, each divided into 20 discrete steps. Therefore the dataset is 3x20x20 or 1200 dimensions. Code based on this tutorial: https://pythonprogramming.net/q-learning-reinforcement-learning-python-tutorial/.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-AE_10f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-ctsne-p30.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-dtsne_40p_0-05l.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-pcadtsne-p30-l0_001000-le1-ls0_10.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-qtables-ldtsne-p30--interactive-krandom-n-PCA.png?raw=true" alt="-" style="width:100%">
</tr>
</table>
{{< /expand >}}


{{< expand "8. quickdraw - 600 observations - 89 timesteps - 784 dimensions (28x28 pixels) - 6 classes" "..." >}}
Google has a little fun project called Quick Draw (https://quickdraw.withgoogle.com/data). It’s a website where they give you a few seconds to draw some object while a neural network is trying to guess what is it that you are trying to draw. What I did was extract drawing sequences for 600 objects of 6 different classes drawn by random people. In my sample, each final drawing is composed of an average of 36.1 partial drawings. Each image is a 28x28 pixel binary map.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-AE_784f_500f_500f_2000f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-VAE_784f_2048f_1024f_512f_2f_0-25drop_10ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-ctsne-p30.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-dtsne_200p_0-1l.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-pcadtsne-p30-l0_001000-le1-ls1_00.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-quickdraw-ldtsne-p30-l0_1000-ge2-le1-krandom-n-TSNE-1585997292.png?raw=true" alt="-" style="width:100%">
</tr>
</table>
{{< /expand >}}


{{< expand "9. sorts - 80 observations - 100 timesteps - 100 dimensions - 8 classes" "..." >}}
Intermediate states of 8 sorting algorithms. Arrays initially have 100 random elements. Based on franciscouzo.github.io/sort/

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-AE_10f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-ctsne-p30.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-dtsne_77p_0-01l.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-pcadtsne-p30-l0_010000-le1-ls1_00.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-sorts-ldtsne-p30-l0_2500-ge10-le2-krandom-nt-PCA-1592723377.png?raw=true" alt="-" style="width:100%">
</tr>
</table>
{{< /expand >}}


{{< expand "10. walk - 300 observations - 50 timesteps - 100 dimensions - 3 classes" "..." >}}
There are three classes, in one the values of the dimensions start low and go high, one the values start high and decrease over time, and in the last, they stay roughly the same. For all of them, there is noise added (see example). This is supposed to be a "ground-truth" dataset with simple dynamics.

<table  width="100%" padding="0" spacing="0" border="0" cellpadding="0" cellspacing="0" style="border-collapse:collapse">
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-pca_s1.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-tsne_s1_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-umap_s1_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-AE_10f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-VAE_100f_10f_2f_20ep.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-pca_s4.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-tsne_s4_30p.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-umap_s4_15p.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-ctsne-p30.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-cumap.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-dtsne_100p_0-01l.png?raw=true" alt="-" style="width:100%">
</tr>
<tr width="100%" padding="0" margin="0" cellpadding="0" cellspacing="0">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-pcadtsne-p30-l0_000100-le1-ls1_00.png?raw=true" alt="-" style="width:100%">
<td> <img src="https://github.com/EduardoVernier/guided-dynamic-projections-resources/blob/main/static/colored_by_time/trails-walk-ldtsne-p30--interactive-krandom-n-PCA.png?raw=true" alt="-" style="width:100%">
</tr>
</table>
{{< /expand >}}
