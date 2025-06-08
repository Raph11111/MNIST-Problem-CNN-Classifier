# Deep Learning - MNIST-Klassifikation mit Convolutional Neural Network (CNN)  🧠📊

## Übersicht
Dieses Projekt widmet sich der Lösung des klassischen MNIST-Problems (Klassifikation handgeschriebener Ziffern von 0 bis 9) mithilfe eines Convolutional Neural Network (CNN). Es demonstriert die Implementierung eines vollständigen Deep-Learning-Workflows in PyTorch, von der Datenvorbereitung über den Modellaufbau bis hin zum Training und der Evaluierung.

## Motivation
Als Übungsaufgabe im Rahmen meines Studiums und zur Vertiefung meiner Kenntnisse im Bereich Deep Learning und Computer Vision wurde dieses Projekt erstellt. Es ermöglichte mir, praktische Erfahrungen mit Faltungsnetzen zu sammeln und deren Leistungsfähigkeit im Vergleich zu traditionellen neuronalen Netzen zu erleben.


## Funktionen
* Laden und Vorverarbeiten des MNIST-Datensatzes.
* Definition eines mehrschichtigen Convolutional Neural Network (CNN) mit `nn.Conv2d`, `nn.MaxPool2d`, `nn.ReLU` und `nn.Dropout`-Layern.
* Training des Modells mit dem Adam-Optimizer und Cross-Entropy Loss.
* Evaluierung der Modellgenauigkeit auf einem separaten Testdatensatz.
* Beobachtung des Trainingsfortschritts (Verlust und Genauigkeit pro Epoche).

## Technologien
* Python
* PyTorch (torch, torchvision)
* NumPy
* Matplotlib
* Jupyter Notebook

## Installation und Ausführung
1.  **Klonen Sie das Repository:**
    `git clone https://github.com/Raph11111/MNIST-Problem-CNN-Classifier.git`
    `cd mnist-cnn-pytorch`
2.  **Virtuelle Umgebung erstellen und aktivieren (optional, aber empfohlen):**
    `python -m venv venv`
    `source venv/bin/activate` (Linux/macOS) oder `.\venv\Scripts\activate` (Windows)
3.  **Abhängigkeiten installieren:**
    `pip install -r requirements.txt`
4.  **Jupyter Notebook starten:**
    `jupyter notebook MNIST-Classifier-with-CNN.ipynb`
5.  Führen Sie die Zellen im Notebook aus, um das Modell zu trainieren und zu evaluieren.

## Bezug zur Stellenausschreibung (Werkstudent Softwareentwicklung – Künstliche Intelligenz)
Dieses Projekt ist direkt relevant für die ausgeschriebene Stelle, da es meine praktischen Fähigkeiten in folgenden Bereichen unter Beweis stellt:
* **Künstliche Intelligenz & Maschinelles Lernen:** Fundiertes Verständnis und praktische Anwendung von Deep Learning-Konzepten (insbesondere CNNs für Computer Vision).
* **PyTorch:** Umfangreiche Erfahrung im Aufbau, Training und der Evaluierung neuronaler Netze mit PyTorch, einem der führenden Frameworks in der KI-Forschung und -Entwicklung.
* **Softwareentwicklung mit Python:** Strukturierter Code und Implementierung eines vollständigen ML-Workflows.
* **Datenanalyse und -verarbeitung:** Umgang mit Bilddaten und deren Transformationen für Deep Learning-Modelle.
* **Problemlösungsfähigkeiten:** Anwendung bekannter Algorithmen zur Lösung eines Klassifikationsproblems.
* **Erfahrung im Erstellen von Prompts:** Obwohl dieses Projekt kein direktes Prompt Engineering im Sinne von Large Language Models (LLMs) beinhaltet, zeigt die detaillierte Dokumentation des Workflows und der Modellarchitektur mein Verständnis für präzise Anweisungen und den Aufbau von Systemen, was eine übertragbare Fähigkeit im Umgang mit komplexen KI-Modellen ist.
