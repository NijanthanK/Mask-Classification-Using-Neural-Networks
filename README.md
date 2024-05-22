# Case Study
Mask identification at bank


![image](https://github.com/NijanthanK/Mask-Classification-Using-Neural-Networks/assets/154366232/3dff2a7b-ee12-456e-af66-efec5fc46950)

# About the dataset
Data Set contains two folders named as Train and Test. Within each of these fol
ders there are 2 different folders WithMask and WithoutMask. WithMask folder 
contains grayscale images of faces with mask. WithoutMask folder contains gra
yscale images of faces with without mask. All images are of resolution 28x28.


A popular bank has implemented a facial recognition system at their entrance to 
authenticate customers before they can enter the building. However, due to the 
COVID-19 pandemic, more and more people have started wearing face 
coverings like surgical masks, which makes it difficult for the facial recognition 
system to accurately identify them. As a result, the bank is experiencing 
increasingly high rates of false rejections. To address this issue, bank has decide
d to develop a reliable solution that can detect whether someone is wearing a
mask or not, so that the facial recognition system can still work effectively


So the data science team took up this task, to design and implement a real-time 
mask detection algorithm using that can accurately distinguish between a person 
without mask and one who is wearing a mask. Team must ensure that their
algorithm runs efficiently on a standard PC, consumes minimal computing 
resources and memory. Additionally, the accuracy of the model should exceed 
95%. Finally, algorithm must be able to handle variations in lighting conditions, 
head pose, occlusions, resolution changes, etc., while maintaining acceptable 
levels of precision and recall.
To achieve these objectives, the data science team will build a Convolutional 
Neural Network (CNN) model inspired by architectures such as VGG16, 
VGG19, or Xception. These established architectures have demonstrated 
effectiveness in image classification tasks and can serve as a solid foundation 
for the mask detection algorithm. By leveraging the capabilities of these 
models, the team aims to develop a highly accurate and efficient mask detection 
solution that meets the bank's requirements and seamlessly integrates with its 
existing infrastructure.
Following the development of the CNN model, the evaluation step will be 
conducted to assess its performance. This evaluation will involve splitting the 
dataset into training and testing sets, using techniques such as cross-validation 
to ensure robustness. The performance metrics considered will include 
accuracy, precision and recall with a specific focus on achieving metrics 
exceeding the 98% threshold established by the bank. Additionally, the model's 
performance will be evaluated on its ability to handle various environmental 
factors and scenarios, ensuring its practical effectiveness in real-world settings.
The ultimate goal is to develop a mask detection algorithm that enhances the 
security and efficiency of the bank's facial recognition system, adapting to the 
new normal of mask-wearing in public spaces while maintaining high 
performance and reliability

# APPROCH TO THE SOLUTION
IMPORT REQUIRED LIBRARIES

READ IMAGES USING IMAGE GENERATOR

VISUALIZE THE IMAGES

RESCALE THE IMAGES BY NORMALIZING

CREATING MODEL ARCHITEHTURE USING VGG19

COMPILE THE MODEL

CHECK OVERFITTING

APPLY DROPOUT,

FIT THE MODEL

PLOT ACUURACY AND LOSS

MODEL SUMMARY

EVALUAVATION METRICS

PREDICTION ON TEST IMAGES

#  Conclusion

1. **Introduction**: Real-time mask detection using CNNs addresses the bank's facial recognition challenges during COVID-19.
2. **CNN Architectures**: Model inspired by VGG16, VGG19, or Xception for high accuracy and efficiency.
3. **Security & Efficiency**: Enhances entrance authentication by detecting masked individuals accurately.
4. **False Rejections**: Mitigates false rejections caused by face coverings.
5. **Performance Metrics**: Focus on accuracy, precision, and recall, aiming for over 95% effectiveness.
6. **Practical Evaluation**: Tested under various conditions to ensure real-world applicability.
7. **Integration**: Seamlessly integrates with the bank's existing facial recognition system.
8. **Safety Commitment**: Demonstrates the bank's dedication to safety and security during the pandemic.
9. **Continuous Improvement**: Regular evaluations to maintain high performance and operational efficiency.
10. **Adaptability**: Aligns with new mask-wearing norms and regulatory requirements.
