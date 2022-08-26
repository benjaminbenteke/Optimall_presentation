# Optimall presentation: Explainable Deep neural networks

## Problem understanding

The main paper is <a href= 'https://arxiv.org/pdf/1703.01365.pdf'> Axiomatic Attribution for Deep Networks </a>.

The main idea behind this paper is to identify how much an inputs feature (pixels, for instance) contribute to the prediction of a given input data. This is very important for the model explainability. The method that we use is <b> Integrated gradient</b>.

In <a href= 'https://arxiv.org/pdf/1703.01365.pdf'> Axiomatic Attribution for Deep Networks </a>, the experiments were done on:
<ol>
  <li> <b> An Object Recognition Network </b> </li>
  <li> <b> Diabetic Retinopathy Prediction </b> </li>
  <li> <b> Question Classification </b> </li>
  <li> <b> Neural Machine Translation </b> </li>
  <li> <b> Chemistry Models </b> </li> 
</ol>

Whereas, this presentation focus on <b> An Object Recognition task </b>.

Go to: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wKN9dUU5NAwlyg6_f3iE2VpRMBVwUPH9?authuser=1#scrollTo=9vKBnbYAQkEL
)


## Results
The original image is:

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/70bfca4555cca92e.jpg' width= 50%>

The interpolated images are:

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/interpolated_images.png' width= 50% height= 50%>

<b> Experimentation results: </b> The left and right figures represent </b> gradient method </b> result and <b> Integrated Gradient method </b> results respectively. As you can see, <b> Integrated Gradient method </b> works better than <b> Gradient method </b>, because it the Integrated Gradient image seems the original image. See the Attention mask image et Attention mask + original image.

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/ig_result.png' width= 40% height= 40% align="right">

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/grad.png' width= 40%  height= 40% align="left"> 
