# UAS_linear-regression_Purnomo_171011402245
UAS_Kecerdasan_Buatan


# -*- coding: utf-8 -*-
"""
Created on Mon Nov 16 03:03:58 2020

@author: purna
"""
import numpy as np
import pandas as pd
from matplotlib import pyplot as plt
from sklearn.linear_model import LinearRegression
X = [[6], [8], [10], [14], [18]]
y = [[7], [9], [13], [17.5], [18]]
plt.figure()
plt.title('Pizza price plotted against diameter')
plt.xlabel('Diameter in inches')
plt.ylabel('Price in dollars')
plt.plot(X, y, 'k.')
plt.axis([0, 25, 0, 25])
plt.grid(True)
plt.show()
