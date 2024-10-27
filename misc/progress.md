Progress Overview:
To date, significant strides have been made in the development of image captioning system. I have successfully selected the MSCOCO dataset for its extensive variety and comprehensive annotations, ensuring a robust foundation for training and evaluation.
Technical Approach:
Image Embedding: we have integrated the Inception V3 pre-trained model to extract high-quality image embeddings. This model was chosen for its proven performance in feature extraction tasks.
Caption Generation Models: Implementation of both LSTM and GRU architectures has been completed. Initial experiments with LSTM have shown promising results in generating coherent and contextually relevant captions.
Model Training: The models have been trained on 80% of the MSCOCO dataset, with the remaining 20% reserved for testing. Training involved fine-tuning the pre-trained Inception V3 model to optimize feature extraction specific to our dataset.
Implementation:
Data Preprocessing: Completed preprocessing steps including image resizing, normalization, and tokenization of captions.
Model Integration: Established the pipeline connecting Inception V3 embeddings with LSTM and GRU networks.
Initial Testing: Conducted preliminary tests to ensure the models are learning effectively, with initial captions demonstrating reasonable accuracy and relevance.
Evaluation:
Metrics Setup: Established evaluation frameworks using BLEU scores and semantic distance measures to assess the quality of generated captions against ground truth.
Preliminary Results: Early evaluations indicate that LSTM models slightly outperform GRU in maintaining contextual coherence, though GRU models train faster.
Future Directions:
Model Optimization: Further fine-tuning of both LSTM and GRU models to enhance caption accuracy and diversity.
Comparison with LLMs: Planning to integrate and compare results with captions generated by a Large Language Model (LLM) to benchmark performance.
Slide Preparation: Currently developing a comprehensive slide deck covering problem description, data sources, technical approaches, implementation details, initial results, evaluation metrics, and future work, scheduled for presentation on October 30.
Conclusion: The project is progressing smoothly with foundational components successfully implemented. Ongoing efforts will focus on refining model performance and comprehensive evaluation to achieve high-quality image captioning results.
Next Steps:
Complete training and fine-tuning of GRU models.
Conduct thorough evaluations and comparative analysis with LLM-generated captions.
Finalize and polish the presentation slides for the upcoming mid-term presentation.