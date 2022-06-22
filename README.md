# predict_osteoarthritis_CNN_VGG16_model

**create a deep learning model that can provide the probability of having osteoarthritis for a given knee X-ray image.


# Problem

* An orthopaedist is a medical doctor specializing in diagnosing and treating disorders related to the skeletal system. Part of their job is to distinguish between a healthy person and a person with Osteoarthritis by looking at their knee X-ray images.

* Osteoarthritis: Osteoarthritis, commonly known as wear-and-tear arthritis, is a condition in which the natural cushioning between joints — cartilage — wears away. When this happens, the bones of the joints rub more closely against one another with less of the shock-absorbing benefits of cartilage. The rubbing results in pain, swelling, stiffness, decreased ability to move, and, sometimes, the formation of bone spurs.


# Dataset 

The Dataset contains three folders 

   * Test (845 images)
   * Train (2350 images)
   * Valid (641 images)

The train is a dataset that you will use to train your model.

The test is a dataset that you will use to test your model and find out the accuracy and confusion matrix.

Each of these folders has two folders 

#### Test

     Normal 
     Osteoarthritis

#### Train

    Normal       
    Osteoarthritis

#### Valid

    Normal
    Osteoarthritis


# Task

Your task is to create a deep learning model that can provide the probability of having osteoarthritis for a given knee X-ray image.

# conclusion 
**VGG16 model gives as validation accuracy of 97.82%.

**CNN model gives valication accuracy of 82.03% 
