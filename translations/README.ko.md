[![GitHub license](https://img.shields.io/github/license/microsoft/AI-For-Beginners.svg)](https://github.com/microsoft/AI-For-Beginners/blob/main/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/AI-For-Beginners.svg)](https://GitHub.com/microsoft/AI-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/AI-For-Beginners.svg)](https://GitHub.com/microsoft/AI-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/AI-For-Beginners.svg)](https://GitHub.com/microsoft/AI-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/AI-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/AI-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/AI-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/AI-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/AI-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/AI-For-Beginners/stargazers/)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/microsoft/ai-for-beginners/HEAD)
[![Gitter](https://badges.gitter.im/Microsoft/ai-for-beginners.svg)](https://gitter.im/Microsoft/ai-for-beginners?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# 초보자를 위한 인공지능 - 교육 과정

|![ Sketchnote by [(@girlie_mac)](https://twitter.com/girlie_mac) ](./lessons/sketchnotes/ai-overview.png)|
|:---:|
| 초보자를 위한 인공지능 - _[@girlie_mac](https://twitter.com/girlie_mac)가 그린 스케치 노트_ |

마이크로소프트의 Azure Cloud Advocates는 **인공지능**에 대한 모든 내용을 12주 24개 강의 교육과정으로 제공하게 된 것을 기쁘게 생각합니다.

이 교육 과정에서 여러분은 아래 내용을 배웁니다:

* **지식 표현 (Knowledge Representation)** 과 추론(reasoning) ([GOFAI](https://en.wikipedia.org/wiki/Symbolic_artificial_intelligence))을 활용한 "좋은 옛날 방식의" 기호 접근법을 포함한 다양한 방법으로 인공지능을 설명합니다.
* **신경망(Neural Networks)** 과 **딥러닝(Deep Learning)**은 최근 인공지능의 핵심입니다. 최근에 가장 인기있는 2개 프레임워크인 [TensorFlow](http://Tensorflow.org) 과 [PyTorch](http://pytorch.org)로 중요한 인공 지능의 주제들을 소스코드로 구현하면서 그 주제들의 개념을 보여줍니다.
* 이미지와 텍스트를 다루는 **신경망 구조(Neural Architectures)**. 최근 모델들을 다루기는 하지만, 아주 최신 (state-of-the-art)의 모델에 대해서는 다소 아쉬울 수 있습니다.
* **유전 알고리즘(Genetic Algorithms)** 과 **멀티 에이전트 시스템(Multi-Agent Systems)**과 같은 덜 알려진 인기있는 인공지능 방법.

이 교육 과정에서 다루지 않는 것:

* **비즈니스에서의 인공지능** 활용 사례. 마이크로소프트 Learn의 과정 중의 하나인 [Introduction to AI for business users](https://docs.microsoft.com/learn/paths/introduction-ai-for-business-users/?WT.mc_id=academic-57639-dmitryso) 나 [INSEAD](https://www.insead.edu/)와 함께 협력해서 만든 과정인 [AI Business School](https://www.microsoft.com/ai/ai-business-school/?WT.mc_id=academic-57639-dmitryso)를 참고하세요.
* **전통적인 머신 러닝**은 [Machine Learning for Beginners Curriculum](http://github.com/Microsoft/ML-for-Beginners)에 잘 설명되어 있습니다.
* **[Cognitive Services](https://azure.microsoft.com/services/cognitive-services/?WT.mc_id=academic-57639-dmitryso)**를 사용해서 만든 실제 인공 지능 애플리케이션. 이런 애플리케이션을 만들려면, 마이크로소프트 Learn의 [vision](https://docs.microsoft.com/learn/paths/create-computer-vision-solutions-azure-cognitive-services/?WT.mc_id=academic-57639-dmitryso), [natural language processing](https://docs.microsoft.com/learn/paths/explore-natural-language-processing/?WT.mc_id=academic-57639-dmitryso) 와 같은 모듈을 참고하면서 시작하는 것을 추천합니다.
* [Azure Machine Learning](https://azure.microsoft.com/services/machine-learning/?WT.mc_id=academic-57639-dmitryso) 나 [Azure Databricks](https://docs.microsoft.com/learn/paths/data-engineer-azure-databricks?WT.mc_id=academic-57639-dmitryso)와 같은 특정 머신 러닝 **클라우드 프레임워크**. 해당 클라우드 프레임워크는 마이크로소프트 Learning 과정인 [Build and operate machine learning solutions with Azure Machine Learning](https://docs.microsoft.com/learn/paths/build-ai-solutions-with-azure-ml-service/?WT.mc_id=academic-57639-dmitryso) 과 [Build and Operate Machine Learning Solutions with Azure Databricks](https://docs.microsoft.com/learn/paths/build-operate-machine-learning-solutions-azure-databricks/?WT.mc_id=academic-57639-dmitryso) 를 참고하세요.
* **Conversational AI** 과 **Chat Bots**. 마이크로소프트 Learning에서 [Create conversational AI solutions](https://docs.microsoft.com/learn/paths/create-conversational-ai-solutions/?WT.mc_id=academic-57639-dmitryso)라는 과정으로 제공합니다. 또한 더 자세한 내용은 다음 블로그를 참고할 수 있습니다 [this blog post](https://soshnikov.com/azure/hello-bot-conversational-ai-on-microsoft-platform/).
* 딥러닝을 위한 **수학**. Ian Goodfellow, Yoshua Bengio and Aaron Courville가 강의한 [Deep Learning](https://www.amazon.com/Deep-Learning-Adaptive-Computation-Machine/dp/0262035618)를 추천합니다.  [https://www.deeplearningbook.org/](https://www.deeplearningbook.org/)에서 온라인으로 수강할 수 있습니다.

*클라우드에서의 인공지능*이라는 주제에 대해서는 [Get started with artificial intelligence on Azure](https://docs.microsoft.com/learn/paths/get-started-with-artificial-intelligence-on-azure/?WT.mc_id=academic-57639-dmitryso) Learning 과정을 참고하세요.



---
# 교육 내용

<table>
<tr><th>No</th><th>강의</th><th>소개</th><th>PyTorch</th><th>Keras/TensorFlow</th><th>실습</th></tr>

<tr><td>I</td><td colspan="4"><b>인공지능 소개</b></td><td></td></tr>
<tr><td>1</td><td>Introduction and History of AI</td><td><a href="lessons/1-Intro/README.md">Text</a></td><td></td><td></td><td></td></tr>

<tr><td>II</td><td colspan="4"><b>심볼릭(Symbolic) 인공지능</b></td><td></td></tr>
<tr><td>2 </td><td>Knowledge Representation and Expert Systems</td><td><a href="lessons/2-Symbolic/README.md">Text</a></td><td colspan="2"><a href="lessons/2-Symbolic/Animals.ipynb">Expert System</a>, <a href="lessons/2-Symbolic/FamilyOntology.ipynb">Ontology</a>, <a href="lessons/2-Symbolic/MSConceptGraph.ipynb">Concept Graph</a></td><td></td></tr>
<tr><td>III</td><td colspan="4"><b><a href="lessons/3-NeuralNetworks/README.md">Introduction to Neural Networks</a></b></td><td></td></tr>
<tr><td>3</td><td>Perceptron</td>
   <td><a href="lessons/3-NeuralNetworks/03-Perceptron/README.md">Text</a>
   <td colspan="2"><a href="lessons/3-NeuralNetworks/03-Perceptron/Perceptron.ipynb">Notebook</a></td><td><a href="lessons/3-NeuralNetworks/03-Perceptron/lab/README.md">Lab</a></td></tr>
<tr><td>4 </td><td>Multi-Layered Perceptron and Creating our own Framework</td><td><a href="lessons/3-NeuralNetworks/04-OwnFramework/README.md">Text</a></td><td colspan="2"><a href="lessons/3-NeuralNetworks/04-OwnFramework/OwnFramework.ipynb">Notebook</a><td><a href="lessons/3-NeuralNetworks/04-OwnFramework/lab/README.md">Lab</a></td></tr> 
<tr><td>5</td>
   <td>Intro to Frameworks (PyTorch/TensorFlow)<br/>Overfitting</td>
   <td><a href="lessons/3-NeuralNetworks/05-Frameworks/README.md">Text</a><br/><a href="lessons/3-NeuralNetworks/05-Frameworks/Overfitting.md">Text</a></td>
   <td><a href="lessons/3-NeuralNetworks/05-Frameworks/IntroPyTorch.ipynb">PyTorch</a></td>
   <td><a href="lessons/3-NeuralNetworks/05-Frameworks/IntroKeras.ipynb">Keras</a>/<a href="lessons/3-NeuralNetworks/05-Frameworks/IntroKerasTF.ipynb">TensorFlow</a></td>
   <td><a href="lessons/3-NeuralNetworks/05-Frameworks/lab/README.md">Lab</a></td></tr>
<tr><td>IV</td><td><b><a href="lessons/4-ComputerVision/README.md">Computer Vision</a></b></td>
  <td colspan="3"><a href="https://docs.microsoft.com/learn/paths/explore-computer-vision-microsoft-azure/?WT.mc_id=academic-57639-dmitryso"><i>AI Fundamentals: Explore Computer Vision</i></a></td>
  <td></td></tr>
<tr><td></td><td colspan="2"><i>Microsoft Learn Module on Computer Vision</i></td>
  <td><a href="https://docs.microsoft.com/learn/modules/intro-computer-vision-pytorch/?WT.mc_id=academic-57639-dmitryso"><i>PyTorch</i></a></td>
  <td><a href="https://docs.microsoft.com/learn/modules/intro-computer-vision-TensorFlow/?WT.mc_id=academic-57639-dmitryso"><i>TensorFlow</i></a></td>
  <td></td></tr>
<tr><td>6</td><td>Intro to Computer Vision. OpenCV</td><td><a href="lessons/4-ComputerVision/06-IntroCV/README.md">Text</a><td colspan="2"><a href="lessons/4-ComputerVision/06-IntroCV/OpenCV.ipynb">Notebook</a></td><td><a href="lessons/4-ComputerVision/06-IntroCV/lab/README.md">Lab</a></td></tr>
<tr><td>7</td><td>Convolutional Neural Networks<br/>CNN Architectures</td><td><a href="lessons/4-ComputerVision/07-ConvNets/README.md">Text</a><br/><a href="lessons/4-ComputerVision/07-ConvNets/CNN_Architectures.md">Text</a></td><td><a href="lessons/4-ComputerVision/07-ConvNets/ConvNetsPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/4-ComputerVision/07-ConvNets/ConvNetsTF.ipynb">TensorFlow</a></td><td><a href="lessons/4-ComputerVision/07-ConvNets/lab/README.md">Lab</a></td></tr>
<tr><td>8</td><td>Pre-trained Networks and Transfer Learning<br/>Training Tricks</td><td><a href="lessons/4-ComputerVision/08-TransferLearning/README.md">Text</a><br/><a href="lessons/4-ComputerVision/08-TransferLearning/TrainingTricks.md">Text</a></td><td><a href="lessons/4-ComputerVision/08-TransferLearning/TransferLearningPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/4-ComputerVision/08-TransferLearning/TransferLearningTF.ipynb">TensorFlow</a><br/><a href="lessons/4-ComputerVision/08-TransferLearning/Dropout.ipynb">Dropout sample</a><br/><a href="lessons/4-ComputerVision/08-TransferLearning/AdversarialCat_TF.ipynb">Adversarial Cat</a></td><td><a href="lessons/4-ComputerVision/08-TransferLearning/lab/README.md">Lab</a></td></tr>
<tr><td>9</td><td>Autoencoders and VAEs</td><td><a href="lessons/4-ComputerVision/09-Autoencoders/README.md">Text</a></td><td><a href="lessons/4-ComputerVision/09-Autoencoders/AutoEncodersPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/4-ComputerVision/09-Autoencoders/AutoencodersTF.ipynb">TensorFlow</a></td><td></td></tr>
<tr><td>10</td><td>Generative Adversarial Networks<br/>Artistic Style Transfer</td><td><a href="lessons/4-ComputerVision/10-GANs/README.md">Text</a></td><td><a href="lessons/4-ComputerVision/10-GANs/GANPyTorch.ipynb">PyTorch</td><td><a href="lessons/4-ComputerVision/10-GANs/GANTF.ipynb">TensorFlow GAN</a><br/><a href="lessons/4-ComputerVision/10-GANs/StyleTransfer.ipynb">Style Transfer</a></td><td></td></tr>
<tr><td>11</td><td>Object Detection</td><td><a href="lessons/4-ComputerVision/11-ObjectDetection/README.md">Text</a></td><td>PyTorch</td><td><a href="lessons/4-ComputerVision/11-ObjectDetection/ObjectDetection.ipynb">TensorFlow</td><td><a href="lessons/4-ComputerVision/11-ObjectDetection/lab/README.md">Lab</a></td></tr>
<tr><td>12</td><td>Semantic Segmentation. U-Net</td><td><a href="lessons/4-ComputerVision/12-Segmentation/README.md">Text</a></td><td><a href="lessons/4-ComputerVision/12-Segmentation/SemanticSegmentationPytorch.ipynb">PyTorch</td><td><a href="lessons/4-ComputerVision/12-Segmentation/SemanticSegmentationTF.ipynb">TensorFlow</td><td></td></tr>
<tr><td>V</td><td><b><a href="lessons/5-NLP/README.md">Natural Language Processing</a></b></td>
   <td colspan="3"><a href="https://docs.microsoft.com/learn/paths/explore-natural-language-processing/?WT.mc_id=academic-57639-dmitryso"><i>AI Fundamentals: Explore Natural Language Processing</i></a></td>
   <td></td></tr>
<tr><td></td><td colspan="2"><i>Microsoft Learn Module on Natural Language</i></td>
   <td><a href="https://docs.microsoft.com/learn/modules/intro-natural-language-processing-pytorch/?WT.mc_id=academic-57639-dmitryso"><i>PyTorch</i></a></td>
   <td><a href="https://docs.microsoft.com/learn/modules/intro-natural-language-processing-TensorFlow/?WT.mc_id=academic-57639-dmitryso"><i>TensorFlow</i></a></td>
   <td></td></tr>
<tr><td>13</td><td>Text Representation. Bow/TF-IDF</td><td><a href="lessons/5-NLP/13-TextRep/README.md">Text</a></td><td><a href="lessons/5-NLP/13-TextRep/TextRepresentationPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/5-NLP/13-TextRep/TextRepresentationTF.ipynb">TensorFlow</td><td></td></tr>
<tr><td>14</td><td>Semantic word embeddings. Word2Vec and GloVe</td><td><a href="lessons/5-NLP/14-Embeddings/README.md">Text</td><td><a href="lessons/5-NLP/14-Embeddings/EmbeddingsPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/5-NLP/14-Embeddings/EmbeddingsTF.ipynb">TensorFlow</a></td><td></td></tr>
<tr><td>15</td><td>Language Modeling. Training your own embeddings</td><td><a href="lessons/5-NLP/15-LanguageModeling/README.md">Text</a></td><td></td><td><a href="lessons/5-NLP/15-LanguageModeling/CBoW-TF.ipynb">TensorFlow</a></td><td><a href="lessons/5-NLP/15-LanguageModeling/lab/README.md">Lab</a></td></tr>
<tr><td>16</td><td>Recurrent Neural Networks</td><td><a href="lessons/5-NLP/16-RNN/README.md">Text</a></td><td><a href="lessons/5-NLP/16-RNN/RNNPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/5-NLP/16-RNN/RNNTF.ipynb">TensorFlow</a></td><td></td></tr>
<tr><td>17</td><td>Generative Recurrent Networks</td><td><a href="lessons/5-NLP/17-GenerativeNetworks/README.md">Text</a></td><td><a href="lessons/5-NLP/17-GenerativeNetworks/GenerativePyTorch.md">PyTorch</a></td><td><a href="lessons/5-NLP/17-GenerativeNetworks/GenerativeTF.md">TensorFlow</a></td><td><a href="lessons/5-NLP/17-GenerativeNetworks/lab/README.md">Lab</a></td></tr>
<tr><td>18</td><td>Transformers. BERT.</td><td><a href="lessons/5-NLP/18-Transformers/README.md">Text</a></td><td><a href="lessons/5-NLP/18-Transformers/TransformersPyTorch.ipynb">PyTorch</a></td><td><a href="lessons/5-NLP/18-Transformers/TransformersTF.ipynb">TensorFlow</a></td><td></td></tr>
<tr><td>19</td><td>Named Entity Recognition</td><td><a href="lessons/5-NLP/19-NER/README.md">Text</a></td><td></td><td><a href="lessons/5-NLP/19-NER/NER-TF.ipynb">TensorFlow</a></td><td><a href="lessons/5-NLP/19-NER/lab/README.md">Lab</a></td></tr>
<tr><td>20</td><td>Large Language Models, Prompt Programming and Few-Shot Tasks</td><td><a href="lessons/5-NLP/20-LangModels/README.md">Text</a></td><td><a href="lessons/5-NLP/20-LangModels/GPT-PyTorch.ipynb">PyTorch</td><td></td><td></td></tr>
<tr><td>VI</td><td colspan="4"><b>Other AI Techniques</b></td><td></td></tr>
<tr><td>21</td><td>Genetic Algorithms</td><td><a href="lessons/6-Other/21-GeneticAlgorithms/README.md">Text</a><td colspan="2"><a href="lessons/6-Other/21-GeneticAlgorithms/Genetic.ipynb">Notebook</a></td><td></td></tr>
<tr><td>22</td><td>Deep Reinforcement Learning</td><td><a href="lessons/6-Other/22-DeepRL/README.md">Text</a></td><td></td><td><a href="lessons/6-Other/22-DeepRL/CartPole-RL-TF.ipynb">TensorFlow</td><td><a href="lessons/6-Other/22-DeepRL/lab/README.md">Lab</a></td></tr>
<tr><td>23</td><td>Multi-Agent Systems</td><td><a href="lessons/6-Other/23-MultiagentSystems/README.md">Text</a></td><td></td><td></td><td></td></tr>
<tr><td>VII</td><td colspan="4"><b>AI Ethics</b></td><td></td></tr>
<tr><td>24</td><td>AI Ethics and Responsible AI</td><td><a href="lessons/7-Ethics/README.md">Text</a></td><td colspan="2"><a href="https://docs.microsoft.com/learn/paths/responsible-ai-business-principles/?WT.mc_id=academic-57639-dmitryso"><i>MS Learn: Responsible AI Principles</i></a></td><td></td></tr>
<tr><td></td><td colspan="4"><b>Extras</b></td><td></td></tr>
<tr><td>X1</td><td>Multi-Modal Networks, CLIP and VQGAN</td><td><a href="lessons/X-Extras/X1-MultiModal/README.md">Text</a></td><td colspan="2"><a href="lessons/X-Extras/X1-MultiModal/Clip.ipynb">Notebook</a></td><td></td></tr>
</table>

**[Mindmap of the Course](http://soshnikov.com/courses/ai-for-beginners/mindmap.html)**

Each lesson contains some pre-reading material (linked as **Text** above), and some executable Jupyter Notebooks, which are often specific to the framework (**PyTorch** or **TensorFlow**). The executable notebook also contains a lot of theoretical material, so to understand the topic you need to go through at least one version of the notebooks (either PyTorch or TensorFlow). There are also **Labs** available for some topics, which give you an opportunity to try applying the material you have learned to a specific problem. 

Some sections also contain links to **MS Learn** modules that cover related topics. Microsoft Learn provides a convenient GPU-enabled learning environment, although in terms of content you can expect this curriculum to go a bit deeper.

# Getting Started

**Students**, there are a couple of ways to use the curriculum. First of all, you can just read the text and look through the code directly on GitHub. If you want to run the code in any of the notebooks - [read our instructions](./etc/how-to-run.md), and find more advice on how to do it [in this blog post](https://soshnikov.com/education/how-to-execute-notebooks-from-github/).

> **Note**: [Instructions on how to run the code in this curriculum](./etc/how-to-run.md)

However, if you would like to take the course as a self-study project, we suggest that you fork the entire repo to your own GitHub account and complete the exercises on your own or with a group:

- Start with a pre-lecture quiz
- Read the intro text for the lecture 
- If the lecture has additional notebooks, go through them, reading and executing the code. If both TensorFlow and PyTorch notebooks are provided, you can focus on one of them - chose your favorite framework
- Notebooks often contain some of the challenges that require you to tweak the code a little bit to experiment
- Take the post-lecture quiz
- If there is a lab attached to the module - complete the assignment
- Visit the [Discussion board](https://github.com/microsoft/AI-For-Beginners/discussions) to "learn out loud".
- Chat with other learners [on Gitter](https://gitter.im/Microsoft/ai-for-beginners) or [in Telegram channel](http://t.me/ai_for_beginners).

> For further study, we recommend following these [Microsoft Learn](https://docs.microsoft.com/en-us/users/dmitrysoshnikov-9132/collections/31zgizg2p418yo/?WT.mc_id=academic-57639-dmitryso) modules and learning paths.

**Teachers**, we have [included some suggestions](/etc/for-teachers.md) on how to use this curriculum.

---

## Credits

**✍️ Primary Author:** [Dmitry Soshnikov](http://soshnikov.com), PhD <br/>
**🔥 Editor:** [Jen Looper](https://twitter.com/jenlooper), PhD <br/>
**🎨 Sketchnote illustrator:** [Tomomi Imura](https://twitter.com/girlie_mac) <br/>
**✅ Quiz Creator:** [Lateefah Bello](https://github.com/CinnamonXI), [MLSA](https://studentambassadors.microsoft.com/)  <br/>
**🙏 Core Contributors:** [Evgenii Pishchik](https://github.com/Pe4enIks) 

## Meet the Team

[![Promo video](/lessons/sketchnotes/ai-for-beginners.png)](https://youtu.be/m2KrAk0cC1c "Promo video")

> 🎥 Click the image above for a video about the project and the folks who created it!

---

## Pedagogy

We have chosen two pedagogical tenets while building this curriculum: ensuring that it is hands-on **project-based** and that it includes **frequent quizzes**.

By ensuring that the content aligns with projects, the process is made more engaging for students and retention of concepts will be augmented. In addition, a low-stakes quiz before a class sets the intention of the student towards learning a topic, while a second quiz after class ensures further retention. This curriculum was designed to be flexible and fun and can be taken in whole or in part. The projects start small and become increasingly complex by the end of the 12 week cycle.

> Find our [Code of Conduct](etc/CODE_OF_CONDUCT.md), [Contributing](etc/CONTRIBUTING.md), and [Translation](etc/TRANSLATIONS.md) guidelines. Find our [Support Documentation here](etc/SUPPORT.md) and [security information here](etc/SECURITY.md). We welcome your constructive feedback!

> **A note about quizzes**: All quizzes are contained [in this app](https://red-field-0a6ddfd03.1.azurestaticapps.net/), for 50 total quizzes of three questions each. They are linked from within the lessons but the quiz app can be run locally; follow the instruction in the `etc/quiz-app` folder.

## Offline access

You can run this documentation offline by using [Docsify](https://docsify.js.org/#/). Fork this repo, [install Docsify](https://docsify.js.org/#/quickstart) on your local machine, and then in the `etc/docsify` folder of this repo, type `docsify serve`. The website will be served on port 3000 on your localhost: `localhost:3000`. A pdf of the curriculum is available [at this link](/etc/pdf/readme.pdf).

## Help Wanted!

Would you like to contribute a translation? Please read our [translation guidelines](etc/TRANSLATIONS.md).

## Other Curricula

Our team produces other curricula! Check out:

- [Web Dev for Beginners](https://aka.ms/webdev-beginners)
- [IoT for Beginners](https://aka.ms/iot-beginners)
- [Machine Learning for Beginners](https://aka.ms/ml-beginners)
- [Data Science for Beginners](https://aka.ms/datascience-beginners)
