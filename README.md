## CS470 Team 5
# Show and Tell : A Neural Image Caption Generator

The aim of this project was to replicate results from Show and Tell: A Neural Image Caption Generator paper. This project was carried out as part of CS470 “Introduction to Artificial Intelligence” course at KAIST.

### Contributors
 - Sangwon Hyun
 - Lingjun Liu
 - Andrei Son
 - Youngrae Kim

### Dataset
We have conducted our experiment on Flicker8k dataset.
 - Training: 6000 Images
 - Validation: 1000 Images
 - Testing: 1000 Images

### Architecture
In the “Show and Tell” paper, the model consists of two parts, which are GoogleNet and LSTM model. The role of the GoogleNet is to extract specific features in a picture, and give basic hints of vocabulary for constructing a sentence of the picture. LSTM constructs the caption sentence based on the vocabulary hints from the GoogleNet. In this section, we will describe the basic concept of GoogleNet and the use of LSTM model in the paper.

<p align="center">
<img src="/report/nic-model.png" width=600>
</p>

### References
[1] Vinyals, Oriol, et al. "Show and tell: A neural image caption generator." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.  
[2] Szegedy, Christian, et al. "Going deeper with convolutions." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.   
[3] Sundermeyer, Martin, Ralf Schlüter, and Hermann Ney. "LSTM neural networks for language modeling." Thirteenth annual conference of the international speech communication association. 2012.
