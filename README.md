# Assessment of Cotton Fiber Maturity using Holographic Images
 
Aproach: Classifying cotton fibers using deep learning and image processing techniques.

_Note: This project is currently under development. More updates to this repo would be commited._

_Please contact [me](mailto:tejarahul618@gmail.com) for more information._


# Example Holographic Images of the Cotton Fibers
<table>
  <tr>
    <td><img src="https://github.com/rahultejagorantala/CottonFiberHolography/blob/main/GIF's/052622DAIJA1-6R2.gif" width=250 height=250 ></td>
    <td><img src="https://github.com/rahultejagorantala/CottonFiberHolography/blob/main/GIF's/071522K1-1R8.gif" width=250 height=250 ></td>
  </tr>
 </table>
These two Images above belong to cotton fibers with different levels of maturity. But visually they cannot be distinguished.
This is a Major problem to solve in cotton fiber industry. Correct classification of cotton fibers according to their maturity can repalce the existing techniques which are not reliable and produce inconsistent results.

# Supervised Classification using Transfer Learning.
I have tried different pretrained models to see which one would work better on our dataset. Overall Efficient-B4 and ResNet-50 work slightly better than other models.(when used a subsampled images of size 240x240 from 1002x1002)
<tr>
    <td><img src="https://github.com/rahultejagorantala/CottonFiberHolography/blob/main/Images/model_structure.jpg" width=150 height=250 ></td>
</tr>
The models perform surprisingly well with an average accuracy on test set of around 80%.

<table>
  <tr>
    <td><img src="https://github.com/rahultejagorantala/CottonFiberHolography/blob/main/Images/Models%20Vs%20Accuracy-1.jpg" width=300 height=250 ></td>
    <td><img src="https://github.com/rahultejagorantala/CottonFiberHolography/blob/main/Images/Models%20Vs%20Accuracy.jpg" width=300 height=250 ></td>
  </tr>
 </table>
 
##  Visualisation of the prediction frame by frame.

<tr>
 <td><img src="https://github.com/rahultejagorantala/CottonFiberHolography/blob/main/Images/Barplot.png" width=300 height=250 ></td>
</tr>

## Visualization of Predictions using GRAD-CAM and Guided BackPropagation.
https://github.com/rahultejagorantala/CottonFiberHolography/assets/101026703/86ef630b-c687-4c86-88db-fe84d3a9ad54





 
