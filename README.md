# Way-that-set-threshold-for-setting-PMD
 201624447 김욱환 
 
 201624462 김한영


TABLE FOR 
 * ResNet-56, EPOCH : 100, BATCH : 128, Initial Learning Rate : 0.001
     ||CALTECH-101 | CALTECH-256| CIFAR-10 | CIFAR-100|
     |-----|-----|-----|-----|-----|
     |MADE UP MODEL|loss: 0.8956, accuracy:0.8403|loss: 3.1238, accuracy:0.5647|loss: 1.6422, accuracy:0.8079|loss: 6.9260,  accuracy:0.4518|
     |EXISTING MODEL|loss: 1.9486, accuracy:0.7583|loss: 4.4605, accuracy:0.5168|loss: 0.5328, accuracy:0.9153|loss: 1.8815,  accuracy:0.6797|  
  
 * ResNet-56, ResNet-32 Comparison with EPOCH : 200, BATCH : 32, Initial Learning Rate : 0.001
      ||CALTECH-101 | CALTECH-256| CIFAR-10 | CIFAR-100|STL-10|Linnaeus-5|
      |-------|-------|-------|-------|-------|-------|-------|
      |RestNet-56|loss: 1.4723,  accuracy:0.7835, Best at EPOCH-138 |loss: 3.9402 ,  accuracy:0.5289, Best at EPOCH-124|loss: 0.4284, accuracy:0.9228, Best at-EPOCH 135|loss: 1.6735, accuracy:0.6983, Best at EPOCH-125|loss: 1.0106, accuracy:0.8224, Best at EPOCH-195|loss: 0.6939, accuracy:0.8835, Best at EPOCH-151|
      |ResNet-32|loss: 1.5656,  accuracy:0.7731, Best at EPOCH-142 |loss: 3.8459,  accuracy:0.5203, Best at EPOCH-152 |loss: 0.4350, accuracy:0.9216, Best at-EPOCH 199|loss: 1.6230, accuracy:0.6938, Best at EPOCH-140|loss: 0.9617, accuracy:0.8195, Best at EPOCH-170|loss: 0.6186, accuracy:0.8885, Best at EPOCH-105|


Threshold v1 
 * Static threshold 0.1, 0.2, 0.3, 0.4, 0.5, 0.6, 0.7, 0.8, 0.9 
 * Dynamic threshold = 95%, 97.5%, 99% one-tails


Threshold v2 
 * Static threshold 0.0000001, 0.000001, 0.00001, 0.00005, 0.0001, 0.0005, 0.001, 0.01, 0.05, 0.1, 0.2, 0.3, 0.4, 0.5 
 * Dynamic threshold = 95%, 97.5%, 99% one-tails


Threshold FINAL 
 * Static threshold 0.0000001, 0.000001, 0.00001, 0.00005, 0.0001, 0.0005, 0.001, 0.01, 0.05, 0.1, 0.2, 0.3, 0.4, 0.5 
 * Dynamic threshold = min * Alpha (Alpha = 0.05, 0.1, 0.2, 0.3, 0.4, 0.5)
