---
Title: ML-Rückblick 1
Date: 2016-01-29 10:20
Category: Allgemein
Tags: Allgemein
Authors: Martin Thoma
Status: draft
---

Der ML-Rückblick gibt einen kurzen Überblick darüber, was seit dem letzen
Rückblick in der Welt des maschinellen Lernens passiert ist.


## New Developments
<!-- Trends -->


### KogSys Demo

Auf [phiresky.github.io/kogsys-demos](http://phiresky.github.io/kogsys-demos/)
könnt ihr euch schnell mal selbst kleine Netzwerke und Datensätze
zusammenklicken. Dann könnt ihr beobachten, wie sich die Klassifikationsgrenzen
ändern.


### HowHot

[howhot.io](https://howhot.io/) ist eine Website, auf welcher man Fotos
hochladen kann. Das Programm findet dann ein Gesicht, kategorisiert in
"männlich" oder "weiblich", schätzt das Alter und die Attraktivität. Es gab
ein paar lustige Ergebnisse (siehe [Reddit](https://www.reddit.com/r/howhot/)
sowie [ein paar weitere Bilder](https://github.com/MartinThoma/seminar-art-in-machine-learning/tree/master/figures/eth-faces)).


### Weitere

* [Large-scale Image Memorability](http://memorability.csail.mit.edu/)


## Publications
<!-- e.g. arXiv -->

### AlphaGo

Google hat eine Go-Engine namens AlphaGo entworfen. Diese soll den europäischen
Go-Meister besiegt haben. Bald soll sie gegen den Go-Weltmeister antreten.

Erstaunlich ist, dass man die Go-Engine von Facebook ([Link](http://www.technologyreview.com/view/544181/how-facebooks-ai-researchers-built-a-game-changing-go-engine/?utm_campaign=socialsync&utm_medium=social-post&utm_source=facebook)) nicht mal erwähnt.

Quellen und Materialien:

* [technologyreview.com](http://www.technologyreview.com/news/546066/googles-ai-masters-the-game-of-go-a-decade-earlier-than-expected/)
* [Google Blog Artikel](https://googleblog.blogspot.de/2016/01/alphago-machine-learning-game-go.html)
* [Nature Artikel](http://www.nature.com/nature/journal/v529/n7587/full/nature16961.html)
* [Nature Video](https://www.youtube.com/watch?v=g-dKXOlsf98)
* Paper: [Mastering the Game of Go with Deep Neural Networks and Tree Search](https://storage.googleapis.com/deepmind-data/assets/papers/deepmind-mastering-go.pdf)


### Deep Residual Networks

Microsoft hat mit einem besonders tiefen neuronalen Netzwerk die Microsoft Common Objects in Context (MS COCO) Challenge gewonnen. Das tiefste Netz hat 1202 Schichten.

Materialien:

* Paper: [Deep Residual Learning for Image Recognition](http://arxiv.org/abs/1512.03385v1)
* Microsoft Blog: [Microsoft researchers win ImageNet computer vision challenge](http://blogs.microsoft.com/next/2015/12/10/microsoft-researchers-win-imagenet-computer-vision-challenge/)


### Weitere

* Thoma: [Creativity in Machine Learning](http://arxiv.org/abs/1601.03642), 2016.
* Radford, Metz und Chintala: [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](http://arxiv.org/abs/1511.06434), 2015. Es ist auch [Code online](https://github.com/Newmu/dcgan_code) verfügbar.


### Blog-Artikel

* Martin Thoma, 19. Januar 2016: [Comparing Classifiers](https://martin-thoma.com/comparing-classifiers/): Ein kurzer Vergleich verschiedener Klassifikationsalgorithmen auf MNIST und IRIS.
* Martin Thoma, 18. Januar 2016: [Function Approximation](https://martin-thoma.com/function-approximation/): Ein sehr kurzes Beispiel, wie man mit gausschen Prozessen Funktionen approximinieren kann.
* Zach Dwiel, 15. Januar 2016, [Evaluation of Deep Learning Toolkits](https://github.com/zer0n/deepframeworks/blob/master/README.md): Ein schöner Vergleich zwischen TensorFlow, CNTK, Theano, Torch und Caffe.
* Abhinav kumar Gupta, 30. November 2015: [Intelligent Photo OCR that reads better than you (Or not)](https://www.linkedin.com/pulse/intelligent-photo-ocr-reads-better-than-you-abhinav-kumar-gupta?trk=pulse_spock-articles)
* 12. November 2015: [Single Artificial Neuron Taught to Recognize Hundreds of Patterns](http://www.technologyreview.com/view/543486/single-artificial-neuron-taught-to-recognize-hundreds-of-patterns/?utm_campaign=socialsync&utm_medium=social-post&utm_source=facebook) ([arxiv](http://arxiv.org/abs/1511.00083))
* Mike Schroepfer, 3. November 2015: [Teaching machines to see and understand: Advances in AI research](https://code.facebook.com/posts/1478523512478471)
* Kyle Hill, 22. Juli 2015: [What happens when artificial intellicence makes Magic: The Gathering cards](http://nerdist.com/what-happens-when-artificial-intelligence-makes-magic-the-gathering-cards/)
* Yarin Gal, 3. Juli 2015, [What My Deep Model Doesn't Know...](http://mlg.eng.cam.ac.uk/yarin/blog_3d801aa532c1ce.html): Wie kann man die Unsicherheit eines Modells quantifizieren?
* Andrej Karpathy, 21. Mai 2015, [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/): Eine Einführung in RNNs. **Sehr Empfehlenswert**. Eine etwas technischere, aber auch sehr gute Einführung ist auf [colah.github.io](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* Stephanie Yee und Tony Chu: [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)


## Software
<!-- e.g. Theano, Keras, ... -->

* Microsoft veröffentlicht das hauseigene Deep Learning-Toolkit CNTK ([Quelle](http://blogs.microsoft.com/next/2016/01/25/microsoft-releases-cntk-its-open-source-deep-learning-toolkit-on-github/))
* [Reinforcement Learning using Tensor Flow](https://github.com/nivwusquorum/tensorflow-deepq)


## Interessante Fragen
<!-- For example StackExchange -->

* Neural Networks
  * [How important is ECC for Neural Networks?](https://groups.google.com/forum/#!topic/lasagne-users/2FgZMACnQR4)
  * [Is it only more computing power why we can now train deeper networks?](https://www.reddit.com/r/MachineLearning/comments/42gipr/is_it_only_more_computing_power_why_we_can_now/)
  * [How exactly does adding a new unit work in Cascade Correlation?](http://datascience.stackexchange.com/q/9672/8820)
  * [The cross-entropy error function in neural networks](http://datascience.stackexchange.com/q/9302/8820)
  * [Can the size of a pooling layer be learned?](http://datascience.stackexchange.com/q/8855/8820)
  * [(Why) do activation functions have to be monotonic?](http://datascience.stackexchange.com/q/9233/8820)
  * [How do subsequent convolution layers work?](http://datascience.stackexchange.com/q/9175/8820)
* [What are the limitations of linear regression + feature / label transformation?](http://math.stackexchange.com/q/1626052/6876)
* [How is a digit recognizer trained when using a Markov Random Field?](http://stackoverflow.com/q/34648517/562769)
* Nomenclature
  * [What is the difference between 'features' and 'descriptors' in computer vision / machine learning?](http://cs.stackexchange.com/q/51373/2914)
  * [Is there a difference between “classification” and “labeling”?](http://datascience.stackexchange.com/q/9074/8820)
  * [What is “semantic segmentation” compared to “segmentation” and “scene labeling”?](http://stackoverflow.com/q/33947823/562769)
* [What is the complexity of classification with SVMs?](http://cs.stackexchange.com/q/51144/2914)
* [Can k-means clustering get shells as clusters?](http://datascience.stackexchange.com/q/9172/8820)
* [Are all images in ImageNet in the leaves?](http://datascience.stackexchange.com/q/9073/8820)
* [What is the difference between a (dynamic) Bayes network and a HMM?](http://datascience.stackexchange.com/q/10000/8820)


## Gemischtes

* Auf Udacity gibt es nun einen Deep Learning Kurs von Google ([Link](https://www.udacity.com/course/deep-learning--ud730))
* Quentin de Laroussilhe: [Introduction to machine Learning](https://docs.google.com/presentation/d/1O6ozzZHHxGzU-McpvEG09hl7K6oQDd2Taw0FOlnxJc8/preview?slide=id.p). Eine sehr kurze Einführung.
* Daniel Povey: [Why simple CNNs with 1x1 kernels may be viewable as learned many-to-many nonlinearities](https://plus.google.com/113952791760990667476/posts/9Hiib9UgUeK).
* Auf [drivendata.org](http://www.drivendata.org/) und [kaggle.com](http://kaggle.com/) gibt es regelmäßig Wettbewerbe.
* Auf [robotart.org](http://robotart.org/) gibt es für 2016 einen Wettbewerb.

## Klassische Werke
<!--  -->

Alte Werke wieder in Erinnerung rufen und einen Hauch von Nostalgie spüren, oder aber einfach nur ein Gespür dafür bekommen, was sich in den letzten Jahren und Jahrzehnten so alles getan hat im Bereich Machine Learning - das soll Sinn und Zweck dieses Abschnitts sein.

Dieses mal zum Thema HMM und deren Anwendung in der Spracherkennung:

[Rabiner, Lawrence R.](http://www.ece.ucsb.edu/Faculty/Rabiner/ece259/) 
*"A tutorial on hidden Markov models and selected applications in speech recognition."* 
Proceedings of the IEEE 77.2 (1989): 257-286. [DOI: 10.1109/5.18626](http://dx.doi.org/10.1109/5.18626)

## Interna
<!-- About ML-KA itself; can also be a link to posts on this website -->

### Paper Discussion Group

Die Paper Discussion Group (PDG) wurde ins Leben gerufen um gemeinsam
wissenschaftliche Veröffentlichungen zu besprechen. Der Gedanke ist, dass man
mehr aus den Veröffentlichungen mitnimmt, wenn man es nicht nur alleine liest,
sondern auch zusammenfasst, anderen erklärt und darüber diskutiert.

Bisher wurden folgende Paper besprochen:

1. Stanford: [Deep Learning Tutorial](http://ufldl.stanford.edu/tutorial/)
2. Krizhevsky, Sutskever und Hinton: [ImageNet Classification with Deep Convolutional Neural Networks](http://www.cs.toronto.edu/~fritz/absps/imagenet.pdf), 2012. ("AlexNet")
3. Szegedy et al: [Going Deeper with Convolutions](http://arxiv.org/abs/1409.4842), 2014. ("GoogLeNet")
4. ?
5. Sermanet et al: [OverFeat: Integrated Recognition, Localization and Detection using Convolutional Networks](http://arxiv.org/abs/1312.6229), 2013.
6. Nochmals OverFeat
7. ?
8. Long, Shelhamer und Darrell: [Fully Convolutional Networks for Semantic Segmentation](http://arxiv.org/abs/1411.4038), 2014
9. ?
10. He, Zhang, Ren und Sun: [Deep Residual Learning for Image Recognition](http://arxiv.org/abs/1512.03385)


Mehr Informationen finden sich auf der
[Projektseite](../paper-discussion-group/).


## Meetings
<!-- ML-KA meetings, but not only -->

* Boston, 12. Mai 2016: Deep Learning Summit ([Link](https://www.re-work.co/events/deep-learning-boston-2016))
* München, 7. Oktober 2015: Deep Learning in Action #3 ([Link](http://www.meetup.com/de-DE/deeplearning/events/225423302/?eventId=225423302))
