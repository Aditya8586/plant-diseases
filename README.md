## Plant Disease Classification with Explainable AI

- Built a multi-class plant disease classifier using transfer learning (EfficientNetB0) on the PlantVillage dataset (38 disease classes across 14 crop species, 54K+ leaf images), achieving 94.7% validation accuracy.
- Applied data augmentation (random flip, rotation, zoom, contrast) to improve model generalisation, and evaluated performance with per-class precision/recall and confusion matrix analysis.
- Implemented explainable AI (XAI) using SHAP and LIME to visualise which regions of a leaf image drove each prediction, making the model's decisions interpretable rather than a black box, a key requirement for real-world agricultural deployment.
