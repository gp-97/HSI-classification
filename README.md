# HSI-classification
Hyperspectral Image Classification using:
- DR-CNN (Dimensionality reduction and CNN)
- f-norm reduction
- PCA reduction

The model has been trained on the __Indiana Pines__ dataset.

|[HSI Slice 1](assets/images/img1.png)|[HSI Slice 2](assets/images/img2.png)|[HSI Slice 3](assets/images/img3.png)|[HSI Slice 4](assets/images/img4.png)

|Loss V/s epoch|Accuracy V/s epoch|
|--------------|------------------|
|[Loss V/s epoch](assets/images/res1.png)|[Accuracy V/s epoch](assets/images/res2.png)|

#### Model:
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
