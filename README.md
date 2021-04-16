# HSI-classification
Hyperspectral Image Classification using:
- DR-CNN (Dimensionality reduction and CNN)
- f-norm reduction
- PCA reduction

The model has been trained on the __Indiana Pines__ dataset.

### Model: "sequential_4"
|Layer (type)|Output Shape|Param|   
|----------------------|----------------------------|----------------|
|conv2d_7 (Conv2D)|(None, 14, 14, 16)|416|       
|max_pooling2d_7|(MaxPooling2 (None, 7, 7, 16)|0|         
|conv2d_8 (Conv2D)|(None, 4, 4, 32)|8224|      
|max_pooling2d_8|(MaxPooling2 (None, 2, 2, 32)|0|         
|flatten_4 (Flatten)|(None, 128)|0|         
|dense_7 (Dense)|(None, 100)|12900|     
|dense_8 (Dense)|(None, 17)|1717|      

- Total params: 23,257
- Trainable params: 23,257
- Non-trainable params: 0
