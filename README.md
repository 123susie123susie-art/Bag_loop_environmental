# Bag_loop_environmental
# AI-Mediated Fashion Upcycling: A Framework for Transforming Post-Consumer Garments via CNN and Diffusion Models
<img width="836" height="375" alt="image" src="https://github.com/user-attachments/assets/8cee9660-753c-47ae-9c43-df536485d3a9" />

## Main Process: 
Users upload pictures of their old clothes, and the model identifies the attributes of the clothes in the pictures (such as the material, color, size, and other elements). Based on the identified attributes, several bag designs are created for users to choose from, and the transaction is completed.

## System Architecture Overview:
<img width="1004" height="414" alt="image" src="https://github.com/user-attachments/assets/d01cacd5-f0ca-464b-b7f7-a84e1b739246" />

(1) Semantic Perception, where a CNN-based model extracts fine-grained attributes from the source garment

(2) Knowledge Alignment, which translates these attributes into multi-modal prompts

(3) Generative Transformation, where a Latent Diffusion Model (LDM) synthesizes the final upcycled design based on semantic and textural constraints.

## Perception Layer: Fine-grained Attribute Extraction
<img width="883" height="428" alt="image" src="https://github.com/user-attachments/assets/f52dcab7-3698-4b96-9e1a-ed5af931a323" />

## Generation Layer: Conditioned Image Synthesis
<img width="865" height="487" alt="image" src="https://github.com/user-attachments/assets/a7cb153b-bc64-4e07-912c-aa9aff39fcd8" />
