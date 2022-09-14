
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  
  <h3 align="center">Human Activity Recognition</h3>

  <p align="center">
    Taking a look from different perspective
    
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#requirements">Requirements</a></li>
      </ul>
    </li>
    <li><a href="#project">Project</a></li>
        <ul>
            <li><a href="#window-features">Window features</a></li>
            <li><a href="#creating-average-signal-for-each-class-with-use-of-ann">Creating average signal for each class with use of ANN</a></li>
        </ul>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

I spent few years looking at "mechanical" signals. 
While working in Data Science field I thought showing some things from my previous area might be useful for others.
Here we have Human Activity Recognition dataset. 
So recordings from few sensors while performing given activity.
My aim isn't to provide the best solution, but just show another point of view on some aspects.

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- GETTING STARTED -->
## Getting Started

Except the files contained in this repository a dataset will be needed: [Dataset](https://www.kaggle.com/datasets/malekzadeh/motionsense-dataset?resource=download)

### Requirements

For each jupyter requirements in txt was created






<!-- PROJECT -->
## Project

So far only 2 subproject based on this was done. Below you find description of each one.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Window features

Many people tried fed the ML methods just with just scaled data at each timestamp. 
The others lagged features as new one. However, it leads to hundreds of features.
I would come with different attempt. 
I will take features values from time interval and compute a new features.
It will make constant amount of features independent of length of interval, and significant reduce amount of features.
Hopefully also increase results of methods.

### Creating average signal for each class with use of ANN

I have mentioned some people just took lagged features and fed that into ANN.
This attempt inspired me. 
Since taking a look at math standing behind while making some other limitations to model may result ANN is capable of delivering "average" signal for each activity.



<!-- CONTACT -->
## Contact

Jakub Mrowka -  jakmrowka@gmail.com

Project Link: [https://https://github.com/jakmrowka/Simple-Human-Activity-Recognition](https://https://github.com/jakmrowka/Simple-Human-Activity-Recognition)

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/jakub-mrowka/

