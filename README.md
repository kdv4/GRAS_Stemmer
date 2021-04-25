## GRAS Stemmer 
GRAS stemmer is stastical stemmer to stem language. We implemented GRAS stemmer for the Gujarati language. Also computed MAP score for the different approaches. We also attach report which consist of our analytical results and basic algorithm for the GRAS stemmer. 

This codebase contains 3 files namely under code directory, 
1.  Pre-processing.ipynb

        In this file, we perform some pre-processing and output unique tokens. 

2.  GRAS.ipynb

        In this file, there's implementation of GRAS stemmer and we experiment with different values of alpha and delta to get different root word dir. 

3.  Stemming and Retrieval.ipynb
    
        In this file, we perform retrieval task and compare its MAP value with non-stemmed corpus. 


### Dataset used:
Dataset download link: http://fire.irsi.res.in/fire/static/data , We used FIRE 2011 Gujarati corpus.

### How to run?
Change basic path accordingly.


        - Step1: Pre-processing.ipynb
        - Step2: GRAS.ipynb        
        - Step3: Stemming adn Retrieval.ipynb

### Result:
MAP score
<table style="width:100%">
  <tr>
    <th>L</th>
    <th>Alpha</th>
    <th>Delta</th>
    <th> MAP </th>
  </tr>
    <tr>
    <td colspan="3">No Stemming</td>
    <td>0.30810024908953476</td>
  </tr>
  <tr>
    <td>6</td>
    <td>4</td>
    <td>0.5</td>
    <td>0.35627292511280606</td>
  </tr>
   <tr>
    <td>6</td>
    <td>4</td>
    <td>0.9</td>
    <td>0.348505248917749</td>
  </tr>
  <tr>
    <td>6</td>
    <td>6</td>
    <td>0.5</td>
    <td>0.3465313157081014</td>
  </tr>
  <tr>
    <td>7</td>
    <td>4</td>
    <td>0.5</td>
    <td>0.32438315982958843</td>
  </tr>
  <tr>
    <td>7</td>
    <td>4</td>
    <td>0.8</td>
    <td>0.3331921957671958</td>
  </tr>

</table>
                

## @author:<br>
Kishan Vaishnani<br>
Dhyanil Mehta<br>
Darshil Patel<br>
Tarang Ranpara<br>
Sonal Nathwani<br>

