# Thema 2 - Klassifizierung: Autoencoder und GAN

## Setup
#### 1. Schritt: Das GitHub repository klonen
Im Terminal soll zunächst ins Ziel-Directory navigiert werden.
Anschließend kann über den Befehl
`git clone https://github.com/Diel065/mlClassification.git`
das Projekt heruntergeladen werden.

#### 2. Schritt - Packages installieren
Auch die benutzen Libraries wurden nicht auf GitHub gespeichert. Sie können allerdinges ganz einfach lokal installiert werden. 

Alle benutzten Packages wurden in der _tf_requirements.txt_ Datei gespeichert. 
Hierbei handelt es sich konkret nur um die Tensorflow dependencies, da diese nicht zusammen mit PyTorch funktionieren. Daher bevorzugt mit venvs arbeiten, um sowohl ein PyTorch-venv als auch ein Tensorflow venv aufzusetzen.
Der Befehl `pip install -r tf_requirements.txt` installiert alle benutzen Packages des Projektes in dem Virtual Enviroment.
Die Packages funktionieren auf der neues Python Version, bei der Bearbeitung wurde jedoch Python=3.11.4 verwendet.

> Es muss vorher sicher gestellt werden, dass das man sich im Projekt-Directory befindet

## Netze trainieren und evaluieren

Sowohl der AE als auch das GAN hat sein eigenes File für den MNIST sowie für den CIFAR10 Datensatz. Führt man diese in einer IDE aus, wird das entsprechende Netz trainiert. 
