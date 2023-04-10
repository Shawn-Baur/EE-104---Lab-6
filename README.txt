Name: Shawn Baur
Class: EE 104

Videos: 
GitHub: 

About this code:

# Baseline
Model training script for training an image recognition module that can reconize immages based on the CNN dataset.

# Challenge Test
Tests the model trained in the earlier section using images found on the web, evaluting it's skill to recognize images.

# Happy Garden
Game that has a cow that waters wilting flowers which periodically turn into monsters and try to attack the cow.

# Hello World to OpenAI
Script that accesses OpenAI to create a local website that can be used for name generation.

# Hello World to ChatGPT
Script that accesses ChatGPT and allows you to ask questions to the model the same as the website version.

***MAKE SURE THAT THE FOLLOWING PYTHON MODULES ARE INSTALLED***

import sys
from matplotlib import pyplot
from keras.datasets import cifar10
from keras.utils import to_categorical
from keras.models import Sequential
from keras.layers import Conv2D
from keras.layers import MaxPooling2D
from keras.layers import Dense
from keras.layers import Flatten
from keras.optimizers import SGD
from keras.preprocessing.image import ImageDataGenerator
from keras.layers import Dropout
from keras.layers import BatchNormalization

from random import randint
import time
import pgzrun
import pygame
import pgzero
from pgzero.builtins import Actor

import os
import openai #remember to pip install pandas openai
from dotenv import load_dotenv  #remember to pip install python-dotenv

import openai
from flask import Flask, redirect, render_template, request, url_for
