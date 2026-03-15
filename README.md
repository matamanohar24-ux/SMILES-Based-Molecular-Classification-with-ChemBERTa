# SMILES-Based-Molecular-Classification-with-ChemBERTa

I recently worked on a project exploring how transformer models can be applied to molecular representations (SMILES) for cheminformatics tasks.

In this project, I built a complete machine learning pipeline that fine-tunes a ChemBERTa transformer model to classify molecules based on natural product–likeness (p_np) using SMILES strings.

Pipeline overview:

SMILES dataset
→ Data preparation and cleaning
→ Tokenization using the ChemBERTa tokenizer
→ ChemBERTa transformer encoder
→ Fine-tuning experiments including baseline training, class-weighted training, frozen transformer layers, partial layer freezing, custom classification head, and domain adaptation using masked language modeling
→ Model evaluation and comparison
→ Selection of the best performing model
→ Deployment as a FastAPI service for SMILES prediction

The goal of this project is to build an AI model that can quickly screen molecules and predict whether they resemble natural-product-like compounds. Molecules with natural-product-like characteristics often contain structural patterns associated with biological activity, making them important in early drug discovery.

This type of model can help prioritize molecules from large chemical libraries, support screening workflows, and provide insights into molecular structure patterns learned by transformer models.


#MachineLearning #AI #DrugDiscovery #Cheminformatics #Transformers #SMILES #Bioinformatics
