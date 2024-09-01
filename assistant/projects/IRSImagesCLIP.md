# IRSImagesCLIP
## Title 
Image Retrieval System using Machine Learning.

## skills 
- IRS
- ML
- AI

## keywords
- Embeddings
- Multimodals Embeddings
 
## Languages
- Python

## description
In this project, the problem of precise image retrieval is addressed. The work employs a new approach: the application of the Segment Anything (SAM) segmentation models and the Constractive Language-Image Pretraining (CLIP) model for the generation of multimodal embeddings. Special emphasis is placed on image retrieval via precise queries, taking into account the position of image 
segments that compose the same, processing both text and images.

Este es mi proyecto de tesis para el titulo de cientifico de la computacion. En ese proyecto el enfoque es recuperar imagenes usando texto como entrada. En tiempo de indexacion se crean embedding de la imagen y y segmentaciones de la misma para lograr recuperar las mismas mediante informacion posiscional. Para segmentar las imagenes se usa el modelo de Meta SAM (segment Anything model), con ello se segmenta la imagen y a cada segementacion se le genera un embedding multimodal usando el Modelo de OpenAI CLIP, este modelo genera embeddings tanto para imagenes como para texto. Usando todos los embeddings generados, tanto imagenes como segmentacion de la imagen original se hace la recuperacion matcheando texto contra imagen.
