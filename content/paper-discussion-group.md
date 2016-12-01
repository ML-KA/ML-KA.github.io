Title: Paper Discussion Group
Category: Projekte
Date: 2016-01-09 09:45
Tags: Paper, Deep Learning, Autonomes Fahren
Authors: Marvin Teichmann, Martin Thoma
Summary: Die Paper Discussion Group (PDG) ist eine wöchentlich stattfindende Veranstaltung, in der wir gemeinsam ein Paper besprechen und Fragen dazu klären.

# 30. Treffen

* Datum: [30.11.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=30.+PDG&iso=20161130T1730&p1=964&ah=1&am=30)
* Ort: Rintheimer Straße 15, Karlsruhe (Launchpad der Pioniergarage)
* Thema: [Learning to learn by gradient descent by gradient descent](https://arxiv.org/abs/1606.04474)
* Moderator: Jörg&nbsp;Franke ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/1606.04474))


# Kommende Paper

* Gesichtserkennung
    * [DeepFace: Closing the Gap to Human-Level Performance in Face Verification](https://www.cs.toronto.edu/~ranzato/publications/taigman_cvpr14.pdf) (Facebook)
    * [FaceNet: A Unified Embedding for Face Recognition and Clustering](http://arxiv.org/abs/1503.03832) (Google)
    * [A Lightened CNN for Deep Face Representation](http://arxiv.org/abs/1511.02683v1)
* [Structured Output Layer Neural Network Language Models for Speech Recognition](http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=5947610)
* [Teaching Machines to Read and Comprehend](http://arxiv.org/abs/1506.03340)
* [Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](http://arxiv.org/abs/1502.03167)
* [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](http://arxiv.org/pdf/1502.03044v2.pdf) (Soft attention)
* Knowledge transfer
    * [How transferable are features in deep neural networks](http://arxiv.org/abs/1411.1792)
    * [DEEP-CARVING: Discovering Visual Attributes by Carving Deep Neural Nets](http://arxiv.org/abs/1504.04871)
    * [Predicting Deep Zero-Shot Convolutional Neural Networks using Textual Descriptions](http://arxiv.org/abs/1506.00511)
    * [Learning Transferable Features with Deep Adaptation Networks](http://arxiv.org/abs/1502.02791)
* Reinforcement Learning
    * [Asynchronous Methods for Deep Reinforcement Learning](http://arxiv.org/abs/1602.01783v1)
    * [Actor mimic: Deep multitask and transfer reinforcement learning](http://arxiv.org/abs/1511.06342)
    * [Deep Reinforcement Learning with Double Q-learning](http://arxiv.org/abs/1509.06461v3)

# Paper Liste
Eine Auswahl relevanter Paper zum Thema Deep Learning und Pixel-weiser
Klassifikation.

1. [AlexNet] ImageNet Classification with Deep Convolutional Neural Networks,
   *Alex Krizhevsky et. al* (**NIPS 2012**)
2. [GoogLeNet] Going Deeper with Convolutions,
   *Szegedy et. al* (**ArXiv 2014**)
3. [FCNN] Fully Convolutional Networks for Semantic Segmentation,
   *Jon Long and Evan Shelhamer et. al* (**CVPR2015**)
4. [SegNet] SegNet: A Deep Convolutional Encoder-Decoder Architecture for
   Image Segmentation, *Vijay Badrinarayanan et. al* (**ArXiv 2015**)
5. [ResNets] Deep Residual Learning for Image Recognition ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/HeZRS15#MartinThoma))


# Weitere Literatur zu CNNs und Deep-Learning
Einsteigern empfehle ich das [Deep Learning Tutorial](http://ufldl.stanford.edu/tutorial/)der Universität Stanford.

Wer selber mal gerne ein Netz trainieren möchte, dem empfehle ich das [Lasagne
Tutorial](http://martin-thoma.com/lasagne-for-python-newbies/) von Martin
Thoma. Für die Paper-Discussion Group ist es allerdings nicht Voraussetzung
bereits praktisch mit CNNs gearbeitet zu haben.


# Fragen
Beantworte ich gerne. Schreib mir einfach eine kurze E-Mail:
marvxx.teichmaxx@gmaxx.com

Fragen zu Frameworks könnt ihr Martin stellen: `info@martin-thoma.de`

_________________________________________________________________________

# Vergangene Treffen

## Erstes Treffen
<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="256" src="{filename}/images/Cnn_layer.png">
<figcaption style="display:table-caption;caption-side:bottom">Schematische Darstellung von CNNs.<br/>
Quelle: Stanford Deep Learning Tutorial</figcaption>
</figure>

* Datum: 11.11.2015, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: Stanford Deep Learning Tutorial
* Experte: Marvin&nbsp;Teichmann

In dem ersten Treffen möchte ich mit euch über das [Deep Learning Tutorial](http://ufldl.stanford.edu/tutorial/) der Universität Stanford sprechen. Dieses gibt einen kompakten sehr guten Einstieg in moderne tiefe CNNs.

Aufbauend auf dem Tutorial können wir in weiteren Treffen über aktuell führende
Netze, wie *AlexNet* oder *GoogLeNet* diskutieren. Außerdem besteht die
Möglichkeit, dass wir mit Lasagne einfache Netze selber implementieren.


### Vorbereitung
Beschäftigt euch bitte im Vorfeld mit dem [Deep Learning Tutorial](http://ufldl.stanford.edu/tutorial/) der Universität Stanford. Relevante Abschnitte sind:

*  [Multi-Layer Neural Network](http://ufldl.stanford.edu/tutorial/supervised/MultiLayerNeuralNetworks/)
* [Feature Extraction Using Convolution](http://ufldl.stanford.edu/tutorial/supervised/FeatureExtractionUsingConvolution/)
* [Pooling](http://ufldl.stanford.edu/tutorial/supervised/Pooling/)
* [ConvolutionalNeuralNetwork](http://ufldl.stanford.edu/tutorial/supervised/ConvolutionalNeuralNetwork)
* [Autoencoders](http://ufldl.stanford.edu/tutorial/unsupervised/Autoencoders/)

Das Stanford Tutorial ist recht anspruchsvoll. Für ML Einsteiger kann es
hilfreich sein einzelne Schlagwörter auch in externen Quellen (zum Beispiel
Wikipedia) nachzulesen. Bitte lasst euch von offenen Fragen oder
Verständnisschwierigkeiten nicht abschrecken. Hierfür ist auch die Diskussion
Group da.

## Zweites Treffen
<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="256" src="{filename}/images/imagenet.png">
<figcaption style="display:table-caption;caption-side:bottom">ImageNet Classification Challenge: <br/>
AlexNet erkennt Katzen!</figcaption>
</figure>

* Datum: 25.11.2015, 17:30 - 19:00 Uhr
* Ort: Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: AlexNet: Die Renaissance der tiefen Neuronalen Netz
* Experte: Marvin&nbsp;Teichmann

In diesem Treffen möchte ich mit euch über *AlexNet* reden. *AlexNet* ist ein
tiefes Neuronales Netz, welches 2010 überraschend die *ImageNet Classification
Challenge* gewann. Dies leitete eine Renaissance von Deep Learning ein, welche
bis heute anhält. Viele aktuell führende Netze, wie beispielsweise *GoogLeNet*, sind Weiterentwicklungen von *AlexNet*.

In dem zweiten Treffen möchte ich mit euch verstehen was *AlexNet* so
erfolgreich macht. Wir diskutieren dazu die neuen Ideen zum Trainieren und
Evaluieren des Netzes und untersuchen die neue Netzarchitektur.

### Vorbereitung
Beschäftigt euch bitte im Vorfeld mit folgender Quelle:

1. [AlexNet](http://www.cs.toronto.edu/~fritz/absps/imagenet.pdf)


## Drittes Treffen
<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="256" src="{filename}/images/a88.jpg">
<figcaption style="display:table-caption;caption-side:bottom">Inception module: Ein wichtiges Feature von GoogLeNet</figcaption>
</figure>

* Datum: 02.12.2015, 17:30 - 19:00 Uhr
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: GoogLeNet: Going Deeper with Convolutions
* Experte: Marvin Teichmann

In diesem Treffen schauen wir uns *GoogLeNet* an. *GoogLeNet* basiert auf *AlexNet* und enthält einige Verbesserungen, die es Google ermöglicht haben in der ImageNet Challenge 2014 zu führen.

Im zweiten Teil des Treffens beantworten wir dann erste Fragen die euch beim arbeiten mit dem Tensorflow Tutorial gekommen sind.


### Vorbereitung
Beschäftigt euch bitte im Vorfeld mit folgender Quelle:

1. [GoogLeNet](http://arxiv.org/abs/1409.4842)
2. [Tensorflow Session Vorbereitung](http://ml-ka.de/training-your-first-neural-network/)

## Viertes Treffen (Praktisches Treffen)

<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="128" src="{filename}/images/tensorFlow.png">
<figcaption style="display:table-caption;caption-side:bottom"><br/>
Quelle: Wikipedia</figcaption>
</figure>


* Datum: 09.12.2015, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: Implementierung von CNNs mit Tensorflow
* Experte: Martin&nbsp;Thoma



Das nächste Treffen wird ein praktisches Treffen. Wir möchten uns im Vorfeld mit Tensorflow beschäftigen und bei dem Treffen das Framework unterhalten.

### Vorbereitung
Zur Vorbereitung tut bitte folgendes:

1. Installiert Python, falls noch nicht vorhanden schaut euch das [offizielle Python 2 tutorial](https://docs.python.org/2/tutorial/) an.
2. [Installiert Tensor Flow](http://www.tensorflow.org/get_started/os_setup.html)
3. Stelle sicher, dass Tensor Flow funktionier ([siehe auch](http://ml-ka.de/training-your-first-neural-network/))
4. Bearbeite [MNIST For ML Beginners](http://www.tensorflow.org/tutorials/mnist/beginners/index.html) tutorial
5. Registriere bei Kaggle, und bearbeite [Digit Recognizer task](https://www.kaggle.com/c/digit-recognizer). Modifiziere dazu die Implementation von Schritt&nbsp;4

## Fünftes Treffen

<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="256" src="{filename}/images/woman_bb.png">
<figcaption style="display:table-caption;caption-side:bottom"><br/>
Lokalisierung eines Kopfes.</figcaption>
</figure>

* Datum: 16.12.2015, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: Overfeat: Objektlokalisierung mit CNNs
* Experte: Michael&nbsp;Weber

Overfeat ermöglicht es Objecte (z.b. Autos) auf Bildern zu lokalisieren. Die Aufgabe ist es eine Bounding-Box um das zu Lokalisierende Objekt zu zeichnen.

### Vorbereitung
Beschäftigt euch im Vorfeld mit Overfeat:

1. [Overfeat](http://arxiv.org/abs/1312.6229)

Laut Michael ist die Quelle sehr Umfrangreich. Wir werden in der PDG also vermutlich nicht ganz durchkommen. Wer es also nicht schafft das gesammte Paper zu lesen kann trotzdem gerne vorbeikommen.


## Sechstes Treffen

<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="256" src="{filename}/images/arma.png">
<figcaption style="display:table-caption;caption-side:bottom"><br/>
Lokalisierung von Köpfen.</figcaption>
</figure>

* Datum: 21.12.2015, 16:15
* Ort:  KIT Biblothek (30.50) R31 (Medienzentrum)
* Thema: Overfeat2: Localization and Detection
* Experte: Michael&nbsp;Weber

Wir besprechen Sektion 4 und 5 von Overfeat.

### Vorbereitung
Beschäftigt euch im Vorfeld mit Overfeat:

1. [Overfeat](http://arxiv.org/abs/1312.6229)

## Siebtes Treffen

<figure style="display:table;float:right">
<img style="float:right;" align="middle"  width="256" src="{filename}/images/horse640_final.png">
<figcaption style="display:table-caption;caption-side:bottom"><br/>
Segmentierung eines Bildes.</figcaption>
</figure>

* Datum: 13.01.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: Fully Convolutional Networks for Semantic Segmentation ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/1411.4038#MartinThoma))
* Experte: Marvin&nbsp;Teichmann

In dem nächsten Treffen verstehen wir die FCNs welche Long und Shelhammer auf der CVPR 2015 vorgestellt haben. Diese haben innerhalb weniger Monate viel Aufmerksamkeit erhalten und wurden in kurzer Zeit bereits fast 200 mal zitiert.

### Vorbereitung
Lest bitte im Vorfeld das folgende Paper:

1. [Fully Convolutional Networks for Semantic Segmentation](http://www.cs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf),
   *Jon Long and Evan Shelhamer et. al* (**CVPR2015**)


## Achtes Treffen

* Datum: 20.01.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* Experte: Leonard&nbsp;Lausen

## Neuntes Treffen

* Datum: 27.01.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: [Recurrent Models of Visual Attention](http://arxiv.org/abs/1406.6247)
* Experte: Leonard&nbsp;Lausen

Bei dem Treffen wurden folgende Paper für weitere Treffen vorgeschlagen:

* [Playing Atari with Deep Reinforcement Learning](http://arxiv.org/abs/1312.5602)
    * [Actor mimic: Deep multitask and transfer reinforcement learning](http://arxiv.org/abs/1511.06342)
* [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](http://arxiv.org/pdf/1502.03044v2.pdf) (Soft attention)
* [How transferable are features in deep neural networks](http://arxiv.org/abs/1411.1792)
* Knowledge transfer
    * [DEEP-CARVING: Discovering Visual Attributes by Carving Deep Neural Nets](http://arxiv.org/abs/1504.04871)
    * [Predicting Deep Zero-Shot Convolutional Neural Networks using Textual Descriptions](http://arxiv.org/abs/1506.00511)
    * [Learning Transferable Features with Deep Adaptation Networks](http://arxiv.org/abs/1502.02791)


## Zehntes Treffen

* Datum: 03.02.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: [Deep Residual Learning for Image Recognition](http://arxiv.org/abs/1512.03385)
* Experte: Martin&nbsp;Thoma ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/HeZRS15#MartinThoma))

Going Deeper - mal wieder. In dem Paper wird ein Netz vorgestellt, welches
bei ILSVRC deutlich besser ist als die vorherigen Resultate.


## Elftes Treffen

* Datum: 10.02.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](http://arxiv.org/abs/1502.03044)
* Experte: Leonard&nbsp;Lausen


## Zwölftes Treffen

* Datum: 17.02.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: [Unsupervised Visual Representation Learning by Context Prediction](http://arxiv.org/pdf/1505.05192v3.pdf)
* Experte: Andrey&nbsp;Yegorov


## 13. Treffen

* Datum: 24.02.2016, 17:30
* Ort:  Seminarraum: -107, Infobau (Geb. 50.34)
* Thema: [Playing Atari with Deep Reinforcement Learning](http://arxiv.org/abs/1312.5602)
* Experte: Marvin&nbsp;Teichmann


## 14. Treffen

* Datum: [26.04.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=PDG&iso=20160426T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau (Geb. 50.34)
* Thema: [Deep Networks with Stochastic Depth](http://arxiv.org/abs/1603.09382)
* Experte: Martin&nbsp;Thoma ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=huang2016networks#MartinThoma))


## 15. Treffen

* Datum: [03.05.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=15.+PDG&iso=20160503T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau (Geb. 50.34)
* Thema: [Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks](http://arxiv.org/abs/1506.01497)
* Experte: Martin&nbsp;Thoma ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=conf/nips/RenHGS15))


## 16. Treffen

* Datum: [17.05.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=16.+PDG&iso=20160517T1730&p1=964&ah=1&am=30)
* Ort: IISM-Meetingraum-282 ([Fritz-Erler-Straße 23](https://goo.gl/maps/7t9si2dLkoQ2))
* Thema: [Understanding the difficulty of training deep feedforward neural networks](http://jmlr.org/proceedings/papers/v9/glorot10a/glorot10a.pdf)
* Moderator: Martin&nbsp;Thoma ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/jmlr/GlorotB10#MartinThoma))


# 17. Treffen

* Datum: [24.05.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=16.+PDG&iso=20160524T1730&p1=964&ah=1&am=30)
* Ort: IISM-Meetingraum-282 ([Fritz-Erler-Straße 23](https://goo.gl/maps/7t9si2dLkoQ2)) (ihr müsst klingeln)
* Thema: [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783)
* Moderator: Fabian&nbsp;Both ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/MnihBMGLHSK16))


## 18. Treffen

* Datum: [31.05.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=17.+PDG&iso=20160531T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau ([Geb. 50.34](https://goo.gl/maps/XVYLoJG7o762))
* Thema: [Speech Recognition with Deep Recurrent Neural Networks](https://arxiv.org/abs/1303.5778)
* Moderator: Jörg&nbsp;Franke ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=conf/icassp/GravesMH13))

## 19. Treffen

* Datum: [07.06.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=19.+PDG&iso=20160607T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau ([Geb. 50.34](https://goo.gl/maps/XVYLoJG7o762))
* Thema: [Distributed Representations of Words and Phrases and their Compositionality](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
* Moderator: Fabian&nbsp;Both ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=mikolov2013distributed))

Weiteres:

* [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781.pdf)
* TensorFlow: [Vector Representations of Words](https://www.tensorflow.org/versions/r0.8/tutorials/word2vec/index.html)
* Blog-Artikel: [The amazing power of word vectors](https://blog.acolyer.org/2016/04/21/the-amazing-power-of-word-vectors/) (schöne Bilchen :-) )

## 20. Treffen

* Datum: [14.06.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=20.+PDG&iso=20160614T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau ([Geb. 50.34](https://goo.gl/maps/XVYLoJG7o762))
* Thema: [Neural Turing Machines](https://arxiv.org/abs/1410.5401)
* Moderator: Martin&nbsp;Thoma ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/GravesWD14))

Weiteres:

* [NTM-Lasagne: A Library for Neural Turing Machines in Lasagne](https://medium.com/snips-ai/ntm-lasagne-a-library-for-neural-turing-machines-in-lasagne-2cdce6837315)

## 21. Treffen

* Datum: [28.06.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=21.+PDG&iso=20160628T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau ([Geb. 50.34](https://goo.gl/maps/XVYLoJG7o762))
* Thema: [DeepFace: Closing the Gap to Human-Level Performance in Face Verification](https://www.cs.toronto.edu/~ranzato/publications/taigman_cvpr14.pdf)
* Moderator: Martin&nbsp;Thoma ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=conf/cvpr/TaigmanYRW14))

## 22. Treffen

* Datum: [05.07.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=22.+PDG&iso=20160705T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau ([Geb. 50.34](https://goo.gl/maps/XVYLoJG7o762))
* Thema: [Memory Networks](http://arxiv.org/abs/1410.3916#)
* Moderator: Jörg&nbsp;Franke ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/corr/WestonCB14))

Supplementary resources:

* [Implementing Dynamic memory networks](https://yerevann.github.io/2016/02/05/implementing-dynamic-memory-networks/)
* [Memory networks](https://blog.acolyer.org/2016/03/10/memory-networks/)
* [Memory Neural Networks :MemNN](http://blog.themusio.com/2016/03/09/memory-neural-networks-memnn/)
* [ATTENTION AND MEMORY IN DEEP LEARNING AND NLP](http://www.wildml.com/2016/01/attention-and-memory-in-deep-learning-and-nlp/)


## 23. Treffen

* Datum: [12.07.2016, 17:30](http://www.timeanddate.com/worldclock/fixedtime.html?msg=23.+PDG&iso=20160712T1730&p1=964&ah=1&am=30)
* Ort: Seminarraum 131, Infobau ([Geb. 50.34](https://goo.gl/maps/XVYLoJG7o762))
* Thema: [Generating Design Suggestions under Tight Constraints with
Gradient-based Probabilistic Programming](http://stanford.edu/~dritchie/graphics-hmc.pdf)
* Moderator: Jùnjun&nbsp;Nigel&nbsp;Wàn ([Zusammenfassung](http://www.shortscience.org/paper?bibtexKey=journals/cgf/RitchieLGH15))
