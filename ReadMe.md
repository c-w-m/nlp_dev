# ![mdf-logo](doc/img/mdf-logo100x100.gif) NLP Development

#### Table of Contents
* [Setup](#markdown-header-setup)

> Note: The following projects are based on opens source tools and free 
> services.

This is an introduction level set of projects that focus on NLP and OCR.

Remember to use the `recursive` clone to get all the submodules.

## Setup

### Clone - recursive to get submodules
```shell
$ git clone --recurse-submodules https://github.com/c-w-m/nlp_dev.git
```

### Submodules
```shell
# The following submodules were added:
$ cd docs
$ git submodule add https://github.com/c-w-m/hgf-awesome-papers.git

$ cd src
$ git submodule add https://github.com/c-w-m/anlp-tf2.git
$ git submodule add https://github.com/c-w-m/btap.git
$ git submodule add https://github.com/c-w-m/colab.git
$ git submodule add https://github.com/c-w-m/hgf-datasets.git
$ git submodule add https://github.com/c-w-m/hgf-transformers.git
$ git submodule add https://github.com/c-w-m/hgf-tokenizers.git
$ git submodule add https://github.com/c-w-m/nlp-py-tutorial.git
$ git submodule add https://github.com/c-w-m/nlp-w2d.git
$ git submodule add https://github.com/c-w-m/pnlp.git
$ git submodule add https://github.com/c-w-m/snorkel-tutorials.git
$ git submodule add https://github.com/c-w-m/tensorflow.git
$ git submodule add https://github.com/c-w-m/tensorflow_docs.git
$ git submodule add https://github.com/c-w-m/tnlp.git
$ git submodule add https://github.com/c-w-m/web_scraping.git

```
#### Removing Submodules
```shell
# Remove the submodule entry from .git/config
git submodule deinit -f path/to/submodule

# Remove the submodule directory from the super-project's .git/modules 
directory
rm -rf .git/modules/path/to/submodule

# Remove the entry in .gitmodules and remove the submodule directory located at path/to/submodule
git rm -f path/to/submodule
```

### Jupyter Lab
#### Add a Kernel
```shell
$ source .tox/snorkel37/bin/activate
(snorkel37) $ python -m ipykernel install --user --name=snorkel37
```

#### List All Kernels
```shell
$ jupyter kernelspec list
```
#### Remove a Kernel
```shell
$ jupyter kernelspec uninstall <kernel_name>
```

### Helper Scripts
Two helper scripts are included, one to set the terminal path to the virtual
environment, and the other removes all the `tox` created artifacts.  Remember to
tweak these as needed for the specific project directory names.
#### Set path
* First make sure your environment is correctly set (see [Ubuntu ReadMe](doc/Ubuntu/ReadMe.md))
* make the script executable
```shell
$ chmod +x setpath.sh
```
* run
```shell
$ source ./setpath.sh
```
#### Clean Up
Run this if you want to remove all the `tox` cache directories (i.e., everything
that is not checked into the repository).
* make the script executable
```shell
$ chmod +x clean_after_tox.sh
```
* run
```shell
$ sh ./clean_after_tox.sh
```

## References

### Tutorials
* [Natural Language Processing in Python](https://www.youtube.com/watch?v=xvqsFTUsOmc)
    - code [nlp-in-python-tutorial](https://github.com/adashofdata/nlp-in-python-tutorial)
    - abstract [Natural Language Processing in Python by Alice Zhao](https://www.pyohio.org/2018/schedule/presentation/38/)

* [A comprehensive guide to OCR with Tesseract, OpenCV and Python](https://nanonets.com/blog/ocr-with-tesseract/)
    - code [ocr-with-tesseract](https://github.com/NanoNets/ocr-with-tesseract)

* [OpenCV OCR and text recognition with Tesseract](https://www.pyimagesearch.com/2018/09/17/opencv-ocr-and-text-recognition-with-tesseract/)
    - code [opencv-text-recognition](https://github.com/efviodo/opencv-text-recognition)

* [Tesseract_(software) wiki](https://en.wikipedia.org/wiki/Tesseract_(software))
    - code [tesseract-ocr](https://github.com/tesseract-ocr)
    - idioms [tessdoc](https://tesseract-ocr.github.io/tessdoc/Data-Files)
    
* [Towards AI](https://github.com/towardsai)
    - [tutorials](https://github.com/towardsai/tutorials)
    - [natural_language_processing](https://github.com/towardsai/tutorials/tree/master/natural_language_processing)

* [SuperDataScience](https://www.superdatascience.com)
    - [Computer Vision series: Download Supplemental Materials](https://www.superdatascience.com/pages/computer-vision-series)
      * [videos - Art of Visualization](https://www.youtube.com/c/ArtofVisualization/videos)
      * [OCR with Python - Part #1](https://youtu.be/tQ56PMSG-Ks)
        * [code - Part #1](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-1-Files.zip)
      * [OCR WITH PYTHON - Part #2](https://www.youtube.com/watch?v=RmffCbqDb7Y&t=2s)
        * [code - Part #2](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-2-Files.zip)
      * [OCR WITH PYTHON - Part #3](https://www.youtube.com/watch?v=azXcRM2uZJs)
        * [code - Part #3](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-3-Files.zip)
      * [Extracting Text from Video - Part #4](https://www.youtube.com/watch?v=9nJ0b1PZalY)
        * [code - Part #4](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-4-Files.zip)
      * [Boosting Accuracy - Part #5](https://www.youtube.com/watch?v=sOh9pnwZeMA)
        * [code - Part #5](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-5-Files.zip)
      * [Working with DataFrames - Part #6](https://www.youtube.com/watch?v=vresDMDR6_o)
        * [code - Part #6](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-6-Files.zip)
      * [Callenge Introduction - Part #7](https://www.youtube.com/watch?v=46aGQ3UfLbI)
        * [code - Part #7](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-7-Files.zip)
      * [Challenge Solution - Part #8](https://www.youtube.com/watch?v=qb5eG4V2FtU)
        * [code - Part #8](https://sds-platform-private.s3-us-east-2.amazonaws.com/uploads/P52-Episode-8-Files.zip)
* Blueprints for Text Analytics Using Python
    - original code: [blueprints-text](https://github.com/blueprints-for-text-analytics-python/blueprints-text)
    - local code: [btap](https://github.com/c-w-m/btap.git)
* Practical Natural Language Processing
    -  original code: [practical-nlp](https://github.com/practical-nlp/practical-nlp)
    - local code: [pnlp](https://github.com/c-w-m/pnlp.git)
* Advanced Natural Language Processing with TensorFlow 2
    - original code: [Advanced-Natural-Language-Processing-with-TensorFlow-2](https://github.com/PacktPublishing/Advanced-Natural-Language-Processing-with-TensorFlow-2)
    - local code: [anlptf2](https://github.com/c-w-m/anlptf2.git)
* [Hugging Face](https://github.com/huggingface)
    - [awesome-papers]() 
    - transformers

### Misc Code
* [pytesseract](https://github.com/madmaze/pytesseract)
     - [pytesseract 0.3.7](https://pypi.org/project/pytesseract/)
* [Pillow](https://github.com/python-pillow/Pillow)
* [btap](https://github.com/c-w-m/btap.git)
* [pnlp](https://github.com/c-w-m/pnlp.git)
* [anlptf2](https://github.com/c-w-m/anlptf2.git)
* []()

### Blogs
* [Build your own OCR(Optical Character Recognition) for free](https://medium.com/@balaajip/optical-character-recognition-99aba2dad314)
* [Python | Reading contents of PDF using OCR (Optical Character Recognition)](https://www.geeksforgeeks.org/python-reading-contents-of-pdf-using-ocr-optical-character-recognition/)
* [Python | Convert image to text and then to speech](https://www.geeksforgeeks.org/python-convert-image-to-text-and-then-to-speech/)
* [Installing Tesseract for OCR](https://www.pyimagesearch.com/2017/07/03/installing-tesseract-for-ocr/)
* [Using Tesseract OCR with Python](https://www.pyimagesearch.com/2017/07/10/using-tesseract-ocr-python/)
* [Setting up a Simple OCR Server](https://realpython.com/setting-up-a-simple-ocr-server/)

### Google SAS
* [Training Your Models on Cloud TPUs in 4 Easy Steps on Google Colab](https://medium.com/analytics-vidhya/tpu-training-made-easy-with-colab-3b73b920878f)
* [Document AI](https://cloud.google.com/document-ai#section-1)
* [Cloud Vision API](https://cloud.google.com/vision/docs?hl=en_US)

## eLib
* [Natural Language Processing with Python - Data Science](http://www.datascienceassn.org/sites/default/files/Natural%20Language%20Processing%20with%20Python.pdf)
* [Python 3 Text Processing with NLTK 3 Cookbook](https://tailieuhoctap123blog.files.wordpress.com/2016/06/python-3-text-processing-with-nltk-3-cookbook.pdf)
* [Mastering Python Regular Expressions](http://psulibrary.palawan.edu.ph/wtbooks/resources/pdf/910016.pdf)
* [Python Data Visualization Cookbook](http://blaqueyard.com/download/Python%20Data%20Visualization%20Cookbook.pdf)
* [Python for Data Analysis](https://bedford-computing.co.uk/learning/wp-content/uploads/2015/10/Python-for-Data-Analysis.pdf)
* [Python Data Science Essentials 2nd ed](https://www.rgonzo.us/shiny/books/Python%20Data%20Science%20Essentials.pdf)
