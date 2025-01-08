# Semantische Segmentierung mit MaskFormer und Mask2Former (Fine-Tuning & Inference)

Dieses Repository bietet Jupyter-Notebooks und Ressourcen zur Verwendung von MaskFormer sowie Mask2Former für verschiedene Segmentierungsaufgaben. 
MaskFormer ist ein Segmentierungsmodell, das panoptische, semantische und instanzbasierte Segmentierung kombiniert.
Mask2Former ist eine Erweiterung des MaskFormer und nutzt mask attention sowie multi-scale high-resolution features.

## Inhalt des Repositories

1. **Semantische Segmentierung: Inference mit Mask2Former**
   - **Notebook:** `Inference Mask2Former (1).ipynb`
   - **Beschreibung:** Zeigt, wie semantische Segmentierung mit Mask2Former durchgeführt wird.
     
2. **Panoptische Segmentierung: Inference Mask2Former**
   - **Notebook:** `Panoptische Segmentierung_ Inference Mask2Former.ipynb`
   - **Beschreibung:** Demonstriert den Einsatz von Mask2Former für die panoptische Segmentierung.
  
3. **Fine Tuning Mask2Former**
   - **Notebook:** `Fine Tuning Mask2Former (1).ipynb`
   - **Beschreibung:** Erläutert das Fine-Tuning von Mask2Former auf benutzerdefinierten Datensätzen. Beinhaltet die Vorbereitung von Daten, die Anpassung von Hyperparametern und die Modellbewertung.

## Voraussetzungen

1. **Python-Version:** Mindestens Python 3.8
2. **Bibliotheken:**
   - PyTorch
   - Transformers von Hugging Face
   - NumPy
   - Pillow
3. **Hardware:** GPU wird empfohlen für Trainings- und Inference-Aufgaben.
