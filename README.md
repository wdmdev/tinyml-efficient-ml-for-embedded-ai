# TinyML: Efficient Machine Learning for Embedded AI Systems
(Danish Title) TinyML: Effektiv maskinlæring til indlejrede AI-systemer.

My way of creating an overview of a special course I am taking at [The Technical University of Denmark](https://www.dtu.dk/) as 
part of my MSc in Mathematical Modeling and Computation with a Machine Learning and Signal Processing specialization.  

This page is created as a fork of the following course page [Real-Time Visual and Machine Learning Systems](https://absorensen.github.io/real-time-visual-and-machine-learning-systems/). Thanks to [Anders Bo Sørensen](https://absorensen.github.io/) and his co-workers for making it available! 
<a href="https://www.flaticon.com/free-icons/lightning" title="lightning icons">Lightning icons created by Freepik - Flaticon</a>
.

## Course Description
This course provides an introduction to TinyML, focusing on efficient machine learning for embedded AI systems. Students will learn the fundamental concepts and techniques for developing machine learning models that can run on resource-constrained devices. Topics covered include model optimization, quantization, neural architecture search, knowledge distillation, and domain-specific optimization. The course will also explore efficient training methods, distributed training, on-device training, and transfer learning. Hands-on labs and readings will complement the lectures, allowing students to gain practical experience in implementing TinyML systems. By the end of the course, students will have the knowledge and skills to design and deploy machine learning models on embedded devices.


## Learning Objectives

A student who has met the objectives of the course will be able to:

* Understand the concept of TinyML and its applications in embedded AI systems.
* Learn techniques for optimizing machine learning models for resource-constrained devices.
* Gain knowledge in model quantization, neural architecture search, knowledge distillation, and domain-specific optimization.
* Explore efficient training methods, including distributed training, on-device training, and transfer learning.
* Develop practical skills in implementing TinyML systems through hands-on labs.
* Design and deploy machine learning models on embedded devices.

## Evaluation
* Summary report of the learnings throughout the course

### Course work
The course will consist of:

* Lectures
* Some readings (mainly papers)
* Hands-on labs

For extra resources one may find the following useful:

* [Machine Learning Systems](https://harvard-edge.github.io/cs249r_book/)
* [Paper Overview - CMU On-Device Machine Learning](https://cmu-odml.github.io/papers/)

## Schedule
The course starts on Friday 7 June and runs until Friday 28 June 2024.

Date      | Labs      | Topics    |Lecture
----------|-----------|-----------|-------
|<div style="background-color: #D3D3D3; padding: 5px; color: black; text-align: center; width:325%" colspan="4">Efficient Inference</div>|
6/11/24   |[Lab 1][21]|Pruning and Sparsity                         | [Part 1][0] , [Part 2][1]
6/12/24   |[Lab 2][22]|Quantization                                 | [Part 1][2], [Part 2][3]
6/13/24   |[Lab 3][23]|Neural Architecture Search                   | [Part 1][4], [Part 2][5]
6/14/24   ||Knowledge Distillation                                  | [Link][6] 
6/15/24   ||Frameworks                                              | [MCUNet][7], [TinyEngine][8] 
|<div style="background-color: #D3D3D3; padding: 5px; color: black; text-align: center; width:325%" colspan="4">Domain Specific Optimization</div>|
6/17/24   |[Lab 4][26] and [Lab 5][27]|Transformer and LLM                          | [Part 1][9], [Part 2][10] 
6/18/24   |[Lab 6][28]|Vision Transformer                           | [Link][11] 
6/19/24   ||GAN, Video, and Point Cloud                             | [Link][12] 
6/20/24   ||Diffusion Model                                         | [Link][13] 
6/21/24   ||Recurrent Neural Networks                               | [Paper][14] 
|<div style="background-color: #D3D3D3; padding: 5px; color: black; text-align: center; width:325%" colspan="4">Efficient Training</div>|
6/24/24   ||Distributed Training                                    | [Part 1][15], [Part 2][16] 
6/25/24   ||On-Device Training and Transfer Learning                | [Link][17] 
6/26/24   ||Efficient Fine-tuning and Prompt Engineering            | [Link][18] 
6/27/24   |[Lab 7][29]|Benchmarking TinyML Systems                 | [Paper][19] 
6/28/24   |[Lab 8][30]|Carbon and Energy Tracking                  | [Paper][20] 

<!--Lectures-->
[0]:    https://youtu.be/w5WiUcDJosM
[1]:    https://youtu.be/3t9aGLLaCqs
[2]:    https://youtu.be/TSc_BibWRhM
[3]:    https://youtu.be/g-TzDApaE88
[4]:    https://youtu.be/gFi29IEHRGc
[5]:    https://youtu.be/EFpGQoDQ7JI
[6]:    https://youtu.be/EkjVHToId7U
[7]:    https://youtu.be/l7RdJRYl7ZY
[8]:    https://youtu.be/HGsvWHqU29Y
[9]:    https://www.youtube.com/embed/A12m85vbZro?si=D1-cvRL-RDlqFGfd
[10]:   https://youtu.be/7WeraZ0LLlg 
[11]:   https://youtu.be/QQY24LLww1A
[12]:   https://youtu.be/W3WwxI0M-hI
[13]:   https://youtu.be/nFE1euQ_Wtw
[14]:   https://arxiv.org/abs/2402.12263
[15]:   https://youtu.be/0vdzBAms8mE
[16]:   https://youtu.be/mP4BL6URdxc
[17]:   https://youtu.be/PArGX623PvA
[18]:   https://youtu.be/vOPwwRCZ8q8
[19]:   https://arxiv.org/abs/2003.04821     
[20]:   https://arxiv.org/abs/2007.03051
<!--Labs-->
[21]:   https://drive.google.com/file/d/124toPMHDd3z6LiXOhOgHPy6Wvb0Xzw3E/view?usp=sharing   
[22]:   https://github.com/cmu-odml/cmu-odml.github.io/blob/master/labs/03_quantization.ipynb
[23]:   https://drive.google.com/file/d/1n1_T-icO-LZsZpcti-pRZcX_VvumbDWM/view?usp=sharing
[26]:   https://colab.research.google.com/drive/1zxkqlnaJ7y5P9PAhyr0504je3uJZVIaF?usp=share_link
[27]:   https://github.com/ee292d/labs/blob/main/lab6/README.md
[28]:   https://github.com/ee292d/labs/tree/main/lab2
[29]:   https://github.com/cmu-odml/cmu-odml.github.io/blob/master/labs/01_pytorch_ffnns.md
[30]:   https://github.com/cmu-odml/cmu-odml.github.io/blob/master/labs/05_energy.md