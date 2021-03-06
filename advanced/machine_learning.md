# Machine Learning

## Google Cloud APIs <a id="google-cloud-apis"></a>

If you want a taste of what Machine Learning does before diving right into it, the Google Cloud Platform is a good place to start. The Cloud platform is a web Application Program Interface \( web API\), which you can think of as a service that let you “ask” something to the Google servers, and they “reply” to you in a certain way. In our case, the action of asking is called a get request, and their reply will be given as a .json file \(which resembles a JavaScript object, or Python Dictionary\). To read more about web requests, read it [here](https://www.tutorialspoint.com/http/http_requests.htm).

To get started with Google Cloud Platform, you have to first create an account. You will get $300 in credits when you start if you enter your billing information. However, you will still have access to some of the features without it. The [how-to](https://cloud.google.com/billing/docs/how-to/manage-billing-account) explain the process well.

Once you have setup your account, you can start playing with the APIs! Here are the four Machine Learning APIs Google is currently offering:

* [Vision API](https://cloud.google.com/vision/docs/quickstart)
* [Speech API](https://cloud.google.com/speech/docs/apis)
* [Natural Language API](https://cloud.google.com/natural-language/docs/reference/rest/)
* [Translation API](https://cloud.google.com/translate/docs/apis)

Once you have setup everything, you can do some pretty cool projects right away! Either a mood detector, or a text summarizer, or a voice assistant, it is up to you to decide.

## Installing Machine Learning Packages <a id="installing-machine-learning-packages"></a>

Installing a Machine Learning Package can be really easy, or really hard, depending on what you are using. Some of the more general package, such as Numpy and Sci-kit Learn, will only take a few minutes to install once you downloaded the packages. Other packages, such as Tensorflow or Torch, might take a while, since you might have to install other packages on which they depend on, and fix sometimes obscure bug related to your own computer. It is therefore advised that, if you plan on working on a Machine Learning project, to install what you plan to use before starting, so you wouldn’t spend hours and hours trying to get started. As for Keras, since it is built on top of Tensorflow \(in other words, Keras makes it easier to use\), you obviously need to install Tensorflow and all the dependent packages before getting started with Keras.

## Installing Anaconda and Jupyter <a id="installing-anaconda-and-jupyter"></a>

Anaconda is a Python scientific package manager, which means that it comes with many packages and libraries useful for Statistical analysis, Data Science, and as you would’ve guessed, Machine Learning. In addition, it also includes a “notebook” called Jupyter, which lets you fragments of Python code instead of having to run the whole file, which is what a normal text editor do.

To download Anaconda, you can go [here](https://www.anaconda.com/download/)

To learn more about J[Jupyter](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)

## Getting Started with Numpy and Scikit-Learn <a id="getting-started-with-numpy-and-scikit-learn"></a>

If you have installed Anaconda, you can find Numpy and Scikit-Learn already installed. Otherwise, you can find the installation link on their respective website.

Numpy is a mathematical package that focus on computing multi-dimensional arrays, which are efficient versions of Python lists. If you have taken Linear Algebra, you can perform a lot of lightning-fast matrix computations using this library.

Scikit Learn is a machine learning library that include most of the popular models and algorithms, and can compute them very efficiently. It is significantly easier to use than Tensorflow or Torch, and includes a lot of algorithms that are not in those two libraries. In fact, it is beginner-friendly enough that you can dive directly in the website, and follow tutorial here and there to create your first Machine Learning model, even if you don’t have prior knowledge.

Official [Numpy](http://www.numpy.org/) Website.

Official [Scikit](http://scikit-learn.org) Learn Website.

## Beginner Implementations: Keras <a id="beginner-implementations-keras"></a>

If you want to implement Neural Networks right away, Keras is exactly what you need. It wraps another API \(e.g. Tensorflow, Torch\), and makes creating neural networks much quicker and simpler. However, if you want to use Keras and Tensorflow more seriously, you will need to learn about neural networks and deep learning. [Here](https://github.com/fchollet/keras-resources) is a compilation of all the tutorials available to get started. Many of them are outdated, so it is normal if you get errors while running the code. The only way to solve this would be to modify the code so that it would work with the new version \(which requires a lot of Googling and Stack Overflow\).

## TensorFlow <a id="tensorflow"></a>

TensorFlow is probably the most useful library if you want to create advanced projects with deep learning and neural networks. However, getting started with TensorFlow is definitely not easy, and requires you to have a strong background in programming and machine learning. However, for the purpose of the hack, it is definitely possible to find great open-sourced programs posted on GitHub \(Google is your best friend here\), and implement those pre-trained models.

You can download [TensorFlow](https://www.tensorflow.org/install/) on the official website.

If you want to learn more about how to use TensorFlow, you can take the Udacity course created by the Google developers [here](https://www.udacity.com/course/deep-learning--ud730).

## Kaggle <a id="kaggle"></a>

Kaggle is an important Data Science platform that provide tutorials, data sets and competitions using Machine Learning. You could use it to find the data sets you want to use for your hack, or inspire your project from one of the projects available.

You can get started with their Titanic competition, which is the most beginner-friendly [here](https://www.kaggle.com/c/titanic)

Kaggle’s founder explains very well the best way to get started with the platform [here](https://www.quora.com/How-should-a-beginner-get-started-on-Kaggle/answer/Anthony-Goldbloom?srid=UWVn).

