# Final Project in Recognition Class - Spring 2021
## Voice Biometrics and State of the Art Deep Learning in Speaker Recognition

### Abstract

In recent years, Machine Learning has achieved many outstanding achievements, promoting the rapid development of Technology Revolution 4.0. One of the most powerful factors coming from Deep Learning, learning models based on these methods have been very successful, achieving a promising performance, for many various tasks in Computer Vision, Natural Language Processing, Pattern Recognition, Biometrics Recognition, ...

In recognition task, especially Voice/ Speech Recognition is almost a difficult problem for many years, it takes very complicated methods to solve. Due to Deep Learning, the solution must be feasible, especially with Convolutional Neural Networks (CNNs) that bring promising results when only direct input is the raw voice sample. Instead of using standard manual features, CNNs later learned to represent low-level voices from waveforms, potentially allowing the network to better capture critical narrow-band speaker characteristics such as pitch and formants.

For the purpose of researching scientific articles, as well as finding out machine learning models and methods that have emerged recently in important tasks, namely identification. Our group decided to research this field by reading the chapter 8 - Voice Biometrics of the Handbook of Biometrics and use Latex Presenation to talk about the State of the Art of Deep Learning in Speech Recognition

### Acknowledgments

Our work would not be complete without the enthusiastic help from our teachers, our friends, our team. Thank you for our family always support us during the time. Last but not least, we must thank to the authors of the Handbook of Biometrics, who wrote a usefull science book for newbie in Machine Learning like us, the authors of papers that we reference for this project, the authors of SincNet - a great architecture.

### Introduction

As we know about voice is the most accessible biometric trait as no extra acquisition device or transmission system is needed because more and more people all over the world use mobile phone to talk together, the number of telephone landlines in operation increase everyday and the development of social network. However, the voice trait is not only related with personal characteristics, but also with many environmental and sociolinguistic variables. Fortunately, state-of-the-art technologies and applications are presently able to compensate for all those sources of variability allowing for efficient and reliable value-added applications that enable remote authentication or voice detection based just in telephone-transmitted voice signals. Moset of these state of the art methods based on the i-vectors representation of speech segments, significantly improved over the Gaussian Mixture Model-Universal Background Models and development of the Deep Neural Network contributed to the resolution of perception. voice form. However, there are still many problems to be solved with this problem such as the input data problem, optimizing the error, increasing the convergence performance and especially how to design a compact, fine-tunable model. are to match our applications.

### About our work

Our work separated into three parts: In the first and the second part, we will show basic knowledge (theory), and the last one, we will demo a small task in Speaker Recognition

Part 1: present insights about Voice Biometrics Topic, as know as traditional approach that we learned from Handbook of Biometric 

Its content outline following the list below:
- Introduction about Voice/Speech, which is one of the most accessible biometric trait
- Identification information in Voice/Speech signal
- Extracting features and word tokenization
    - Short-term analysis
    - Parameterization
    - Phonetic and word tokenization
    - Prosodic Tokenization
- Two big technologies in Voice/Speech Recognition
    - Text-dependent speaker recognition
    - Text-indenpent speaker recognition
- Applications and some awesome case study

Part 2: In this section, we will talking about the state of the art of Voice Biometrics in over the last few years, about from 2014, when Deep Learning became more popular in researchers

Its content outline following the list below:
- Introduction about SOTA Voice Biometrics
- The motivation
- Problem statement of Speaker Recognition (Input/ Output)
- Corpus/ Dataset used for Speaker Recognition
- Testing model in Speaker Recognition
- Meansures in Speaker Recognition
- Related work
    - Deep Learning in extracting features
        - d-vectors
        - j-vectors
        - x-vectors
    - Deep Learning in speaker classification
        - Multi-domain features
        - SincNet

Part 3: Demo section, in this section, we use SincNet to train a model use in speaker verification task and speaker identification task, we use three dataset: TIMIT dataset, Librispeech Dataset (for English) and Son el Dataset for Vietnamese

To present a Speaker Recognition pipeline:
- Data prepration
- Development: Training model
- Enrollment: Enroll for new people
- Evaluate: Testing model, compute d-vector and use cosine meansure to identify or verify speaker

### Final comment

### About Contributing

- Issue Tracker: github.com/nhutnamhcmus/introduction-to-machine-learning-hcmus-presentation/issues
- Source Code: github.com/github.com/nhutnamhcmus/introduction-to-machine-learning-hcmus-presentation

