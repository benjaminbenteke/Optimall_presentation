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

## Results
The original image is:

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/70bfca4555cca92e.jpg' width= 50%>

The interpolated images are:

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/interpolated_images.png' width= 50% height= 70%>

<b> Experimentation results: </b> The left and right figures represent </b> gradient method </b> result and <b> Integrated Gradient method </b> results respectively. As you can see, <b> Integrated Gradient method </b> works better than <b> Gradient method </b>, because it the Integrated Gradient image seems the original image. See the Attention mask image et Attention mask + original image.

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/ig_result.png' width= 40% height= 40% align="right">

<img src='https://github.com/benjaminbenteke/Axiomatic-Attribution-for-DeepNetwork/blob/main/grad.png' width= 40%  height= 40% align="left"> 

<br>
  
# Contributors #
<div style="display:flex;align-items:center">

<div style="display:flex;align-items:center">
    <div>
        <h5> <a href='https://github.com/benjaminbenteke'> Benjamn Benteke Longau </a> </h5> <img src="https://raw.githubusercontent.com/benjaminbenteke/Deep_RL_Project/master/images/bennn.jpg" height= 7% width= 7%>
<div>
    <h5> <a href='https://github.com/Maramy93'> Maram A. Abdelrahman Mohamed </a> </h5> <img src="images/maram.jpeg" height= 7% width= 7%>
    
<div>
    <h5> <a href='https://github.com/Mikhael-P'> Mikhaël P. Kibinda-Moukengue </a> </h5> <img src="images/mikhael_2.jpeg" height= 7% width= 7%>
    
</div>

<div>
    <h5> <a href='https://github.com/ARNAUD-25'> Arnaud Watusadisi Mavakala </a> </h5> <img src="images/arnaud.jpeg" height= 7% width= 7%>
    
</div>

<div>
    <h5> <a href='https://github.com/Jeannette-del'> Jeanette Nyirahakizimana</a> </h5><img src="images/jeanette.jpeg" height= 10% width= 10%> 
</div>
</div>
