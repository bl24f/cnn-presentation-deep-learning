# Convolutional Neural Networks (CNNs) — Educational Presentation

## Overview
A 16-slide educational presentation introducing Convolutional Neural 
Networks built for Computational Probabilistic Modeling (FSU, Spring 
2026), a graduate-level course also open to senior undergraduates.

The goal: by the end of the presentation, the audience can look at 
a CNN architecture diagram and explain what every single block is 
doing and why it's there.

## Tools & Technologies
- Python (PptxGenJS for slide generation)
- CNN theory: filters, feature maps, pooling, ReLU, backpropagation
- Custom SVG diagrams and visual explainers

## What's Covered
- What convolution is, spatial intuition using the flashlight analogy
- How filters scan images and produce feature maps
- Pooling layers and why they build translation invariance
- How stacking layers builds from edges → shapes → high-level features
- Reading a real CNN architecture diagram
- Benefits over fully connected networks (parameter sharing, 
  local connectivity)
- Real-world applications: medical imaging, object detection, 
  autonomous vehicles

## Key Concepts Demonstrated
- A 3x3 Sobel filter applied by hand to detect edges
- Max pooling reducing a 4x4 grid to 2x2
- Layer hierarchy: early layers find edges, deep layers find concepts
- FISTA/ISTA connection: CNNs applied to MRI reconstruction

## Limitations & Lessons Learned
- Presentation was designed for intuition-building, not 
  implementation, a follow-up Jupyter notebook with working 
  code would strengthen my project.
- Future improvement: add an interactive demo showing real 
  filter activations on an actual image.

## Files
| File | Description |
|------|-------------|
| `CNN_Presentation.pdf` | Final slide deck (16 slides) |

