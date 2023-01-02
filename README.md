# "Binary Classification of Brain MRI Images for Detection of Brain Tumor using Convolutional Neural Network"
Classification of brain tumor is a critical task to assess the tumors and settle on a treatment 
resolution as per their classes. Although there are many imaging methods used to identify brain 
tumors, nevertheless MRI is most frequently used. The popularity of MRI relies on the fact that it 
has a condescending image quality despite being non-invasive and not involving any ionizing 
radiation. In recent times deep learning has shown an extraordinary performance on classification 
problems. Acknowledging that, CNN (Convolutional Neural Network) a class of deep neural 
networks is used in this thesis for binary classification of brain MRI images. The dataset includes 
253 images in total, among which, 98 are non-tumor images and 155 are tumor images. The best 
results are shown by augmented dataset and pre-trained models. Without augmentation the dataset 
is tremendously small and tends to overfit the training data and thus results in bad performance. 
However, after augmentation the result does not improve much while using the simple 1, 2 or 3
convolutional layer architecture. The accuracy on unseen test data is 88.39%, 87.10% and 82.85%
for 1, 2 and 3-layer models respectively. The pre-trained models have rather finer results other 
than ResNet50 which has the lowest accuracy rate of all models and it is 82.20%. VGG-16 has 
obtained 97.42%, VGG-19 has obtained 97.10% and InceptionV3 has obtained 96.45% accuracy 
on test data. Even though VGG-16 has the highest accuracy rate, it takes 13.8 minutes per epoch 
whereas, InceptionV3 takes only 6.6 minutes. Therefore, the most convenient CNN model would 
be InceotionV3 considering all the potentials such as the performance level as well as the 
computational cost.
