# The SJTU-AN21 Dataset
The SJTU-AN21 dataset is an anonymity network dataset generated by ten anonymity services.

## Latest Info 
The readme is not completed yet ⚠️

## Introduction
To make the classifier applicable to the current anonymity network traffic analysis, we collected the traffic data generated by ten anonymity services in the latest version of the three most popular anonymity networks (i.e., Tor, I2P, JonDonym).

## SJTU-NSSL Anonymity Network Traffic Dataset (SJTU-AN21) Content
In the SJTU-AN21 dataset, Eepsites, IRC, Snark, and Video are the four main anonymity services in the I2P network, and BitTorrent, Chat, FTP, Streaming, and Browsing are the five main anonymity services in the Tor network. We give a detailed description of the different types of traffic generated:

|Anonymity Services|Network|Training Dataset|Test Dataset|
|--|--|--|
| **Eepsites** |I2P|1,825|1,197|
| **IRC** |I2P|3,009|484|
| **Snark** |I2P|7,284|1,784|
| **Video** |I2P|12,577|581|
| **JonDonym** |JonDonym|1,254|967|
| **Bittorrent** |Tor|198|76|
| **Chat** |Tor|624|150|
| **FTP** |Tor|364|184|
| **Streaming** |Tor|949|598|
| **Browsing** |Tor|1,130|958|

There are 29,214 flows in the training dataset and 6,979 flows in the test dataset. Note that these flows were generated using a lightweight traffic analyzer [Tranalyzer2](https://tranalyzer.com).

## About
Link to our laboratory: [SJTU-NSSL](https://github.com/NSSL-SJTU "SJTU-NSSL")

## Reference

The SJTU-AN21 dataset is publicly available for researchers. If you are using our dataset, you should cite our related research paper:

Ruijie Zhao, Yiteng Huang, Xianwen Deng, Zhi Xue, Jiabin Li, Zijing Huang, and Yijun Wang, "Flow Transformer: A Novel Anonymity Network Traffic Classifier with Attention Mechanism", in *17th International Conference on Mobility, Sensing and Networking (MSN)*, Exeter, UK, Dec. 13-15, 2021, pp. 1--8.

```
@inproceedings{ZRJ-MSN21,
  author    = {Ruijie Zhao and
               Yiteng Huang and
               Xianwen Deng and
               Zhi Xue and
               Jiabin Li and
               Zijing Huang and
               Yijun Wang},
  title     = {Flow Transformer: {A} Novel Anonymity Network Traffic Classifier with
               Attention Mechanism},
  booktitle = {17th International Conference on Mobility, Sensing and Networking (MSN)},
  pages     = {223--230},
  year      = {2021},
  doi       = {10.1109/MSN53354.2021.00045},
}
```

