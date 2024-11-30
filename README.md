## Experiment model for classifying different kinds of waveforms.

# Input: 
- Image 100x250, 32 bit depth
- 3 color channel

# Output: 
- 3 output class, corresponding to 3 numeric labels: 0 (Normal), 1 (Atrial-related), 2 (Block-related)

# Model:
- Transfer learning using ResNet50 as base model
- Will update this section soon after experimenting more...