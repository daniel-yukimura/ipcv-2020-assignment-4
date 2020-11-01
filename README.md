
## Assignment 4

In this assignment we'll learn about some of the available tools for video processing through Deep Learning.
We'll be using the [**GluonCV**](https://cv.gluon.ai/) library, since it seems easy to use and well documented.
This assignment will be divided into two parts, over two weeks. In the first week you'll be going through some of the necessary
preliminaries for using [MXNet](https://mxnet.apache.org/versions/1.7.0/) and the library itself. In the second week you'll be
experimenting and testing with the GluonCV library with models trained on videos.

### Part 1:

**Instructions:**

Study the following references before the next laboratory meeting, on **Monday, November 02 2020**:

1. Introduction to MXNet: [Intro](https://mxnet.apache.org/versions/1.7.0/api/python/docs/tutorials/getting-started/crash-course/index.html).

2. A Comprehensive Tutorial on Video Modeling (CVPR 2020): [Tutorial](https://bryanyzhu.github.io/videomodeling.github.io/)
  * You should, at least, check the talk **A Chronological Review of Recent SoTA and Beyond**  by Yi Zhu: [slides](https://bryanyzhu.github.io/videomodeling.github.io/slide/talk2_gluoncv_video_slide.pdf) - [talk](https://youtu.be/Vox_ZnabryQ).

3. Action Recognition tutorial using the GluonCV library: [Tutorials](https://cv.gluon.ai/tutorials/index.html#action-recognition)

**Remark:** You'll not be required to deliver anything for this part of the assignment, but is expected that you look into these references
before next lab class, so you can ask any doubts before the remaining assignment is presented.


### Part 2:

In this next part we'll be practicing what we studied in the previous week, we'll be experimenting with a few models from
the GluonCV library. The goals for this assignment can be summarized as

* Learning how to apply and run experiments using the library of models provided by GluonCV.
* Learn how to apply and test Action Recognition models of different types.
* Experiment with depth estimation on videos.

**Instructions:**

0. If you're using Google Colab, you just need to have a google account and an associated Google Drive. In case you're choosing to work locally in your machine you must set Anaconda or a `venv` virtual environment, and install the necessary libraries.

1. Create a folder in your Google Drive or in your machine's workspace. Copy to your drive folder or download the following notebook:

 [**Assignment 4 - notebook**](https://colab.research.google.com/drive/1ppJ2oV6OYWYzkTvgHa9Vn-60_LEAdM5W?usp=sharing)

2. Follow the instructions in the notebook for completing the assignment.

3. You can build auxiliary `.py` scripts and call them from your notebook, for organizational purposes.

### Submission for IMPA students

The assignment is due on **Friday, November 13 2020** at 11:59pm (GMT-3).

IMPA students that are regularly enrolled in the program should send their assignments before the due date to <yukimura@impa.br> with a copy to <lvelho@impa.br>. Late delivers will be consider subject to a lower score.

The submission email should be sent with the subject **"Assignment 4 - [first-name] - [last-name]"**. The assignment can be structured and sent in two ways:
* If your whole solution is implemented in the same notebook as the one provided for the assignment, then you can send just the `.ipynb` file as the solution.
* If parts of your implementation were done in auxiliary `.py` scripts, then you must send both the final notebook and the scripts inside a `.zip` file.

The organization of the code will also be considered in the evaluation.

#### For remaining students:

For students that are enrolled as "Aluno de Curso Livre" you must not send your assignment to us, since we'll not be able to evaluate them due to the large number of students and lack of resources from our side.

For students following the course on this modality, we recall that all assignments will be corrected/solved during the Lab classes. Therefore, students must evaluate themselves by comparing our corrections with their solutions. Students taking the writing exam at the end of the semester will be expected to have solved all the assignments.
