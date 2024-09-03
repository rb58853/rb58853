# Image Retrieval System using Machine Learning

## Overview

This project focuses on developing an advanced Image Retrieval System (IRS) using machine learning techniques. It employs cutting-edge models like Segment Anything (SAM) and Constrative Language-Image Pretraining (CLIP) to create multimodal embeddings for precise image retrieval based on text queries.

### Key Features

- Multimodal Embeddings Generation
- Image Segmentation using SAM Model
- Text-to-Image Matching
- Positional Information Processing

### Technologies Used

- Python
- Segment Anything (SAM) Model
- Constrative Language-Image Pretraining (CLIP) Model

### Skills Demonstrated

- Information Retrieval Systems (IRS)
- Machine Learning (ML)
- Artificial Intelligence (AI)
- Image Processing
- Natural Language Processing

### Description

This project tackles the challenging task of precise image retrieval using text queries. The approach involves:

1. **Image Segmentation**:
   - Utilizes the Segment Anything (SAM) model to divide images into meaningful segments
   - Allows for more granular and contextual understanding of image contents

2. **Multimodal Embeddings Generation**:
   - Employs the CLIP model to create embeddings for both images and text
   - Generates multimodal embeddings for each image segment

3. **Indexing Process**:
   - Creates embeddings for entire images and their segments during indexing
   - Stores positional information of segments within images

4. **Query Processing**:
   - Accepts text queries as input
   - Generates embeddings for query text using CLIP model

5. **Retrieval Mechanism**:
   - Matches query embeddings against stored image and segment embeddings
   - Considers positional information for more accurate retrieval

### Implementation Details

- Uses Python as the primary development language
- Implements efficient storage and retrieval mechanisms for large-scale image datasets
- Develops algorithms for processing and matching multimodal embeddings

### Thesis Project Significance

This project serves as the author's thesis for the Computer Science degree. It focuses specifically on retrieving images using text input, leveraging advanced machine learning models to achieve high precision in image retrieval.

### Keywords

- Embeddings
- Multimodal Embeddings