# Sars-Escape Network with Augmented Dataset
## Overview
This repository houses a pretrained Sars-Escape network model and a dataset of synthetic spike protein sequences generated using a Generative Adversarial Network (GAN). The resources here facilitate research on viral escape mechanisms and potential therapeutic design strategies.
## Contents
•	Pretrained Sars-Escape model:\\
o	Trained to detect potential escape mutations in SARS-CoV-2 spike protein sequences.  
o	Located in models/pretrained_sars_escape_spike_detection_model/m4.  
•	Generated spike protein sequences:\\
o	Produced using a GAN to augment the training dataset.  
o	Found in results/gan_generated_escape_sequences.csv  
•	Original Code for generating sequences was leveraged using:  
o	Based on https://github.com/Biomatter-Designs/ProteinGAN.  
•	Code for training the Sars-Escape model:  
o	Based on https://github.com/PremSinghBist/Sars-CoV-2-Escape-Model.  
o	Available in the code/model_training directory.  
## Reference
For a comprehensive understanding of the Sars-Escape network training process, please refer to the following publication:  
•	Bist, P. S., Tayara, H., & Chong, K. T. (2023). Sars-escape network for escape prediction of SARS-COV-2. Briefings in Bioinformatics, 24(3), bbad140. https://doi.org/10.1093/bib/bbad140

