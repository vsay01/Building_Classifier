# Building_classifier

Building Classifier --- You are a data scientist at vacation rental company. So far company was doing good differentiating itself as a company renting single family vacation homes only. Vocation season is about to start, customers renting, and homeowners are listing. Quality control team is overwhelmed. Team is asking is there way to make their life easier. Ypu just accepted the challenge of classifying listing automatically. As a proof of concept you start with 2 big classes residential, industrial.

https://www.kaggle.com/c/building-type/


# Transfer learning

I tested on three different models:
- MobileV2
- Densenet121
- VGG16

# Comparisons

![Test Image 4](https://github.com/vsay01/Building_Classifier/blob/master/model_comparison.png)

# Inferences

- MobileV2
  - Test Loss: 0.252574
  - Test Accuracy: 88% (266/300)
  
- Densenet121
  - Test Loss: 0.196773
  - Test Accuracy: 94% (282/300)
  
- VGG16
  - Test Loss: 0.409700
  - Test Accuracy: 92% (277/300)
