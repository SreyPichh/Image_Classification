# Introduction 

**Create ML** is an Apple's Framework in which for easy Machine Learning Model Training on Macs. You can extract meaningful insights, or finding relationships between numbers. **Create ML** harnesses the machine learning infrastructure built into the software. 

# Dataset
We will prepare our dataset to test with create ML, in this article I will create **image classification** to classify between cats and dogs and tigers. You can add as many images with as many labels as we want, but for simplicity, I will be building an image that recognize cats, dogs, and tigers. When you open the folder, you will see two more folders, *Testing data* and *Training data*.  

# Create ML Playgrounds & Training data

In Xcode playgrounds for training, evaluating machine learning models.
![Screen Shot 2018-11-14 at 12.18.55 AM.png](https://qiita-image-store.s3.amazonaws.com/0/279562/cb3649c5-3aae-816a-cb8f-2b6c899a9216.png)

It is crucial that you select the Blank template under macOS because **create ML** framework isn't support for iOS playground.

**Snippet Code**

```swift
import CreateMLUI

let builder = MLImageClassifierBuilder()
builder.showInLiveView()
```

That is it and make sure you enable *Live View feature in Xcode Playground* and you will able to see the visual interface.

 **Demo**
 
![demo.gif](https://qiita-image-store.s3.amazonaws.com/0/279562/91393752-7033-ffc1-1b6a-bdae7ba37eab.gif)