### About community support

If you are having issues, please let us know. We have a mailing list located at: lenam.fithcmus@gmail.com or namele1232000@gmail.com

### About the License of this repository

The project is licensed under the MIT license.

### References

[1] Github repository: Wavencoder - a python library for encoding raw audio with pytorch backend.

[2] Wav2vec 2.0: Learning the structure of speech from raw audio.

[3] S. Chopra, R. Hadsell, and Y. LeCun. Learning a similarity metric discriminatively, with appli-
cation to face verification. In 2005 IEEE Computer Society Conference on Computer Vision and
Pattern Recognition (CVPR’05), volume 1, pages 539–546 vol. 1, 2005.

[4] Juan M. Coria, Hervé Bredin, Sahar Ghannay, and Sophie Rosset. A comparison of metric learning
loss functions for end-to-end speaker verification, 2020.

[5] Juan M. Coria, Hervé Bredin, Sahar Ghannay, and Sophie Rosset. Github repository: Companion
repository for the paper "a comparison of metric learning loss functions for end-to-end speaker
verification"published at slsp 2020, 2020.

[6] Oscar Forth (1) Finnian Kelly (1), Anil Alexander (1) and David van der Vloed (2). From i-vectors
to x-vectors – a generational change in speaker recognition illustrated on the nfi-frida database.

[7] Evans Kiplagat Francesco Grauso. Github repository: Keras (tensorflow) implementation of sinc-
net (mirco ravanelli, yoshua bengio, 2018.

[8] Omid Ghahabi and Javier Hernando. Deep learning backend for single and multisession i-
vector speaker recognition. IEEE/ACM Transactions on Audio, Speech, and Language Processing,
25(4):807–817, 2017.

[9] Anil K. Jain, Patrick Flynn, and Arun A. Ross. Handbook of Biometrics. Springer Publishing
Company, Incorporated, 1st edition, 2010.

[10] Andy T. Liu, Shu-wen Yang, Po-Han Chi, Po-chun Hsu, and Hung-yi Lee. Mockingjay: Unsuper-
vised speech representation learning with deep bidirectional transformer encoders. ICASSP 2020 -
2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), May
2020.

[11] Kai Yu Nanxin Chen, Yanmin Qian. Multi-task learning for text-dependent speaker verification.
In INTERSPEECH 2015 16th Annual Conference of the International Speech Communication
Association, pages 185–189, 2015.

[12] Son T. Nguyen, Viet D. Lai, Quyen Dam-Ba, Anh Nguyen-Xuan, and Cuong Pham. Vietnamese
speaker authentication using deep models. In Proceedings of the Ninth International Symposium
on Information and Communication Technology, SoICT 2018, page 177–184, New York, NY, USA,
2018. Association for Computing Machinery.

[13] Santiago Pascual, Mirco Ravanelli, Joan Serrà, Antonio Bonafonte, and Yoshua Bengio. Learning
problem-agnostic speech representations from multiple self-supervised tasks, 2019.

[14] Mirco Ravanelli and Yoshua Bengio. Github repository: Sincnet original code written in pytorch
by the autor, 2019.

[15] Mirco Ravanelli and Yoshua Bengio. Speaker recognition from raw waveform with sincnet, 2019.

[16] Steffen Schneider, Alexei Baevski, Ronan Collobert, and Michael Auli. wav2vec: Unsupervised
pre-training for speech recognition, 2019.

[17] David Snyder, Daniel Garcia-Romero, Gregory Sell, Daniel Povey, and Sanjeev Khudanpur. X-
vectors: Robust dnn embeddings for speaker recognition. In 2018 IEEE International Conference
on Acoustics, Speech and Signal Processing (ICASSP), pages 5329–5333, 2018.

[18] Zhiyuan Tang, Lantian Li, and Dong Wang. Multi-task recurrent model for speech and speaker
recognition, 2016.

[19] Ehsan Variani, Xin Lei, Erik McDermott, Ignacio Lopez Moreno, and Javier Gonzalez-Dominguez.
Deep neural networks for small footprint text-dependent speaker verification. In 2014 IEEE
International Conference on Acoustics, Speech and Signal Processing (ICASSP), pages 4052–4056,
2014.

[20] Jee weon Jung, Seung bin Kim, Hye jin Shim, Ju ho Kim, and Ha-Jin Yu. Improved rawnet with
feature map scaling for text-independent speaker verification using raw waveforms, 2020.