# Learning TinyML
This is the repository for the LinkedIn Learning course Learning TinyML. The full course is available from [LinkedIn Learning][lil-course-url].

![Learning TinyML][lil-thumbnail-url] 

While you may not realize it, TinyML probably affects your life in some way on a daily basis. If you have a smartphone or IoT device that features voice activation, facial recognition, audio detection, or other functions that employ machine learning algorithms, you have TinyML to thank. In this course, instructor Vaidheeswaran Archana
guides you into the world of TinyML and shows you how you can process huge AI models right in the palm of your hand. Vaidheeswaran starts by teaching you how to identify if your ML/AI problem is a TinyML problem, then shows you optimization techniques to fit your deep learning models and illustrates multiple use cases. She explains quantization techniques, how to train a model using Tflite, how to deploy a TinyML model, and covers the entire TinyMLOps lifecycle. Vaidheeswaran finishes the course with a look at what’s in store for the future of TinyML, along with some resources you can use to continue your learning.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"


### Instructor

Vaidheeswaran Archana 
                            


                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/vaidheeswaran-archana).

[lil-course-url]: https://www.linkedin.com/learning/learning-tinyml
[lil-thumbnail-url]: https://cdn.lynda.com/course/2447146/2447146-1658257176610-16x9.jpg
