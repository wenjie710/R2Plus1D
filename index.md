## A Closer Look at Spatiotemporal Convolutions for Action Recognition
by [Du Tran](http://www.cs.dartmouth.edu/~dutran), [Heng Wang](http://lear.inrialpes.fr/people/wang/), [Lorenzo Torresani](http://www.cs.dartmouth.edu/~lorenzo), [Jamie Ray](https://research.fb.com/people/ray-jamie), [Yann LeCun](http://yann.lecun.com/), and [Manohar Paluri](https://research.fb.com/people/paluri-manohar), CVPR 2018.

### Abstract
In this paper we discuss several forms of spatiotemporal convolutions for  video analysis and  study their effects  on
action recognition. Our motivation stems from the observation that 2D CNNs applied to individual frames of the video
have remained solid performers in action recognition. In this work we empirically demonstrate the accuracy advantages of 3D CNNs over 2D CNNs within the framework of residual learning.  Furthermore,  we show that factorizing the 3D convolutional filters into separate spatial and temporal components yields significantly gains in accuracy.  Our empirical study leads to the design of a new spatiotemporal convolutional block “R(2+1)D” which produces CNNs that
achieve results comparable or superior to the state-of-the-art on Sports-1M, Kinetics, UCF101, and HMDB51.

Link to: [paper](https://128.84.21.199/pdf/1711.11248.pdf) and [code](https://github.com/facebookresearch/R2Plus1D).

### Acknowledgements
The authors would like to thank Ahmed Taei, Aarti Basant, Aapo Kyrola, and the Facebook Caffe2 team for their help in implementing ND-convolution, in optimizing video I/O, and in providing support for distributed training. We are grateful to Joao Carreira for sharing I3D results on the Kinetics validation set.
