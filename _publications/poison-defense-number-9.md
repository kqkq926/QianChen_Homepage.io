---
title: "Poisoning attack detection scheme based on generative adversarial network for federated learning"
collection: Journal of Computer Applications
excerpt: '**Qian Chen**, Zheng Chai, Zilong Wang, Jiawei Chen'
date: 2023-12-10
venue: 'Journal of Computer Applications'
paperurl: 'http://www.joca.cn/CN/abstract/abstract25970.shtml'
---
**Abstract:** Federated Learning （FL） emerges as a novel privacy-preserving Machine Learning （ML） paradigm. However， the distributed training structure of FL is more vulnerable to poisoning attack， where adversaries contaminate the global model through uploading poisoning models， resulting in the convergence deceleration and the prediction accuracy degradation of the global model. To solve the above problem， a poisoning attack detection scheme based on Generative Adversarial Network （GAN） was proposed. Firstly， the benign local models were fed into the GAN to output testing samples. Then， the testing samples were used to detect the local models uploaded by the clients. Finally， the poisoning models were eliminated according to the testing metrics. Meanwhile， two test metrics named F1 score loss and accuracy loss were defined to detect the poisoning models and extend the detection scope from one single type of poisoning attacks to all types of poisoning attacks. Besides， a threshold determination method was designed to deal with misjudgment， so that the robust of misjudgment was confirmed. Experimental results on MNIST and Fashion-MNIST datasets show that the proposed scheme can generate high-quality testing samples， and then detect and eliminate poisoning models. Compared with the global models trained with the detection scheme based on directly gathering test data from clients and the detection scheme based on generating test data and using test accuracy as the test metric， the global model trained with the proposed scheme has significant accuracy improvement from 2.7 to 12.2 percentage points.

