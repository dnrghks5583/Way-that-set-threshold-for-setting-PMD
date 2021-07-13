# Way-that-set-threshold-for-setting-PMD
 201624447 김욱환 
 
 201624462 김한영


TABLE FOR 
 * ResNet-56, EPOCH : 100, BATCH : 128, Initial Learning Rate : 0.001
     ||CALTECH-101 | CALTECH-256| CIFAR-10 | CIFAR-100|
     |-----|-----|-----|-----|-----|
     |BUILTED MODEL|loss: 0.8956, accuracy:0.8403|loss: 3.1238, accuracy:0.5647|loss: 1.6422, accuracy:0.8079|loss: 6.9260,  accuracy:0.4518|
     |EXISTING MODEL|loss: 1.9486, accuracy:0.7583|loss: 4.4605, accuracy:0.5168|loss: 0.5328, accuracy:0.9153|loss: 1.8815,  accuracy:0.6797|  
  
 * ResNet-56, ResNet-32 Comparison with EPOCH : 200, BATCH : 32, Initial Learning Rate : 0.001
      ||CALTECH-101 | CALTECH-256| CIFAR-10 | CIFAR-100|SIFAR-10|
      |-----|------|------|------|------|------|
      |RestNet-56|loss: 1.7210,  accuracy:0.7753, Best at EPOCH-120 |loss: 3.9402 ,  accuracy:0.5289, Best at EPOCH-124|loss: 0.4284, accuracy:0.9228, Best at-EPOCH 135|loss: 1.6735, accuracy:0.6983, Best at EPOCH-125|loss: 1.0106, accuracy:0.8224, Best at EPOCH-195|
      |ResNet-32|loss: 1.8885,  accuracy:0.7654, Best at EPOCH-156 |NA|loss: 0.4350, accuracy:0.9216, Best at-EPOCH 199|loss: 1.6230, accuracy:0.6938, Best at EPOCH-140|loss: 0.9617, accuracy:0.8195, Best at EPOCH-170|
