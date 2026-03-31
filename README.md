# ImageBind Project (Milestone)

## Selected Topic
ImageBind: One Embedding Space To Bind Them All

## Objective
This project focuses on understanding and partially re-implementing the main idea of ImageBind.  
In this milestone, we start with image-text embedding to simulate a shared embedding space.

## Current Progress
- Read and analyzed the core idea of ImageBind
- Set up the GitHub repository
- Started working on image-text embedding using CLIP
- Planned an initial benchmark based on similarity between embeddings

## Method
We use a pretrained CLIP model to encode images and text into the same embedding space.  
Then we compare them using cosine similarity.

## Testing (Initial Benchmark)
- Input: image + multiple text descriptions
- Compute cosine similarity between image and text embeddings
- Check whether the correct text has higher similarity than incorrect ones

Example idea:
- "a dog" → high similarity  
- "a cat" → lower similarity  
- "a car" → lower similarity  

## Repository Structure
- `test_image_text.py`: test script for image-text similarity
- `images/`: sample images for testing
- `results/`: output results (screenshots or logs)

## Next Steps
- Complete image-text testing and upload results
- Extend to other modalities (audio, depth, etc.)
- Improve benchmark and evaluation
