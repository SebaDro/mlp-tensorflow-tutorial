# GI-Projekt KI SoSe 2021 - Regression mit Tensorflow
Diese praktische Übung soll in die Python Bibliothek Tensorflow geben. Mittels Regression wird die in der Vorlesung zum 
Multilayer Perceptron vorgestellte Sinusfunktion mit einem Neuronalen Netz modelliert.

## Vorbereitung
Nutzen Sie die bereitgestellt `environment.yml` um eine separate Environment in Conda zu erstellen. Die `environment.yml`
enthält neben der Deep Learning Bibliothek [TensorFlow](https://www.tensorflow.org/) weitere Dependencies für die Bearbeitung
des Jupyter Notebooks.

## Aufgaben
### 1 Tensorflow Einführung
Bearbeiten Sie interaktiv das Jupyter Notebook und versuchen Sie die Vorgehensweise des Trainierens eines Neuronalen Netzes
nachzuvollziehen. Nutzen Sie zur Unterstützung auch die Dokumentation von Tensorflow bzw. die darunter liegende Bibliothek Keras. 
Insbesondere sei auf die folgenden Ressourcen verwiesen:
* https://www.tensorflow.org/guide/keras/sequential_model
* https://www.tensorflow.org/guide/keras/train_and_evaluate
* https://www.tensorflow.org/tutorials/keras/regression

### 2 Trainieren eines eigenen Modells
Definieren Sie ein eigenes sequentielles Modell und variieren Sie dabei verschiedene Parameter des Neuronalen Netzes:
* Anzahl der DenseLayer
* Anzahl der Neuronen in einem Layer
* Aktivierungsfunktion (eine Übersicht der implementierten Aktivierungsfunktionen in Tensorflow finden Sie unter: https://www.tensorflow.org/api_docs/python/tf/keras/activations)
  
Überprüfen Sie, inwiefern sich die Anpassungen auf den Trainingsfortschritt und die Qualität des Modells auswirken.

### 3 Evaluation
Werten Sie die Evaluationsmetriken des linearen Modells, des DNN Models und ihres eigenen Modells aus, indem Sie die
Metriken in ein pandas DataFrame übertragen und angemessen mit matplotlib visualisieren