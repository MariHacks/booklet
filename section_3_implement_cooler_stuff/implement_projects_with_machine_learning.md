## Implement Projects with Machine Learning {#implement-projects-with-machine-learning}

Have you guys ever seen a male to male usb type A cable? A simple cable that allows you to plug one computer into another. Little did you know, but that&#039;s how computers teach each other!! (In reality plugging one computers USB into another will only generate a whole plethora of problems and can even fry the motherboard if not properly protected).

In reality, machine learning is the idea that a machine/algorithm can get better every time it is run by learning something either from the user or just a data set.

### Google Cloud APIs {#google-cloud-apis}

If you want a taste of what Machine Learning does before diving right into it, the Google Cloud Platform is a good place to start. The Cloud platform is a web Application Program Interface ( web API), which you can think of as a service that let you “ask” something to the Google servers, and they “reply” to you in a certain way. In our case, the action of asking is called a get request, and their reply will be given as a .json file (which resembles a JavaScript object, or Python Dictionary). To read more about web requests, read it here: [https://www.tutorialspoint.com/http/http_requests.htm](https://www.tutorialspoint.com/http/http_requests.htm)

To get started with Google Cloud Platform, you have to first create an account. You will get $300 in credits when you start if you enter your billing information. However, you will still have access to some of the features without it. The how-to explain the process well: [https://cloud.google.com/billing/docs/how-to/manage-billing-account](https://cloud.google.com/billing/docs/how-to/manage-billing-account)

Once you have setup your account, you can start playing with the APIs! Here are the four Machine Learning APIs Google is currently offering:

*   Vision API: [https://cloud.google.com/vision/docs/quickstart](https://cloud.google.com/vision/docs/quickstart)
*   Speech API: [https://cloud.google.com/speech/docs/apis](https://cloud.google.com/speech/docs/apis)
*   Natural Language API: [https://cloud.google.com/natural-language/docs/reference/rest/](https://cloud.google.com/natural-language/docs/reference/rest/)
*   Translation API: [https://cloud.google.com/translate/docs/apis](https://cloud.google.com/translate/docs/apis)

Once you have setup everything, you can do some pretty cool projects right away! Either a mood detector, or a text summarizer, or a voice assistant, it is up to you to decide.

### Installing Machine Learning Packages {#installing-machine-learning-packages}

Installing a Machine Learning Package can be really easy, or really hard, depending on what you are using. Some of the more general package, such as Numpy and Sci-kit Learn, will only take a few minutes to install once you downloaded the packages. Other packages, such as Tensorflow or Torch, might take a while, since you might have to install other packages on which they depend on, and fix sometimes obscure bug related to your own computer. It is therefore advised that, if you plan on working on a Machine Learning project, to install what you plan to use before starting, so you wouldn’t spend hours and hours trying to get started. As for Keras, since it is built on top of Tensorflow (in other words, Keras makes it easier to use), you obviously need to install Tensorflow and all the dependent packages before getting started with Keras.

### Installing Anaconda and Jupyter {#installing-anaconda-and-jupyter}

Anaconda is a Python scientific package manager, which means that it comes with many packages and libraries useful for Statistical analysis, Data Science, and as you would’ve guessed, Machine Learning. In addition, it also includes a “notebook” called Jupyter, which lets you fragments of Python code instead of having to run the whole file, which is what a normal text editor do.

To download Anaconda, you can go on: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)

To learn more about Jupyter: [https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)

### Getting Started with Numpy and Scikit-Learn {#getting-started-with-numpy-and-scikit-learn}

If you have installed Anaconda, you can find Numpy and Scikit-Learn already installed. Otherwise, you can find the installation link on their respective website.

Numpy is a mathematical package that focus on computing multi-dimensional arrays, which are efficient versions of Python lists. If you have taken Linear Algebra, you can perform a lot of lightning-fast matrix computations using this library.

Scikit Learn is a machine learning library that include most of the popular models and algorithms, and can compute them very efficiently. It is significantly easier to use than Tensorflow or Torch, and includes a lot of algorithms that are not in those two libraries. In fact, it is beginner-friendly enough that you can dive directly in the website, and follow tutorial here and there to create your first Machine Learning model, even if you don’t have prior knowledge.

Official Numpy Website: [http://www.numpy.org/](http://www.numpy.org/)

Official Scikit Learn Website: [http://scikit-learn.org](http://scikit-learn.org)

### Beginner Implementations: Keras {#beginner-implementations-keras}

If you want to implement Neural Networks right away, Keras is exactly what you need. It wraps another API (e.g. Tensorflow, Torch), and makes creating neural networks much quicker and simpler. However, if you want to use Keras and Tensorflow more seriously, you will need to learn about neural networks and deep learning. Here is a compilation of all the tutorials available to get started: [https://github.com/fchollet/keras-resources](https://github.com/fchollet/keras-resources). Many of them are outdated, so it is normal if you get errors while running the code. The only way to solve this would be to modify the code so that it would work with the new version (which requires a lot of Googling and Stack Overflow).

### Tensorflow {#tensorflow}

Tensorflow is probably the most useful library if you want to create advanced projects with deep learning and neural networks. However, getting started with Tensorflow is definitely not easy, and requires you to have a strong background in programming and machine learning. However, for the purpose of the hack, it is definitely possible to find great open-sourced programs posted on GitHub (Google is your best friend here), and implement those pre-trained models.

You can download Tensorflow on the official website: [https://www.tensorflow.org/install/](https://www.tensorflow.org/install/)

If you want to learn more about how to use Tensorflow, you can take the Udacity course created by the Google developers: [https://www.udacity.com/course/deep-learning--ud730](https://www.udacity.com/course/deep-learning--ud730)

### Kaggle {#kaggle}

Kaggle is an important Data Science platform that provide tutorials, data sets and competitions using Machine Learning. You could use it to find the data sets you want to use for your hack, or inspire your project from one of the projects available.

You can get started with their Titanic competition, which is the most beginner-friendly: [https://www.kaggle.com/c/titanic](https://www.kaggle.com/c/titanic)

Kaggle’s founder explains very well the best way to get started with the platform:

[https://www.quora.com/How-should-a-beginner-get-started-on-Kaggle/answer/Anthony-Goldbloom?srid=UWVn](https://www.quora.com/How-should-a-beginner-get-started-on-Kaggle/answer/Anthony-Goldbloom?srid=UWVn)