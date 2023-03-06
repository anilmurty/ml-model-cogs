# Cogs for common AI/ ML models

This repository contains cog packages for many common AI & ML models that can be run as containers. This makes use of https://github.com/replicate/cog/blob/main/docs/getting-started.md for building containerized images from commonly available models.

## Motivation

My motivation in building this was to have a repository of containerized reference models that can be quickly spun up and used by anyone (inluding me) building applications using them

## Structure

The structure of this directory will be Model/Platform | Specific Model (for e.g /tensorflow/bert)
In each directory there will be a cog.yaml file and a predict.py file. These will can be used in conjunction with the examples under https://github.com/anilmurty/ml-model-deployment-experiments


