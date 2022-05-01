# CS-112-Project
#Oluwatoyosi Adeleke 
import numpy as np


def variance(data):
  n = len(data)
  mean = sum(data) / n
  deviations = [(x - mean) ** 2 for x in data]
  variance = sum(deviations) / n
  return variance
 
def stdev(data):
  import math
  var = variance(data)
  std_dev = math.sqrt(var)
  return std_dev

def CreateList(data):
  data = int(input("Enter a string of  10 numbers seperted by commas:"))
  data = range not (68,80)
 
  
 
print("Standard Deviation of the sample is % s "% (stdev(data)))

