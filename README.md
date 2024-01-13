# Improved Bird Detection Inside Cages

An automated method for detecting birds is prevalent, however, it is difficult to use when the birds are kept in cages. Although there are numerous datasets that may be used to train models for bird detection, including COCO, Birdsnap, and Birds-450, producing a dataset with caged birds can be time-consuming and expensive. In this article, we provide a technique to increase the accuracy of bird detection inside cages without the necessity for a specific dataset.

## Methodology

In order to evaluate the performance of models built solely from the COCO base with models built from COCO plus the cage, we added a transparent cage image to the COCO dataset. We have numerous places, though, that these tasks don’t. In this research, we investigate the impact of including a cage on the objects that we are using to train our model.

## Results

Our findings indicate that adding clear cages to our birds has a significant impact on testing accuracy and mAP. Our mAP50 value was approximately 20% after the original test without utilizing this approach, and after using it, we reached a mAP50 value of 61%.
