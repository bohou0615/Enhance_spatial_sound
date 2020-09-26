# Enhance spatial sound of stereo audio by upmixing

# Abstract
This project aims to enhance the spatial feeling of stereo sound by upmixing the audio to 5.1 surround sound and then synthesize back to stereo. \
Here, we try to achieve a real-time system. We focus on using filters, delayed signal ,and phase transform to upmix the stereo. \
In the process, we first try using PAE(primary-ambient extraction) to upmix the stereo. This method is based on linear estimation, which includes PCA(principle component analysis), LS(least squares). Therefore, this attempt is modified in PAE.mlx. \
However, due to the complexity of the previous method, we decide to simplify it. Thus, we try to use an easier way to upmix the stereo. We first indentify what functions of channels are, such as the center one is for human voice. Then, we select the range of the frequency of human voice. Other information will be shown in the report file. This is edited in Main.mlx

# Author
Po-Hao Wu

# Reference
1. Bai, Mingsian & Shih, Geng-Yu. (2007). Upmixing and Downmixing Two-channel Stereo Audio for Consumer Electronics. Consumer Electronics, IEEE Transactions on. 53. 1011 - 1019. 10.1109/TCE.2007.4341580.
2. He, Jianjun & Tan, Ee-Leng & Gan, Woon-Seng. (2014). Linear Estimation Based Primary-Ambient Extraction for Stereo Audio Signals. IEEE Transactions on Audio Speech and Language Processing. 22. 505-517. 10.1109/TASLP.2013.2297015.
