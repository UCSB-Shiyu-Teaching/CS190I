# CS190I: Introduction to Deep Learning

This course offers students an introduction to some of the latest state-of-the-art techniques in the field of deep learning. Throughout the course, students will delve into a wide range of advanced topics and methodologies, including convolutional neural networks (CNNs), recurrent neural networks (RNNs), generative models such as large language models, and transformers, among others. The primary focus will be on comprehending the underlying principles and mathematical foundations of these techniques, as well as their practical applications in domains such as computer vision and natural language processing. The course places a strong emphasis on practical implementations, allowing students to gain hands-on experience by implementing these techniques themselves. By the end of the course, students will have a basic understanding of deep learning, equipping them with the confidence to apply cutting-edge techniques to real-world problems.

## Course Prerequisites

CS 165B, the Introduction to Machine Learning course, is a prerequisite for this class. We expect students to be familiar with key concepts such as vector calculus, gradient descent, supervised vs. unsupervised learning, regression, classification, training/validation/testing, hyperparameter tuning, and dimensionality reduction.  Additionally, students should have experience in deriving and implementing basic machine learning algorithms using Python.

## Team Hours
- **Instructor**: 
	- [Prof. Shiyu Chang](https://code-terminator.github.io/), Tuesday after the lecture
- **TAs**:
	- [Bairu Hou](https://hbr690188270.github.io/) (Head TA): Wednesday 5 - 6 pm, HH 2118
	- [Yujian Liu](https://yujianll.github.io/): Friday 5 - 6 pm, HH 2118
	- [Jiabao Ji](https://question406.github.io/): Thursday 5 - 6 pm, HH 2118
 - **Grader**:
	- [Guanyu Yao](https://yaoguany.github.io/): Re-grading by appointment only

For any questions regarding course policies, homework assignments, late submissions, or regrading, please contact the head TAs first and include all other TAs in your email.

## Course Discussions

The course piazza can be accessed [here](https://piazza.com/ucsb/fall2024/cmpsc190i).  Please note that the primary purpose of this forum is for students to exchange ideas and clarify any concepts. 
**TAs are not expected to respond to questions around the clock.** 
Additionally, sharing homework solutions directly in the discussion violates the student honor code.

## Schedule
- **Lectures** will occur Tuesday/Thursday from 11:00-12:15 pm Pacific Time at [ILP 2211](https://classrooms.ucsb.edu/classroom-inventory/ilp-2211).
- **Discussion** sections will occur on Friday.  There are three sections, 11-12pm, 12-1pm, and 1-2pm. 

Updated lecture slides will be posted here shortly before each lecture. 

| Date        | Description                   | Course Materials | Important Events                                       |
|-------------|-------------------------------|------------------|--------------------------------------------------------|
| Thu, 09/26 | Introduction to deep learning | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3461027)]   | |
| Tue, 10/01 | CS165B Review  | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3471469)]  [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3522753)]  | [[HW 1 self-assessment](https://colab.research.google.com/drive/11e8EFIg8yfdhCh68OOCMKoe8mC5DB2pa?usp=sharing)] is out, due on Sunday, Oct 13, 11:59 pm PST |
| Thu, 10/03 | CS165B Review Con't | | |
| Fri, 10/04 | Discussion Section: Python Review| [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3489993)]   | |
| Tue, 10/08 | Multi-class Classification | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3495692)]  [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3561005)]  | |
| Thu, 10/10 | Multi-class Classification Con't|  | |
| Fri, 10/11 | Discussion Section: Logistic Regression on Imbalanced Data| [[Slides](https://ucsb.instructure.com/courses/22770/files/folder/SectionSlide?preview=3536300)]   | |
| Tue, 10/15 | Multi-class Classification Con't	| [[Detailed notes](https://ucsb.instructure.com/courses/22770/files?preview=3561018)]  |  [[HW2](https://drive.google.com/file/d/15TihU_iZDMGCDkkbAhrSSXaYJeucXFfo/view?usp=sharing)] is out, due on Sunday, Oct 27, 11:59 pm PST |
| Thu, 10/17 | Fully-connected Neural Networks	| [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3561033)]  [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3605134)]   |  |
| Fri, 10/18 | Discussion Section: A Visual Proof for Universal Approximation Theorem	| [[Slides](https://ucsb.instructure.com/courses/22770/files/folder/SectionSlide?preview=3575387)]   |  |
| Tue, 10/22 | Fully-connected Neural Networks Con't & Back Propagation	| |  |
| Thu, 10/24 | Back Propagation	| [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3598259)]  [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3654120)]  |  |
| Fri, 10/25 | Discussion Section: PyTorch Introduction| [[Slides](https://ucsb.instructure.com/courses/22770/files/folder/SectionSlide?preview=3646982)]   | |
| Tue, 10/29 | Back Propagation Con't & Text Classification | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3646978)]    | [[HW3](https://colab.research.google.com/drive/1kGVg91TqGV3H8jrsrawdVDkCyU115EZA?usp=sharing)] is out, due on Sunday, Nov 10, 11:59 pm PST |
| Thu, 10/31 | Text Classification and Midterm 1 Review	| [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3669938)]  [[Review](https://ucsb.instructure.com/courses/22770/files?preview=3669930)]    |  |
| Fri, 11/01 | Discussion Section: Word Representation| [[Slides](https://ucsb.instructure.com/courses/22770/files/folder/SectionSlide?preview=3676135)]   | |
| Tue, 11/05 | In-Class Midterm Exam | | |
| Thu, 11/07 | Convolutional Neural Networks | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3696375)] | |
| Fri, 11/08 | Midterm 1 Common Mistakes Revisit | [[Reference reading](https://web.eecs.umich.edu/~justincj/slides/eecs498/WI2022/598_WI2022_lecture06.pdf)] | |
| Tue, 11/12 | Convolutional Neural Networks Con't | [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3716194)] [[Video](https://ucsb.instructure.com/courses/22770/files?preview=3716201)]  | [[HW4](https://colab.research.google.com/drive/1zdu4mF_RbxoSvU5sS616ImwTWdDX3l7r?usp=sharing)] is out, due on Sunday, Nov 24, 11:59 pm PST |
| Thu, 11/14 | Residual Networks |  [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3716202)]  [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3716203)] [[Video](https://www.dropbox.com/scl/fi/s81xtkbh1jj14ivfd9t5e/ResNet-Video.mp4?rlkey=sv4sr06yujg76c7auzb3m8xtl&dl=0)] | Reference reading: [[ResNet](https://arxiv.org/abs/1512.03385)], [[Batch Normalization](https://arxiv.org/abs/1502.03167)], [[Layer Normalization](https://arxiv.org/abs/1607.06450)] |
| Tue, 11/19 | Strategies to Mitigate Overfitting | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3772252)] [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3906374)] | Reference reading: [[Dropout](https://www.jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf)] |
| Thu, 11/21 | Recurrent Neural Network | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3866453)]  [[Annotated](https://ucsb.instructure.com/courses/22770/files?preview=3927702)]  | Reference reading: [[LSTM](https://sophieeunajang.wordpress.com/wp-content/uploads/2020/10/lstm.pdf)], [[GRU](https://arxiv.org/pdf/1406.1078)]|
| Tue, 11/26 | Attention Mechanism | [[Slides](https://ucsb.instructure.com/courses/22770/files?preview=3906362)] | [[HW5](https://colab.research.google.com/drive/1FRmNNvfdyEn4CBqb98qtzElVcQa2BCsn?usp=sharing)] is out, due on Sunday, Dec 8, 11:59 pm PST & Reference reading: [[Seq2Seq](https://proceedings.neurips.cc/paper_files/paper/2014/file/a14ac55a4f27472c5d894ec1c3c743d2-Paper.pdf)], [[PyTorch tutorial](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)] |

