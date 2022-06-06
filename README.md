## Ciao! 👋 I'm Matteo (he/him) 🏳️‍🌈 🏳️‍🌈 🏳️‍🌈

### I am a passionate, actively curious, data-driven geoscientist

- 🐍 I’m currently learning: Dashboarding with [Panel](https://blog.holoviz.org/panel_0.13.0.html) and [Holoviews](http://holoviews.org/user_guide/Dashboards.html) 
- 📗 I’m currently reading: [How to Lead in Data Science](https://www.manning.com/books/how-to-lead-in-data-science)
- 📗 Past favourite: [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)
- 🎥 I'm currently watching: [Calling Bullshit in the Age of Big Data](https://youtube.com/playlist?list=PLPnZfvKID1Sje5jWxt-4CSZD7bUI4gSPS)
- ✏️ Hobby: drawing, juggling
- 🃏 Fun fact: a recent fixation with card tricks and Rubik's cube
- 📝 Blog: [mycarta](https://mycarta.wordpress.com/)
- 📫 How to reach me: matteo@mycarta.ca
- 🐦 On Twitter I am [@my_carta](https://twitter.com/My_Carta)
-----
# Table of Contents
1. [GitHub and Stack Overflow Stats](#GitHub-and-Stack-Overflow-Stats)
2. [Featured blog posts](#Featured-blog-posts)
3. [Articles published in Geophysical literature](#Articles-published-in-Geophysical-literature)
4. [Upcoming articles and tutorials](#Upcoming-articles-and-tutorials)
6. [Projects portfolio](#Projects-portfolio)
7. [Exploratory Data Analysis and visualization portfolio](#Exploratory-Data-Analysis-and-visualization-portfolio)
8. [Coding challenges](#Coding-challenges)
9. [My Data Science continuous learning roadmap](#My-Data-Science-continuous-learning-roadmap)
10. [Book library](#Book-library)
11. [Community engagement](#Community-engagement)
12. [Stuff I would do differently](#Stuff-I-would-do-differently)

-----
## GitHub and Stack Overflow Stats
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=mycarta&theme=blue-green&show_icons=true&custom_title= )](https://github.com/anuraghazra/github-readme-stats&count_private=true)

<a href="https://stackexchange.com/users/1025180"><img src="https://stackexchange.com/users/flair/1025180.png?theme=dark" width="250" height="60" alt="profile for MyCarta on Stack Exchange, a network of free, community-driven Q&amp;A sites" title="profile for MyCarta on Stack Exchange, a network of free, community-driven Q&amp;A sites">
</a>

-----
## Featured blog posts
- [Be a geoscience and data science detective](https://mycarta.wordpress.com/2020/09/16/be-a-geoscience-and-data-science-detective/)
- [From zero to JupyterLab pro on Windows 10](https://mycarta.wordpress.com/2019/07/09/from-zero-to-jupyterlab-pro-on-windows-10/)
- [Visual data exploration in Python – correlation, confidence, spuriousness](https://mycarta.wordpress.com/2019/03/17/visual-data-exploration-in-python-correlation-confidence-spuriousness/)

-----
## Articles published in Geophysical literature
- [Introduction to Classification with SVMs](https://csegrecorder.com/assets/pdfs/2018/2018-01-RECORDER-Machine_Learning_in_Geoscience_V.pdf). Article (with [Jupyter notebooks](https://github.com/CSEG/Machine-Learning-CSEG-special-issue/tree/master/Matteo_Niccoli)) offering an intuitive understanding of SVMs using toy datasets inspired by classification problems in geophysics.
- [Mapping and validating lineaments](https://library.seg.org/doi/10.1190/tle34080948.1). Article (with [Jupyter notebook](https://github.com/seg/tutorials-2015/blob/master/1508_Mapping_and_validating_lineamenti/1508_Mapping_and_validating_lineaments.ipynb)) demonstrating how to extract and enhance geologic lineaments from gravity data, and colocate them into a single map to increase confidence.

-----
## Upcoming articles and tutorials
##### For 52 Things You Should Know About Geocomputing: A crowdsourced collection of articles from practitioners, reviewed and edited by the Software Underground community:
- [Some advice on reproducing scientific figures](https://curvenote.com/@swung/52-things-geocomputing/niccoli-advice-on-reproducing-figures)
- [Keep on improving your Geocomputing projects](https://curvenote.com/@swung/52-things-geocomputing/niccoli-keep-on-improving-geocomputing-projects)
- [Prototype colourmaps for fault interpretation](https://curvenote.com/@swung/52-things-geocomputing/niccoli-prototype-colormaps-for-faults)

-----
## Projects portfolio

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

- **Web app**: [Busting bad colormaps](https://mybinder.org/v2/gh/mycarta/Colormap-distorsions-Panel-app/master?urlpath=%2Fpanel%2FDemonstrate_colormap_distortions_interactive_Panel)  - a web-based `Panel` app to show the effects of using a bad colormap with Geophysical data.  The first version was presented as a lightning talk at the [Transform 2020 virtual conference](https://transform2020.sched.com/) organized by [Software Underground](https://softwareunderground.org/); you can watch a [video recording of the presentation here](https://www.youtube.com/watch?v=rUbvueIF5f8&t=510s). Repo with code [here](https://github.com/mycarta/Colormap-distorsions-Panel-app). 
<p align="center">
  <img width="650" src="https://github.com/mycarta/Colormap-distorsions-Panel-app/blob/master/for%20readme/new_gif.gif">
</p>

- **Tutorial**: [Working with 3D seismic data in Python using segyio, numpy, Scikit-image](https://github.com/equinor/segyio-notebooks/blob/master/notebooks/basic/01_basic_tutorial.ipynb). A notebook to demonstrate how to:
    - read a seismic amplitude volume and a seismic similarity volume as `numpy` arrays using `segyio`
    - manipulate the similarity to create a discontinuity / fault volume
    - create a fault mask and display a couple of amplitude time slices with superimposed faults
    - write the fault volume to SEG-Y file re-using the headers from the input file
<p align="center">
  <img width="650" src="https://mycarta.files.wordpress.com/2019/03/workflow.png">
</p>

- **Image augmentation pipelines for Deep Learning**. 
I've worked on two image augmentation pipelines to increase the size of training sets for classification of geologic edges in seismic data, a typically low bias / high variance problem. 
   - I developed the first pipeline to increase the size of training sets for classification of geologic edges in seismic data. The work was commissioned by a company (as a free-lance) and I am not able to share any detail on the image manipulations used. I have permission, however, to disclose that in production tests with Convolutional Neural Networks the approach helped improve performance, and that these efforts paved the path for the company's subsequent coding and investigations.
   - I developed the second pipeline working with the images from the [2018 TGS Salt Identification Challenge on Kaggle](https://www.kaggle.com/c/tgs-salt-identification-challenge/data) in mind. Although I did not participate in the competition, having considere at length the problem of segmenting salt deposits, I came up with the idea of an "adversarial" augmentation strategy, in which not only the size of the training set is increased, but the task is rendered much harder with the image transformation. Some examples are shown below.  Preliminar tests (unpublished) are encouraging and I am currently working at open-sourcing my functions by way of a PR to the [Augmentor package](https://augmentor.readthedocs.io/en/master/index.html), so that where operations can be added not only in a sequence, but also stochastically with a probability value assigned by the user for each operation.
<p align="center">
  <img width="750" src="https://user-images.githubusercontent.com/7424763/172077533-ed00056c-0100-45a8-88ab-404ced0dc9ad.png">
</p>
 
- **Web app (Hackathon project)**: [Sketch2model](https://github.com/epsalt/sketch2model-web) - a browser-based app to turn back-of-the-napkin geological sketches into geologic models that can then be used to generate synthetic seismic sections
- : ![flow](https://raw.githubusercontent.com/mycarta/sketch2model/master/workflow.PNG) The web app was Built around a prototype put together at the [2015 Calgary Geoscience Hackathon](https://csegrecorder.com/articles/view/open-collaboration-hackathons-and-tomorrows-subsurface-software), organized by [Agile Scientific](https://github.com/agile-geoscience), with teammates [Evan Saltman](https://github.com/epsalt) and [Elwyn Galloway](https://github.com/scibbatical), and special guest [Ben Bougher](https://github.com/ben-bougher) from Agile. The original idea for the prototype was proposed by Elwyn at the Hackathon, was to make an app that would turn an image of geological sketch into a model. The implementation of the finished app involves using morphological filtering and other image processing methods to enhance the sketch and convert it into a model with discrete bodies to be passed to a tool akin to Agile's [modelr.io](https://www.modelr.io/) to create a synthetic.

Blog posts:
  - [sketch2model](https://mycarta.wordpress.com/2016/05/04/sketch2model)
  - [sketch2model – sketch image enhancements](https://mycarta.wordpress.com/2016/05/25/sketch2model-sketch-image-enhancements)
  - [sketch2model – linking edges with mathematical morphology](https://mycarta.wordpress.com/2016/07/22/sketch2model-linking-edges-with-mathematical-morphology)

App screenshot:

<img width="1932" alt="Screen Shot 2022-06-05 at 5 34 38 PM" src="https://user-images.githubusercontent.com/7424763/172092024-5dfe687a-b339-4a2f-9932-c2b1656d7fcb.png">

- **Web app (Hackathon project)** :FRIDA (_add link to live app here_) - a browser-based app for interactive removal of acquisition footprint noise removal from #D seismic data. Built at the [2021 Hackathon, Transform virtual conference](https://github.com/softwareunderground/transform-2021-hackathon/discussions). **>>> Description, gif animation, screen captures and workflow to go here**

- **Collaboration project**: [Rainbow][https://github.com/mycarta/rainbow](https://agilescientific.com/blog/2017/5/31/unweaving-the-rainbow). For this project with [Matt Hall](https://github.com/kwinkunks/), I created a pipeline of image processing routines to enhance, clean-up, segment, and rectify the main map from published figures. This was a necessary preprocessing stage for Rainbow, an online tool for automagic recovery data from scientific images with unknown colourmaps. An example of the image processing work is shown is sketched below, with full list of operations in the intro to my blog series [Computer vision in Geoscience](https://mycarta.wordpress.com/2017/07/30/computer-vision-in-geoscience-recover-seismic-data-from-images-introduction/), and detailed methodology described in [Part I](https://mycarta.wordpress.com/2017/09/10/computer-vision-in-geoscience-recover-seismic-data-from-images-part-1/) and [Part II](https://mycarta.wordpress.com/2017/09/18/computer-vision-in-geoscience-recover-seismic-data-from-images-part-2/).
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/7424763/172074830-f9cf1ed1-b899-4823-8574-d4ac0252f43b.png">
</p>

Also, watch Matt’s talk (very insightful and very entertaining) from the 2017 Calgary Geoconvention below:
<p align="center">
  <a href="https://youtu.be/7DnudEsb6hU " target="_blank"><img src="https://user-images.githubusercontent.com/7424763/172075215-75d9b1fb-0202-4f0c-b170-4f12a66cf890.png" alt="Recovering data from seismic images" width="650" /></a>
</p>

- **Knowledge sharing**: [My answer](https://earthscience.stackexchange.com/a/15139/144) to the question **In the northern hemisphere only, what percentage of the surface is land?**  on [Stack Exchange Earth Science Beta](https://earthscience.stackexchange.com). This was a lot of fun combining domain knowledge (about map projections) with a tiny bit of Python programming (using `numpy` arrays) to provide a quantitative solution. It is the mini-project I am proud the most of, and I did it out of curiosity and the pure joy of solving a problem!

-----
## Exploratory Data Analysis and visualization portfolio
- Enhanced `seaborn` pairgrid matrix: one of the things I always do when I start looking at a multivariate probelm is to explore possible associations between features and target; one way I've found really useful is to "enhance"  the standard `Seaborn` pairgrid matrix by labeling each bivariate scatter plot with the [distance correlation](https://en.wikipedia.org/wiki/Distance_correlation) colored by p-value, and also rearrage the plots by the results of clustering analysis, like in the example below (you can read more about it [here](https://mycarta.wordpress.com/2019/04/10/data-exploration-in-python-distance-correlation-and-variable-clustering/)): 
<p align="center">
  <img width="500" src="https://mycarta.files.wordpress.com/2019/04/matrix_sorted-2.png">
</p>

- At the [2020 FORCE Machine Predicted Lithology challenge](https://xeek.ai/challenges/force-well-logs/overview), I used Ipywidget's interactive and the awesome [`missingno`](https://github.com/ResidentMario/missingno) library to enable browsing exploration wells in the North Sea using a widget and check the chosen well's curves completeness, on the fly, as shown below (you can read more about it [in here](https://mycarta.wordpress.com/2020/09/19/geoscience-machine-learning-bits-and-bobs-data-completeness), and try the tool in [this Jupyter notebook](https://github.com/mycarta/Force-2020-Machine-Learning-competition_predict-lithology-EDA/blob/master/Interactive_data_inspection_and_visualization_by_well.ipynb)):
<p align="center">
  <img width="500" src="https://mycarta.files.wordpress.com/2020/09/missingno_completeness_animation-1.gif">
</p>

- 3D model of the ternary system quartz – nepheline – kalsilite, also called petrogeny’s “residua” system, which is used to describe the composition of many cooled residual magma. This was an advanced pet project while I was a student in Geology at the University of Rome, Italy. It involved using AutoCAD and 3D Studio Max to create a WRLM file. For the 3D sketchfab version of the model, I used a DXF export and re-rendered using Rhino3D. See the static snapshot below; navigate, inspet, and download the model on [Sketchfab](https://sketchfab.com/3d-models/ternary-system-quartz-nepheline-kalsilite-c8225185f7004ad0a23533ca191b0c6b)
<p align="center">
<img width="650"  src="https://user-images.githubusercontent.com/7424763/171786565-3452ddf5-a05b-4279-8cec-26c09a394415.gif">
</p>


- 3D model of the Yoder Tilley tetrahedron for basalt classification. In this visualization the tetrahedron isbroken to separate the Quartz Tholeiite, Oliving Tholeiite, and Alkali Basalt sub-volumes and show the critical planes of silica saturation and silica under-saturation. For the 3D sketchfab version of the model, I used a DXF export and re-rendered using Rhino3D. Check it out [on Sketchfab](https://sketchfab.com/3d-models/basalt-classification-yoder-tilley-tetrahedron-4d5b741603424850af8946c7316d059a)
<p align="center">
<img width="650" src="https://user-images.githubusercontent.com/7424763/171785612-052ccf71-62c7-42ad-87e5-26a6de6e7b3c.gif">
</p>

- 3D paths of colormap in CIELAB color space. These are a very useful way to analyze a colormap as they show clearly where abrupt chages in contrast happen; these are responsible for artifacts in mapping when these colormaps are used (more details in [this blog post](https://mycarta.wordpress.com/2013/02/21/perceptual-rainbow-palette-the-method/) ). As example in the two animations below (produced using the [3D color inspector plugin](https://imagej.nih.gov/ij/plugins/color-inspector.html) for ImageJ), notice the may abrupt changes in the path for the classic Jet colormap (top) and compary to the regular piraling path of a more perceptual rainbow, called CubicYF (bottom), which I created:
<p align="center">
<img width="400" src="https://user-images.githubusercontent.com/7424763/170847059-1afa96d0-7231-4005-98d1-14e5cbe90061.gif">
</p>

<p align="center">
<img width="400" src="https://user-images.githubusercontent.com/7424763/170847071-92754fca-ac6a-40c0-be7a-40f88a2172c1.gif">
</p>

-----
## Coding challenges
- Completed all the Python challenges at [Coding bat](https://codingbat.com/python) and earned an overall 10-Star badge.

<p align="center">
<img width="520" src="https://user-images.githubusercontent.com/7424763/171553242-81d3a943-a86f-4e92-9cbe-702195cce783.png">
</p>

-----
## My Data Science continuous learning roadmap
📕
<details>
  <summary>Click here to expand the roadmap section</summary> 

### Python development, unit testing, and debugging
- [ ] Introduction to Visual Studio Code, Real Python
- [x] [Test-Driven Development With PyTest](https://realpython.com/certificates/96ecff0f-2d92-422f-b3d8-f6790a03f872/), Real Python
- [ ] Raising and Handling Python Exceptions, Real Python
- [x] [Enhance your Python unit testing using Coverage](https://www.coursera.org/account/accomplishments/certificate/TGYBNFKE3DJW), Coursera Project Network
- [ ] Software Debugging, Coursera

### Foundations of Data Science [Professional Certificate](https://credentials.edx.org/credentials/3ff1fe712ebe4e6bb47093928883d765/) (edX)
- [x] [Computational Thinking with Python](https://courses.edx.org/certificates/a5d76bfe8eff4a43bfc70c356745b3f6)
- [x] [Inferential Thinking through Simulations](https://courses.edx.org/certificates/5ad5a7c792c04d5a9371b2f7fc97d253)
- [x] [Machine Learning and Predictions](https://courses.edx.org/certificates/02807f521af04f3db11ce95e01e62625)

### Intermediate Data Science
- [x] [Pandas](https://www.kaggle.com/learn/certification/mycarta/pandas), Kaggle
- [x] [15 Mistakes to Avoid in Data Science](https://www.linkedin.com/learning/certificates/80c3a9379c2a96b55083dab7f651cf99ea2b01d52c56ea4684e22befeb06cfdb?trk=share_certificate), LinkedIn Learning
- [ ] Intermediate Machine Learning, Kaggle
- [ ] Refactoring Pandas, Meta Snake
- [ ] Web Scraping With Beautiful Soup and Python, Real Python
- [ ] Time Series, Kaggle
- [ ] Intro to SQL, Kaggle
- [ ] Advanced SQL, Kaggle
- [ ] SQL for Data Analysis, Coursera
 
### Analytics
- [x] [Spotfire Essentials I](https://support.ruths.ai/support/solutions/articles/6000191001-kickstart-how-to-schedule-training), Ruths.ai (now Petro.ai)
- [x] [Spotfire Essentials II](https://support.ruths.ai/support/solutions/articles/6000191001-kickstart-how-to-schedule-training), Ruths.ai (now Petro.ai)
- [ ] Spotfire - The Complete TIBCO Spotfire Course, Udemy

### GIS and Geospatial
- [ ] Geospatial Analysis, Kaggle
- [x] [Climate Geospatial Analysis in Python with Xarray](https://www.coursera.org/account/accomplishments/certificate/VMKXGAQKGGFP),  Coursera Project Network
- [ ] Monitoring Changes in Surface Water Using Satellite Image Data, Manning Live Project
- [ ] Spatial Data Science: The New Frontier in Analytics. Esri Academy
- [ ] ARSET - Fundamentals of Remote Sensing, NASA Applied Science
- [ ] ARSET - Introduction to Synthetic Aperture Radar, NASA Applied Science
- [ ] ARSET - Humanitarian Applications Using NASA Earth Observations, NASA Applied Science
- [ ] End-to-End Machine Learning for Rain Prediction, Manning Live Project

### AI, Deep Learning, Ethics, ML explainability
- [x] [AI for Everyone](https://www.coursera.org/account/accomplishments/certificate/W9V3WB6GADC4), Coursera
- [x] [Machine learning explainability](https://www.kaggle.com/learn/certification/mycarta/machine-learning-explainability), Kaggle
- [ ] Intro to AI Ethics, Kaggle
- [ ] Intro to Deep Learning, Kaggle
- [ ] Computer Vision, Kaggle
- [ ] Practical Deep Learning for Coders, fastai
- [ ] Practical Data Ethics, fastai

### Race, Gender and Workplace Equity [Professional Certificate](https://credentials.edx.org/credentials/da6b5edb91eb43ca808d960407a84601/), edX
- [x] [Understanding Gender Equity](https://courses.edx.org/certificates/a052cc54020b465096d2cf5c1c557877)
- [x] [Facing Racism and Emotional Tax in the Workplace](https://courses.edx.org/certificates/ab3dc247ac9149bfb20ead074daf22ed)
- [x] [Communication Skills for Dialoguing Across Difference](https://courses.edx.org/certificates/e73a19e937274de1b790cf3dcc02fc7a)
- [x] [Unconscious Bias: From Awareness to Action](https://courses.edx.org/certificates/62d405fb03794ae4bdc4d05bf53d757d)

### Communication tools
- [x] [Enhance Organizational Communications with Slack](https://www.coursera.org/account/accomplishments/certificate/JEBLDLJQLSZN), Coursera Project Network
</details>
📕

-----
## Book library
It looks like it has become very trendy these days to post a picture your datascience library. I admit it, I could not resist doing it too! Here is my collection of books, with a focus on computative geoscience and visualization (… and keeping myself honest about what I have not read yet…)
<p align="center">
  <img width="650" src="https://user-images.githubusercontent.com/7424763/170873518-fdae9db3-9b94-4c43-9784-2199331f5373.PNG">
</p>

-----
## Community engagement
- Mentor, Canadian Society of Exploration Geophysicists (volunteer). From 2010 to 2020: mentored in Geophysics - and more recently in both Geophysics and Data Science - 3rd-4th year undergraduate students, and graduate students.
- Co-founder and coordinator of the Calgary GeoPy group, which run semi-regular meetups for 2018 and 2019.
- Editor, Canadian Society of Exploration Geophysicists (volunteer). From 2014 to 2016 Editor for the society's journal Recorder; notable project: conceived and coordinated a special topic edition on Programming in Geoscience.

-----
## Stuff I would do differently
- These days I would definitely build this one in Python: [A study of Ricker wavelets in MS Excel (2016)](https://mycarta.wordpress.com/2016/02/04/a-study-of-ricker-wavelets-in-ms-excel/)
