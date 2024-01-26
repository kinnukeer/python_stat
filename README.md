# python_stat
#python code to demonstrate the working of
#variance() function of statistics module
#importing statistics module
import statistics
#creating a sample of data
sample=[2.74,1.23,2.63,2.22,3,1.98]
#prints variance of the sample set
#function will automatically calculate
#it's mean and set it as xbar
print("variance of sample set is % s" %(statistics.variance(sample)))
