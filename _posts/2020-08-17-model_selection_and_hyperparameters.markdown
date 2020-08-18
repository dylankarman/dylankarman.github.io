---
layout: post
title:      "Model Selection and Hyperparameters"
date:       2020-08-18 01:03:01 +0000
permalink:  model_selection_and_hyperparameters
---


The process of choosing a model and selecting the correct hyperparameters was very challenging for me at first. Having had absolutely zero experience in the field, I honestly had no idea what was going on. What the heck is a model in the first place? And what the heck are hyperparameters??! Let's take a look so youre not as confused as I was (hopefully). 

First of all, a model is just a fancy work for an algorithm, and depending on what you are doing, different models will suit your needs differently. It is very important to test a plethora of vanilla models (models that have not had their hyperparameters altered) on your training data before you move on to finding out what hyperparameters you should use. Oh yeah. What the heck are those?

Once you have tested your models on your training data and you have selected the model that fits your needs, you are ready to edit the hyperparameters of that model. Im sure there is a really old and drawn out method that takes a really long time to do to accomplish this task, but lucky for us, we have randomgridsearch and gridsearchcv! Random grid search will pick certain hyperparameters in a grid outlined by you, and randomly test them along the way. Gridsearchcv does the same thing but tests every single hyperparameter along the way. You can use both of these programs in tandem to make your life much easier.

I hope this very short explanation helps a little bit. Dont worry, youll get it eventually!
