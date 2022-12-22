---
title: "Accepted paper at the International Symposium on Intelligent Data Analysis"
date: 2022-01-01T00:00:00-00:00
categories:
  - paper
tags:
  - VAE
---

Our paper entitled ["MuseBar: Alleviating Posterior Collapse in Recurrent VAEs toward Music Generation"](/assets/publications/ida22.pdf) has been accepted at 
the [International Symposium on Intelligent Data Analysis 2022](https://ida-2022.org/).

### Abstract
Machine learning has shown remarkable artistic values and commercial potentials in the music industry. Recurrent variational
autoencoders (RVAEs) have been widely applied to this area due to the condensing, inclusive, and smooth nature of their latent space. However, RNNs are powerful auto-regressive models on their own, where the decoder in a RVAE can be strong enough to work independently from the encoder. When this happens, the model degrades from an autoencoder to a traditional RNN, which is known as posterior collapse. In this paper, we propose a cost-effective bar-wise regulation schema called MuseBar to alleviate this problem for music generation. We impose a prior on the hidden state of every music bar in the RNN encoder, instead of only on the last hidden state as in the standard RVAEs, such that the latent code is learned under stronger regulations. We further evaluate our proposed method, quantitatively and qualitatively, with extensive experiments on manually scraped musical data. The results demonstrate that the barwise regulation significantly improves the quality of the latent space in terms of Mutual Information and Kullback-Leibler divergence.
