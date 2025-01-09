# Semantische Segmentierung mit MaskFormer und Mask2Former (Fine-Tuning & Inference)

Dieses Repository bietet Jupyter-Notebooks und Ressourcen zur Verwendung von MaskFormer sowie Mask2Former für verschiedene Segmentierungsaufgaben. 
MaskFormer ist ein Segmentierungsmodell, das panoptische, semantische und instanzbasierte Segmentierung kombiniert.
Mask2Former ist eine Erweiterung des MaskFormer und nutzt mask attention sowie multi-scale high-resolution features.

## Inhalt des Repositories

1. **Semantische Segmentierung: Inference mit Mask2Former**
   - **Notebook:** `Semantische Segmentierung - Inference Mask2Former.ipynb`
   - **Beschreibung:** Zeigt, wie semantische Segmentierung mit Mask2Former durchgeführt wird.
     
2. **Panoptische Segmentierung: Inference Mask2Former**
   - **Notebook:** `Panoptische Segmentierung - Inference Mask2Former.ipynb`
   - **Beschreibung:** Demonstriert den Einsatz von Mask2Former für die panoptische Segmentierung.
  
3. **Fine Tuning Mask2Former**
   - **Notebook:** 1) `Fine Tuning MaskFormer.ipynb` sowie 2)  `Fine Tuning MaskFormer_2.0.ipynb`
   - **Beschreibung:** Erläutert das Fine-Tuning von Mask2Former auf benutzerdefinierten Datensätzen. Beinhaltet die Vorbereitung von Daten, die Anpassung von Hyperparametern und die Modellbewertung. 1) Das Training ist durch einen manuellen Stop, aufgrund von langer Trainingszeit unterbrochen worden. 2) Implementierung von Early Stopping

## Voraussetzungen

1. **Python-Version:** Mindestens Python 3.8
2. **Bibliotheken:**
   - PyTorch
   - Transformers von Hugging Face
   - NumPy
   - Pillow
3. **Hardware:** GPU wird empfohlen für Trainings- und Inference-Aufgaben.
