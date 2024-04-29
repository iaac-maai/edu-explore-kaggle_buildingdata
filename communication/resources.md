# Resources

## General

* [MeanShift](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.MeanShift.html)
* [PCA](https://statisticsbyjim.com/basics/principal-component-analysis/)
* [Dimensionality reduction by Joscha](https://drive.google.com/file/d/1NHy9EsTUuyA1bf7tb6mDJRPlpqIE9tKf/view)
* [UMap](https://umap-learn.readthedocs.io/en/latest/)
* [CNN](https://poloclub.github.io/cnn-explainer/#article-flatten)
* [Keras](https://www.kaggle.com/code/prashant111/comprehensive-guide-to-ann-with-keras)
* [Keras Datacamp](https://app.datacamp.com/learn/courses/introduction-to-deep-learning-with-keras)
* [Visualization](https://playground.tensorflow.org/)
* [Visualiztion](https://artsexperiments.withgoogle.com/tsnemap/)
* [Gradio](https://www.gradio.app/guides/controlling-layout)

## Technical issues

* [Prevent Colab from disconnecting](https://stackoverflow.com/questions/57113226/how-can-i-prevent-google-colab-from-disconnecting)


## Geodata

:dna: Some resources on working with geodata:
* [Geopandas](https://geopandas.org/en/stable/getting_started/introduction.html) - just like pandas library, but shows you geofeatures like polygons and lines along with their attributes. Uses the same functions as pandas, so easy to start with:) instead of a .csv file you read in a .shp file (the one you use in QGIS or ArcGIS)
* [Shapely](https://shapely.readthedocs.io/en/stable/geometry.html) - library for geometric operations. All the operations you do in QGIS you can do with shapely, only faster and easier, with a few lines of code. Like, polygon intersection, offset, checking whether a point lies within a polygon etc
* [Geopandas course](https://app.datacamp.com/learn/courses/working-with-geospatial-data-in-python) on datacamp
* [Extracting geodata from OpenStreetMap](https://wiki.openstreetmap.org/wiki/OSMPythonTools)
* More advanced [course](https://autogis-site.readthedocs.io/en/latest/index.html) on spatial data analysis
* Historical satellite images:
* [Planet Labs](https://www.planet.com/markets/education-and-research/#apply-now) gives free access to their data to students, limited by 5000 sq km
* [Google Earth Engine](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api) has a python API - here is a [colab notebook](https://colab.research.google.com/github/google/earthengine-community/blob/master/guides/linked/ee-api-colab-setup.ipynb#scrollTo=8I_Fr0L5AFmu) on how to use it

## Segmentation

:dna: For the segmentation:

* [Segment Anything](https://github.com/facebookresearch/segment-anything) + [colab notebook](https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/how-to-segment-anything-with-sam.ipynb) + [demo](https://segment-anything.com/demo)
* Alternatively you can use [ArcGIS models](https://dzone.com/articles/six-pre-trained-deep-learning-models-to-digitize-a) for it, but for that you need ArcGIS..
* [Road extraction](https://www.kaggle.com/code/balraj98/road-extraction-from-satellite-images-deeplabv3/notebook)
* [Roboflow](https://universe.roboflow.com/) and [notebooks](https://github.com/roboflow/notebooks)
* [postprocessing](https://scikit-image.org/docs/stable/auto_examples/edges/index.html)
* [postprocessing](https://scikit-image.org/docs/stable/auto_examples/edges/plot_skeleton.html)
* [masks](https://pyimagesearch.com/2021/01/19/image-masking-with-opencv/)



## Reinforcement Learning

Some resources on Reinforcement Learning :
* [OpenAI gym](https://gymnasium.farama.org/content/basic_usage/#) - an alternative to Unity,
    * pros: easier to get started with, the code is written in python, easy to install
    * cons: more difficult to customize
    OpenAIGym could be a good starting point, let's say training an agent in a 2D environment first. Remember, we were talking about starting small? :slightly_smiling_face:  if you manage to do it well, it will be a great project; if you manage to do it before April, we can work on a more complex version in 3D environment
* Looks like HuggingFace has some RL models, like [this one](https://huggingface.co/docs/simulate/howto/rl):
    * pros: written in python, has all the basic elements, looks easy to use, has examples
    * cons: not a big community around, simpler viewport compared to unity or blender or unreal
* [Unity ML agents](https://unity.com/products/machine-learning-agents) and their [toolkit](https://github.com/Unity-Technologies/ml-agents)
    * pros: fully customizable, a lot of features, cool visualization if you work on it
    * cons: the code is written in C#, more difficult to get started, messy installation
* apparently there are people developing DeepRL plugins for [Unreal Engine](https://docs.isaratech.com/ue4-plugins/drl-unreal):
    * pros: code is written in python, possibility of good visualization
    * cons: community-developed tools; a bit more difficult to get started with a new software
* [More advanced course on DeepRL](https://spinningup.openai.com/en/latest/user/introduction.html), really good if you want to get into the topic
Environment   | Language | getting started  |  installation | visualization   |  Official
-----------------|-------------|-------------------|---------------|-----------------|----------------
OpenAIGym   | python      |           :hatched_chick:           |        :hatched_chick:        |      :large_yellow_square:             |        :white_check_mark:
Blender           | python      |           :baby_chick:           |        :hatched_chick:        |      :large_green_square:             |        :x:
Unity               | C#             |           :chicken:           |        :chicken:        |      :large_green_square:             |        :white_check_mark:
Unreal             | python      |           :baby_chick:           |        :baby_chick:        |      :large_green_square:             |        :x:
HuggingFace  | python      |           :hatched_chick:           |        :hatched_chick:        |      :large_yellow_square:             |        :white_check_mark:

__Regrading c#:__

* Unity has a great [explanation](https://unity.com/how-to/learning-c-sharp-unity-beginners) on how to use it
* Codecademy [courses](https://www.codecademy.com/catalog/language/c-sharp) - interactive like in datacamp, but somewhat more challenging in a good sense
Unity module responsible for simulation is called physics, it allows you to simulate many real-world processes. There are tutorials on Unity learning platform on how different operations from this module work (unfortunately, applied to other fields)
:warning: I would recommend looking into other options before going into C#
But the project is yours and the decision is yours :slightly_smiling_face:

* [template](https://docs.google.com/presentation/d/1iRoj34PmbTtoXqmN-l2shdQgcb_fzEZxId413Ug9H5k/edit?usp=sharing)
* [intro examples](https://mlvu.github.io/lecture13/)
* [one more](https://arxiv.org/pdf/1809.02627.pdf)
* [ML Agents resources](https://github.com/Unity-Technologies/ml-agents?tab=readme-ov-file)
* [robot arm example](https://www.youtube.com/watch?v=uD3Oe9YygzE)
* [critical thought](https://towardsdatascience.com/why-you-shouldnt-use-reinforcement-learning-163bae193da8)

## Special

for the translation API there are a few options:
* [Google Translate API](https://cloud.google.com/translate?hl=en#translate-docs-audio-and-videos-in-real-time-with-google-ai)  - The first 500,000 characters sent to the API to process (probably best option if you are within these limits)
* [GoogleTrans](https://py-googletrans.readthedocs.io/en/latest/) - a free package that I have found, unsure if it is good, since I don't know who developed it
* [ChatGPT API](https://medium.com/@datagirl_73546/use-chatgpt-api-in-python-code-to-translate-texts-8def3d7ab4e4)- you need to have an account, then follow the steps in the linked tutorial
* [Yandex](https://yandex.com/dev/translate/) - free tier
* [Azure](https://azure.microsoft.com/en-us/products/ai-services/ai-translator) - free to begin