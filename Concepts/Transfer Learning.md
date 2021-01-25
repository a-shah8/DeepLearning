## **Transfer Learning**

In the simplest terms possible, transfer learning means using the features of a pre-trained model in your own implementation, without necessarily having to train your model.

*A Better Definition:*

Transfer learning (TL) is a research problem in machine learning (ML) that focuses on storing knowledge gained while 
solving one problem and applying it to a different but related problem. - Wikipedia
    
**Here are the options you have when using Transfer Learning:**
    
1. You can either choose to train all the layers of this transferred model on the data you wish to.
2. Add new layers and train just those layers on your data.
3. You can freeze all the layers of your model but the last 
   (meaning not training any other layers using your data but just the last layer).
4. Or you can simply use the pre-trained model to perform predictions on your data, 
   in which case you are just using a pre-trained saved model.
   
**_I recommend the readers to google the term 'Transfer Learning' and gain a proper theoretical knowledge and intuition behind the concept._**
