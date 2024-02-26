# D360 - Background Removal from Diamond images for MIned Hackathon

**U2NET_Train.ipynb** is training our U2NET architecture using our training images.

**data_loader.py** is used for image processing and loading the data.

**U2net_test.py** is the file which gives the predictions of the input data. Main work is done in this code.

**U2NET_Inference.ipynb** is the testing file.

**U2NET.py** is the architecture of U2NET.


Our U2 -Net is designed as a two-level nested U-structure. The following are some of the benefits of the design: 
<br/>(1)Because of the mixing of receptive fields of various sizes in our proposed ReSidual U-blocks, it is able to gather more contextual information from various scales (RSU).
<br/>(2)Because of the depth, it boosts the overall architecture's depth without considerably raising the computing cost.
<br/>These RSU blocks make use of pooling techniques. We can train a deep neural network using this design.

The trained model is saved at https://drive.google.com/file/d/1tWfz5mSNTx3tgtDDk4n0ZaPu-VD760H-/view?usp=sharing.

**requirements.txt** contains the required libraries to be installed and imported in your system.

The output images of the testing dataset given is saved at https://drive.google.com/drive/folders/1TXwJDu24F61-N7bOy7LbY8M86C-sWtL-?usp=sharing

References: 

https://www.remove.bg/ - Used for getting masks while training 
https://github.com/xuebinqin/U-2-Net/blob/master/README.md - U Square Net
