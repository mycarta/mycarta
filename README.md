## Ciao! 👋 I'm Matteo (he/him)

### I am a passionate, data-driven geoscientist

- 🐍 I’m currently learning: Dashboarding with [Panel](https://panel.holoviz.org/getting_started/) and [Holoviews](http://holoviews.org/user_guide/Dashboards.html) 
- 📗 I’m currently reading: [How to Lead in Data Science](https://www.manning.com/books/how-to-lead-in-data-science)
- 📗 Past favourite: [Grokking Algorithms](https://www.manning.com/books/grokking-algorithms)
- 🎥 I'm currently watching: [Calling Bullshit in the Age of Big Data](https://youtube.com/playlist?list=PLPnZfvKID1Sje5jWxt-4CSZD7bUI4gSPS)
- ✏️ Hobby: drawing, juggling
- 🃏 Fun fact: a recent fixation with card tricks and Rubik's cube
- 📫 How to reach me: matteo@mycarta.ca

## GitHub Stats
[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=mycarta&theme=blue-green&show_icons=true&custom_title= )](https://github.com/anuraghazra/github-readme-stats&count_private=true)

## Published articles (in Geophysical literature)
- [Introduction to Classification with SVMs](https://csegrecorder.com/assets/pdfs/2018/2018-01-RECORDER-Machine_Learning_in_Geoscience_V.pdf). Article (with [Jupyter notebooks](https://github.com/CSEG/Machine-Learning-CSEG-special-issue/tree/master/Matteo_Niccoli)) offering an intuitive understanding of SVMs using toy datasets inspired by classification problems in geophysics.
- [Mapping and validating lineaments](https://library.seg.org/doi/10.1190/tle34080948.1). Article (with [Jupyter notebook](https://github.com/seg/tutorials-2015/blob/master/1508_Mapping_and_validating_lineaments/1508_Mapping_and_validating_lineaments.ipynb)) demonstrating how to extract and enhance geologic lineaments from gravity data, and colocate them into a single map to increase confidence.

## Featured blog posts
- [Be a geoscience and data science detective](https://mycarta.wordpress.com/2020/09/16/be-a-geoscience-and-data-science-detective/)
- [From zero to JupyterLab pro on Windows 10](https://mycarta.wordpress.com/2019/07/09/from-zero-to-jupyterlab-pro-on-windows-10/)
- [Visual data exploration in Python – correlation, confidence, spuriousness](https://mycarta.wordpress.com/2019/03/17/visual-data-exploration-in-python-correlation-confidence-spuriousness/)

## Portfolio highlight
 [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
 
- **Contribution**: [Rainbow](https://github.com/mycarta/rainbow) - a tool to recover data from scientific images with unknown colourmaps, a project by [Matt Hall](https://github.com/kwinkunks/) - read more about it in [Matt's blog post](https://agilescientific.com/blog/2017/5/31/unweaving-the-rainbow)

- **Knowledge sharing**: [My answer](https://earthscience.stackexchange.com/a/15139/144) to the question _In the northern hemisphere only, what percentage of the surface is land?_ on [Stack Exchange Earth Science Beta](https://earthscience.stackexchange.com). This was a lot of fun combining domain knowledge (about map projections) with a tiny bit of Python programming (using `numpy` arrays) to provide a quantitative solution. Ant it was probably one of the most fun mini-projects I did in 2018.

- **App**: [Busting bad colormaps](https://mybinder.org/v2/gh/mycarta/Colormap-distorsions-Panel-app/master?urlpath=%2Fpanel%2FDemonstrate_colormap_distortions_interactive_Panel) - a web-based `Panel` app to show the effects of using a bad colormap with Geophysical data.  The first version was presented as a lightning talk at the [Transform 2020 virtual conference](https://transform2020.sched.com/) organized by [Software Underground](https://softwareunderground.org/); you can watch a [video recording of the presentation here](https://www.youtube.com/watch?v=rUbvueIF5f8&t=510s). Repo with code [here](https://github.com/mycarta/Colormap-distorsions-Panel-app).
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

- **My first package(work in progress)**: [cmaptools](https://pypi.org/project/cmaptools/), _a collection of functions to analyze and fix bad colormaps_. This is my project for the tutorialthe [Publishing your first Python package](https://transform.softwareunderground.org/2022-first-python-package/overview), attended at the Software Underground [Transform 2022 virtual conference](https://transform.softwareunderground.org/overview). Github [repo here](https://github.com/mycarta/cmaptools).

## 3D visualizations
- 3D model of the Yoder Tilley tetrahedron for basalt classification. In this visualization the tetrahedron isbroken to separate the Quartz Tholeiite, Oliving Tholeiite, and Alkali Basalt sub-volumes and show the critical planes of silica saturation and silica under-saturation. For the 3D sketchfab version of the model, I used a DXF export and re-rendered using Rhino3D. Check it out [on Sketchfab](https://sketchfab.com/3d-models/basalt-classification-yoder-tilley-tetrahedron-4d5b741603424850af8946c7316d059a)
- There's also a 3D model of the ternary system quartz – nepheline – kalsilite, also called petrogeny’s “residua” system, is used to describe the composition of many cooled residual magma. This was an advanced pet project while I was a student in Geology at the University of Rome, Italy. It involved using AutoCAD and 3D Studio Max to create a WRLM file. For the 3D sketchfab version of the model, I used a DXF export and re-rendered using Rhino3D. Check it out on [Sketchfab](https://sketchfab.com/3d-models/ternary-system-quartz-nepheline-kalsilite-c8225185f7004ad0a23533ca191b0c6b)
<p align="center">
<img width="650" alt="Screen Shot 2022-05-26 at 9 57 02 PM" src="https://user-images.githubusercontent.com/7424763/170626329-7ecdac24-c612-4fd1-921c-8b4ba6788534.png">
</p>

<div class="sketchfab-embed-wrapper"> <iframe title="Ternary system quartz - nepheline - kalsilite" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/c8225185f7004ad0a23533ca191b0c6b/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/ternary-system-quartz-nepheline-kalsilite-c8225185f7004ad0a23533ca191b0c6b?utm_medium=embed&utm_campaign=share-popup&utm_content=c8225185f7004ad0a23533ca191b0c6b" target="_blank" style="font-weight: bold; color: #1CAAD9;"> Ternary system quartz - nepheline - kalsilite </a> by <a href="https://sketchfab.com/mycarta?utm_medium=embed&utm_campaign=share-popup&utm_content=c8225185f7004ad0a23533ca191b0c6b" target="_blank" style="font-weight: bold; color: #1CAAD9;"> MyCarta </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=c8225185f7004ad0a23533ca191b0c6b" target="_blank" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p></div>


## Hackathons and sprints
- [2015 Calgary Hackathon](https://agilescientific.com/blog/2015/5/15/canadian-codeshow). The hackathon was organized by [Agile Scientific](https://github.com/agile-geoscience). With teammates [Evan Saltman](https://github.com/epsalt) and [Elwyn Galloway](https://github.com/scibbatical), and special guest [Ben Bougher](https://github.com/ben-bougher) from Agile, built `Sketch2model`, an app to turn back-of-the-napkin geological sketches into synthetic seismic sections. You can read about it in [Elwyn's blog post](https://scibbatical.wordpress.com/2016/05/02/sketch2model/) and [this one of mine](https://mycarta.wordpress.com/2016/07/22/sketch2model-linking-edges-with-mathematical-morphology/)
- [2018 Santa Ana SEG Geophysics Sprint](https://agilescientific.com/blog/2018/10/18/cafe-con-leche). The sprint was organized by [Agile Scientific](https://github.com/agile-geoscience) ahead of the Annual SEG Geophysics Conference. With [Volo Vragov](https://github.com/vragov), worked on some [Geophysical inversion optimization code](https://mycarta.wordpress.com/2018/10/28/geophysics-python-sprint-2018-day-2-and-beyond-part-i/) for the [Bruges Python library](https://github.com/agile-geoscience/bruges)
- [2020 Hackathon, Transform virtual conference](https://softwareunderground.org/blog/2020/6/18/transform-2020). The hackathon was organized by the Software Underground group. With teammates [Matt Hall](https://github.com/kwinkunks) and [Dan Austin](https://github.com/esadan), and a few other contributors, edited several chapters of the upcoming book [52 Things You Should Know About Geocomputing](https://mycarta.wordpress.com/2020/01/30/about-52-things-you-should-know-about-geocomputing/). You can watch a video recording of the final presentation [here on the group's YouTube channel](https://youtu.be/VRoSIjqDj-g?t=277) 
- [2021 Hackathon, Transform virtual conference](https://github.com/softwareunderground/transform-2021-hackathon/discussions). Project details coming soon...
- [2021 Geothermal Hackathon, Agile Scientific](https://events.agilescientific.com/event/geothermal-2021/ideas). Project details coming soon...

## Some EDA visulization favourites
- Enhanced `seaborn` pairgrid matrix: one of the things I always do when I start looking at a multivariate probelm is to explore possible associations between features and target; one way I've found really useful is to "enhance"  the standard `Seaborn` pairgrid matrix by labeling each bivariate scatter plot with the distance correlation colored by p-value, and also rearrage the plots by the results of clustering analysis, like in the example below (you can read more about it [here](https://mycarta.wordpress.com/2019/04/10/data-exploration-in-python-distance-correlation-and-variable-clustering/)): 
<p align="center">
  <img width="500" src="https://mycarta.files.wordpress.com/2019/04/matrix_sorted_predictors.png">
</p>

- At the [2020 FORCE Machine Predicted Lithology challenge](https://xeek.ai/challenges/force-well-logs/overview), I used Ipywidget's interactive and the awesome [`missingno`](https://github.com/ResidentMario/missingno) library to enable browsing exploration wells in the North Sea using a widget and check the chosen well's curves completeness, on the fly, as shown below (you can read more about it [in here](https://mycarta.wordpress.com/2020/09/19/geoscience-machine-learning-bits-and-bobs-data-completeness), and try the tool in [this Jupyter notebook](https://github.com/mycarta/Force-2020-Machine-Learning-competition_predict-lithology-EDA/blob/master/Interactive_data_inspection_and_visualization_by_well.ipynb)):
<p align="center">
  <img width="500" src="https://mycarta.files.wordpress.com/2020/09/missingno_completeness_animation-1.gif">
</p>

## My personal Data Science roadmap (~40% courses completed)

### Python development, unit testing, and debugging
- [x] Introduction to Visual Studio Code, Real Python
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
- [x] Intermediate Machine Learning, Kaggle
- [ ] Web Scraping With Beautiful Soup and Python, Real Python
- [ ] Time Series, Kaggle
- [ ] Intro to SQL, Kaggle
- [ ] Advanced SQL, Kaggle
- [ ] SQL for Data Analysis, Coursera

### GIS and Geospatial
- [x] Geospatial Analysis, Kaggle
- [x] [Climate Geospatial Analysis in Python with Xarray](https://www.coursera.org/account/accomplishments/certificate/VMKXGAQKGGFP),  Coursera Project Network
- [ ] ARSET - Fundamentals of Remote Sensing, NASA Applied Science
- [ ] ARSET - Introduction to Synthetic Aperture Radar, NASA Applied Science
- [ ] ARSET - Humanitarian Applications Using NASA Earth Observations, NASA Applied Science

### AI, Deep Learning, Ethics, ML explainability
- [x] [AI for Everyone](https://www.coursera.org/account/accomplishments/certificate/W9V3WB6GADC4), Coursera
- [x] [Machine learning explainability](https://www.kaggle.com/learn/certification/mycarta/machine-learning-explainability), Kaggle
- [ ] Intro to AI Ethics, Kaggle
- [x] Intro to Deep Learning, Kaggle
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

## Upcoming articles and tutorials
##### For 52 Things You Should Know About Geocomputing: A crowdsourced collection of articles from practitioners, reviewed and edited by the Software Underground community:
- [Some advice on reproducing scientific figures](https://curvenote.com/@swung/52-things-geocomputing/niccoli-advice-on-reproducing-figures)
- [Keep on improving your Geocomputing projects](https://curvenote.com/@swung/52-things-geocomputing/niccoli-keep-on-improving-geocomputing-projects)
- [Prototype colourmaps for fault interpretation](https://curvenote.com/@swung/52-things-geocomputing/niccoli-prototype-colormaps-for-faults)

## Stuff I would do differently
- These days I would definitely build this one in Python: [A study of Ricker wavelets in MS Excel (2016)](https://mycarta.wordpress.com/2016/02/04/a-study-of-ricker-wavelets-in-ms-excel/)
