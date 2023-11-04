# Image Generation Using Diffusion Models

This notebook demonstrates how to generate images using diffusion models. It provides examples of different models and prompts you can use to generate images.

## Setup

To run this notebook, you'll need Google Colab, [HERE](https://colab.research.google.com/)

Here is the notebook : 

**Simple :**
[![SIMPLE](https://img.shields.io/badge/-Colab-05122A?style=flat&logo=googlecolab)](https://colab.research.google.com/gist/faizonly5953/6615388356f2fc9665ec061b09c6100c/stable_diffusion_update.ipynb)

**Advanced :**
[![ADVANCED](https://img.shields.io/badge/-Colab-05122A?style=flat&logo=googlecolab)](https://colab.research.google.com/gist/faizonly5953/73faf7c436e0508e93a01404e962e2a7/stable_diffusion_advanced.ipynb)

**Short Explanation About Google Colab :**

Google Colab, short for Google Colaboratory, is a cloud-based platform provided by Google that allows users to write and execute Python code within a web-based integrated development environment (IDE). It offers a convenient and free environment for developing and running machine learning models, data analysis, and various data science tasks.

## Models
You can choose from different diffusion models to generate images. Select one of the following models and run the respective cell to set up the model.

**Realisian Model:** [OUTPUT EXAMPLE](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/ab5b700f-1cc6-408a-bac2-1d3cc38be280/width=450/00001-20230712095453.jpeg)

**Waifu Diffusion Model:** [OUTPUT EXAMPLE](https://user-images.githubusercontent.com/26317155/210155933-db3a5f1a-1ec3-4777-915c-6deff2841ce9.png)

**OrangeMix Model:** [OUTPUT EXAMPLE](https://raw.githubusercontent.com/WarriorMama777/imgup/2c840982550fab41f45ba4b5aedbd3d84ddf2390/img/AOM3/img_sanmples_AOM3_01_comp001.webp)

# Prompt
You can specify a prompt to generate images using the selected model. There is some required prompt so that the image can be generated : 

**Prompt :** start with a written description, often in natural language, that conveys what you want to see in an image. This can be a detailed description of objects, scenes, characters, or any visual concept.


**Negative Prompt :** a "negative prompt" is a textual input that is used to guide the model in generating images that are different from what the prompt describes or specifies. It's essentially a way to instruct the model to avoid certain features or characteristics in the generated image.


**Width:** The width of the image represents the number of horizontal pixels in the generated image. It determines how wide the image will be from left to right.


**Height:** The height of the image represents the number of vertical pixels in the generated image. It determines how tall the image will be from top to bottom.


## Tools
You can also use the code cell to fix false NSFW detection if required.

#
Enjoy generating images using diffusion models! You can modify prompts and explore different models to create stunning images.
