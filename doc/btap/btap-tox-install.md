# Blueprint for Text Analytics Using Python (btap)

`tox.ini` installation:
```setup
/home/cwm/git/git.c-w-m/nlp_dev/.tox/nlp_dev37/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pydev/pydevd.py --multiproc --qt-support=auto --client 127.0.0.1 --port 36533 --file /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 9:10 PM ...
Connected to pydev debugger (build 211.6693.115)
btap38 create: /home/cwm/git/git.c-w-m/nlp_dev/src/btap/.tox/btap38
btap38 installdeps: jupyterlab, ipykernel, numpy, tensorflow, tensorflow_datasets, tensorflow_addons, stanza, stopwordsiso, sklearn, keras, ipywidgets, regex, unidecode, tabulate, pandas>=1.1.0, scikit-learn>=0.23.2, matplotlib, seaborn, plotly>=4.8.2, umap-learn, notebook, jupyter, jupyter_contrib_nbextensions, jupyter_nbextensions_configurator, networkx, graphviz, cython, pip, beautifulsoup4, nltk, spacy>=2.3.2, textacy, gensim, pyldavis, wordcloud, -rch01/requirements.txt, -rch02/requirements.txt, -rch03/requirements.txt, -rch04/requirements.txt, -rch05/requirements.txt, -rch06/requirements.txt, -rch07/requirements.txt, -rch08/requirements.txt, -rch09/requirements.txt, -rch10/requirements.txt, -rch11/requirements.txt, -rch12/requirements.txt
btap38 installed: absl-py==0.12.0,anchor-exp==0.0.2.0,anyio==2.2.0,argon2-cffi==20.1.0,astunparse==1.6.3,async-generator==1.10,attrs==20.3.0,Automat==20.2.0,Babel==2.9.0,backcall==0.2.0,beautifulsoup4==4.9.3,bleach==3.3.0,blis==0.4.1,boto3==1.17.53,botocore==1.20.53,breadability==0.1.20,bs4==0.0.1,cachetools==4.2.1,catalogue==1.0.0,certifi==2020.12.5,cffi==1.14.5,chardet==4.0.0,click==7.1.2,constantly==15.1.0,cryptography==3.4.7,cssselect==1.1.0,cycler==0.10.0,cymem==2.0.5,Cython==0.29.23,cytoolz==0.11.0,decorator==4.4.2,defusedxml==0.7.1,deprecation==2.1.0,dill==0.3.3,docopt==0.6.2,eli5==0.11.0,entrypoints==0.3,fasttext==0.9.2,feedparser==6.0.2,filelock==3.0.12,funcy==1.15,future==0.18.2,gast==0.3.3,gensim==4.0.1,google-auth==1.29.0,google-auth-oauthlib==0.4.4,google-pasta==0.2.0,googleapis-common-protos==1.53.0,graphviz==0.16,grpcio==1.37.0,h2==3.2.0,h5py==2.10.0,hpack==3.0.0,hyperframe==5.2.0,hyperlink==21.0.0,idna==2.10,imageio==2.9.0,importlib-resources==5.1.2,incremental==21.3.0,ipykernel==5.5.3,ipython==7.22.0,ipython-genutils==0.2.0,ipywidgets==7.6.3,isodate==0.6.0,itemadapter==0.2.0,itemloaders==1.0.4,jedi==0.18.0,jellyfish==0.8.2,Jinja2==2.11.3,jmespath==0.10.0,joblib==1.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter==1.0.0,jupyter-client==6.1.12,jupyter-console==6.4.0,jupyter-contrib-core==0.3.3,jupyter-contrib-nbextensions==0.5.1,jupyter-core==4.7.1,jupyter-highlight-selected-word==0.2.0,jupyter-latex-envs==1.4.6,jupyter-nbextensions-configurator==0.4.1,jupyter-packaging==0.9.1,jupyter-server==1.6.2,jupyterlab==3.0.14,jupyterlab-pygments==0.1.2,jupyterlab-server==2.4.0,jupyterlab-widgets==1.0.0,Keras==2.4.3,Keras-Preprocessing==1.1.2,kiwisolver==1.3.1,lime==0.2.0.1,llvmlite==0.36.0,lxml==4.6.3,Markdown==3.3.4,MarkupSafe==1.1.1,matplotlib==3.4.1,mistune==0.8.4,murmurhash==1.0.5,nbclassic==0.2.7,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,networkx==2.5.1,neuralcoref==4.0,nltk==3.6.1,notebook==6.3.0,numba==0.53.1,numexpr==2.7.3,numpy==1.20.2,oauthlib==3.1.0,opt-einsum==3.3.0,packaging==20.9,pandas==1.2.4,pandocfilters==1.4.3,parsel==1.6.0,parso==0.8.2,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.2.0,plac==1.1.3,plotly==4.14.3,preshed==3.0.5,priority==1.3.0,prometheus-client==0.10.1,promise==2.3,prompt-toolkit==3.0.18,Protego==0.1.16,protobuf==3.15.8,ptyprocess==0.7.0,pyasn1==0.4.8,pyasn1-modules==0.2.8,pybind11==2.6.2,pycountry==20.7.3,pycparser==2.20,PyDispatcher==2.0.5,pydot==1.4.2,pyemd==0.5.1,Pygments==2.8.1,pyLDAvis==3.3.1,pynndescent==0.5.2,pyOpenSSL==20.0.1,pyparsing==2.4.7,Pyphen==0.10.0,pyrsistent==0.17.3,PySocks==1.7.1,python-dateutil==2.8.1,pytz==2021.1,PyWavelets==1.1.1,PyYAML==5.4.1,pyzmq==22.0.3,qtconsole==5.0.3,QtPy==1.9.0,queuelib==1.5.0,rdflib==5.0.0,readability-lxml==0.8.1,regex==2021.4.4,requests==2.25.1,requests-oauthlib==1.3.0,retrying==1.3.3,rouge-score==0.0.4,rsa==4.7.2,s3transfer==0.3.7,sacremoses==0.0.44,scikit-image==0.18.1,scikit-learn==0.23.2,scipy==1.4.1,Scrapy==2.5.0,seaborn==0.11.1,Send2Trash==1.5.0,sentencepiece==0.1.91,service-identity==18.1.0,sgmllib3k==1.0.0,six==1.15.0,sklearn==0.0,smart-open==5.0.0,sniffio==1.2.0,soupsieve==2.2.1,spacy==2.3.2,SPARQLWrapper==1.8.5,srsly==1.0.5,stanza==1.2,stopwordsiso==0.6.1,sumy==0.8.1,tabulate==0.8.9,tensorboard==2.2.2,tensorboard-plugin-wit==1.8.0,tensorflow==2.2.0,tensorflow-addons==0.12.1,tensorflow-datasets==4.2.0,tensorflow-estimator==2.2.0,tensorflow-metadata==0.29.0,termcolor==1.1.0,terminado==0.9.4,testpath==0.4.4,textacy==0.10.1,textdistance==4.2.0,thinc==7.4.1,threadpoolctl==2.1.0,tifffile==2021.4.8,tokenizers==0.9.3,tomlkit==0.7.0,toolz==0.11.1,torch==1.8.1,tornado==6.1,tqdm==4.60.0,traitlets==5.0.5,transformers==3.5.1,tweepy==3.9.0,Twisted==21.2.0,typeguard==2.12.0,typing-extensions==3.7.4.3,umap-learn==0.5.1,Unidecode==1.2.0,urllib3==1.26.4,w3lib==1.22.0,wasabi==0.8.2,wcwidth==0.2.5,webencodings==0.5.1,Werkzeug==1.0.1,widgetsnbextension==3.5.1,Wikipedia-API==0.5.4,wordcloud==1.8.1,wrapt==1.12.1,xmltodict==0.12.0,zope.interface==5.4.0
btap38 run-test-pre: PYTHONHASHSEED='1570655044'
btap38 run-test: commands[0] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
btap38 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
btap38 run-test: commands[2] | python -m pip list --format=columns
Package                           Version
--------------------------------- ---------
absl-py                           0.12.0
anchor-exp                        0.0.2.0
anyio                             2.2.0
argon2-cffi                       20.1.0
astunparse                        1.6.3
async-generator                   1.10
attrs                             20.3.0
Automat                           20.2.0
Babel                             2.9.0
backcall                          0.2.0
beautifulsoup4                    4.9.3
bleach                            3.3.0
blis                              0.4.1
boto3                             1.17.53
botocore                          1.20.53
breadability                      0.1.20
bs4                               0.0.1
cachetools                        4.2.1
catalogue                         1.0.0
certifi                           2020.12.5
cffi                              1.14.5
chardet                           4.0.0
click                             7.1.2
constantly                        15.1.0
cryptography                      3.4.7
cssselect                         1.1.0
cycler                            0.10.0
cymem                             2.0.5
Cython                            0.29.23
cytoolz                           0.11.0
decorator                         4.4.2
defusedxml                        0.7.1
deprecation                       2.1.0
dill                              0.3.3
docopt                            0.6.2
eli5                              0.11.0
entrypoints                       0.3
fasttext                          0.9.2
feedparser                        6.0.2
filelock                          3.0.12
funcy                             1.15
future                            0.18.2
gast                              0.3.3
gensim                            4.0.1
google-auth                       1.29.0
google-auth-oauthlib              0.4.4
google-pasta                      0.2.0
googleapis-common-protos          1.53.0
graphviz                          0.16
grpcio                            1.37.0
h2                                3.2.0
h5py                              2.10.0
hpack                             3.0.0
hyperframe                        5.2.0
hyperlink                         21.0.0
idna                              2.10
imageio                           2.9.0
importlib-resources               5.1.2
incremental                       21.3.0
ipykernel                         5.5.3
ipython                           7.22.0
ipython-genutils                  0.2.0
ipywidgets                        7.6.3
isodate                           0.6.0
itemadapter                       0.2.0
itemloaders                       1.0.4
jedi                              0.18.0
jellyfish                         0.8.2
Jinja2                            2.11.3
jmespath                          0.10.0
joblib                            1.0.1
json5                             0.9.5
jsonschema                        3.2.0
jupyter                           1.0.0
jupyter-client                    6.1.12
jupyter-console                   6.4.0
jupyter-contrib-core              0.3.3
jupyter-contrib-nbextensions      0.5.1
jupyter-core                      4.7.1
jupyter-highlight-selected-word   0.2.0
jupyter-latex-envs                1.4.6
jupyter-nbextensions-configurator 0.4.1
jupyter-packaging                 0.9.1
jupyter-server                    1.6.2
jupyterlab                        3.0.14
jupyterlab-pygments               0.1.2
jupyterlab-server                 2.4.0
jupyterlab-widgets                1.0.0
Keras                             2.4.3
Keras-Preprocessing               1.1.2
kiwisolver                        1.3.1
lime                              0.2.0.1
llvmlite                          0.36.0
lxml                              4.6.3
Markdown                          3.3.4
MarkupSafe                        1.1.1
matplotlib                        3.4.1
mistune                           0.8.4
murmurhash                        1.0.5
nbclassic                         0.2.7
nbclient                          0.5.3
nbconvert                         6.0.7
nbformat                          5.1.3
nest-asyncio                      1.5.1
networkx                          2.5.1
neuralcoref                       4.0
nltk                              3.6.1
notebook                          6.3.0
numba                             0.53.1
numexpr                           2.7.3
numpy                             1.20.2
oauthlib                          3.1.0
opt-einsum                        3.3.0
packaging                         20.9
pandas                            1.2.4
pandocfilters                     1.4.3
parsel                            1.6.0
parso                             0.8.2
pexpect                           4.8.0
pickleshare                       0.7.5
Pillow                            8.2.0
pip                               21.0.1
plac                              1.1.3
plotly                            4.14.3
preshed                           3.0.5
priority                          1.3.0
prometheus-client                 0.10.1
promise                           2.3
prompt-toolkit                    3.0.18
Protego                           0.1.16
protobuf                          3.15.8
ptyprocess                        0.7.0
pyasn1                            0.4.8
pyasn1-modules                    0.2.8
pybind11                          2.6.2
pycountry                         20.7.3
pycparser                         2.20
PyDispatcher                      2.0.5
pydot                             1.4.2
pyemd                             0.5.1
Pygments                          2.8.1
pyLDAvis                          3.3.1
pynndescent                       0.5.2
pyOpenSSL                         20.0.1
pyparsing                         2.4.7
Pyphen                            0.10.0
pyrsistent                        0.17.3
PySocks                           1.7.1
python-dateutil                   2.8.1
pytz                              2021.1
PyWavelets                        1.1.1
PyYAML                            5.4.1
pyzmq                             22.0.3
qtconsole                         5.0.3
QtPy                              1.9.0
queuelib                          1.5.0
rdflib                            5.0.0
readability-lxml                  0.8.1
regex                             2021.4.4
requests                          2.25.1
requests-oauthlib                 1.3.0
retrying                          1.3.3
rouge-score                       0.0.4
rsa                               4.7.2
s3transfer                        0.3.7
sacremoses                        0.0.44
scikit-image                      0.18.1
scikit-learn                      0.23.2
scipy                             1.4.1
Scrapy                            2.5.0
seaborn                           0.11.1
Send2Trash                        1.5.0
sentencepiece                     0.1.91
service-identity                  18.1.0
setuptools                        52.0.0
sgmllib3k                         1.0.0
six                               1.15.0
sklearn                           0.0
smart-open                        5.0.0
sniffio                           1.2.0
soupsieve                         2.2.1
spacy                             2.3.2
SPARQLWrapper                     1.8.5
srsly                             1.0.5
stanza                            1.2
stopwordsiso                      0.6.1
sumy                              0.8.1
tabulate                          0.8.9
tensorboard                       2.2.2
tensorboard-plugin-wit            1.8.0
tensorflow                        2.2.0
tensorflow-addons                 0.12.1
tensorflow-datasets               4.2.0
tensorflow-estimator              2.2.0
tensorflow-metadata               0.29.0
termcolor                         1.1.0
terminado                         0.9.4
testpath                          0.4.4
textacy                           0.10.1
textdistance                      4.2.0
thinc                             7.4.1
threadpoolctl                     2.1.0
tifffile                          2021.4.8
tokenizers                        0.9.3
tomlkit                           0.7.0
toolz                             0.11.1
torch                             1.8.1
tornado                           6.1
tqdm                              4.60.0
traitlets                         5.0.5
transformers                      3.5.1
tweepy                            3.9.0
Twisted                           21.2.0
typeguard                         2.12.0
typing-extensions                 3.7.4.3
umap-learn                        0.5.1
Unidecode                         1.2.0
urllib3                           1.26.4
w3lib                             1.22.0
wasabi                            0.8.2
wcwidth                           0.2.5
webencodings                      0.5.1
Werkzeug                          1.0.1
wheel                             0.36.2
widgetsnbextension                3.5.1
Wikipedia-API                     0.5.4
wordcloud                         1.8.1
wrapt                             1.12.1
xmltodict                         0.12.0
zope.interface                    5.4.0
btap38 run-test: commands[3] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
btap38 run-test: commands[4] | pip freeze
absl-py==0.12.0
anchor-exp==0.0.2.0
anyio==2.2.0
argon2-cffi==20.1.0
astunparse==1.6.3
async-generator==1.10
attrs==20.3.0
Automat==20.2.0
Babel==2.9.0
backcall==0.2.0
beautifulsoup4==4.9.3
bleach==3.3.0
blis==0.4.1
boto3==1.17.53
botocore==1.20.53
breadability==0.1.20
bs4==0.0.1
cachetools==4.2.1
catalogue==1.0.0
certifi==2020.12.5
cffi==1.14.5
chardet==4.0.0
click==7.1.2
constantly==15.1.0
cryptography==3.4.7
cssselect==1.1.0
cycler==0.10.0
cymem==2.0.5
Cython==0.29.23
cytoolz==0.11.0
decorator==4.4.2
defusedxml==0.7.1
deprecation==2.1.0
dill==0.3.3
docopt==0.6.2
eli5==0.11.0
entrypoints==0.3
fasttext==0.9.2
feedparser==6.0.2
filelock==3.0.12
funcy==1.15
future==0.18.2
gast==0.3.3
gensim==4.0.1
google-auth==1.29.0
google-auth-oauthlib==0.4.4
google-pasta==0.2.0
googleapis-common-protos==1.53.0
graphviz==0.16
grpcio==1.37.0
h2==3.2.0
h5py==2.10.0
hpack==3.0.0
hyperframe==5.2.0
hyperlink==21.0.0
idna==2.10
imageio==2.9.0
importlib-resources==5.1.2
incremental==21.3.0
ipykernel==5.5.3
ipython==7.22.0
ipython-genutils==0.2.0
ipywidgets==7.6.3
isodate==0.6.0
itemadapter==0.2.0
itemloaders==1.0.4
jedi==0.18.0
jellyfish==0.8.2
Jinja2==2.11.3
jmespath==0.10.0
joblib==1.0.1
json5==0.9.5
jsonschema==3.2.0
jupyter==1.0.0
jupyter-client==6.1.12
jupyter-console==6.4.0
jupyter-contrib-core==0.3.3
jupyter-contrib-nbextensions==0.5.1
jupyter-core==4.7.1
jupyter-highlight-selected-word==0.2.0
jupyter-latex-envs==1.4.6
jupyter-nbextensions-configurator==0.4.1
jupyter-packaging==0.9.1
jupyter-server==1.6.2
jupyterlab==3.0.14
jupyterlab-pygments==0.1.2
jupyterlab-server==2.4.0
jupyterlab-widgets==1.0.0
Keras==2.4.3
Keras-Preprocessing==1.1.2
kiwisolver==1.3.1
lime==0.2.0.1
llvmlite==0.36.0
lxml==4.6.3
Markdown==3.3.4
MarkupSafe==1.1.1
matplotlib==3.4.1
mistune==0.8.4
murmurhash==1.0.5
nbclassic==0.2.7
nbclient==0.5.3
nbconvert==6.0.7
nbformat==5.1.3
nest-asyncio==1.5.1
networkx==2.5.1
neuralcoref==4.0
nltk==3.6.1
notebook==6.3.0
numba==0.53.1
numexpr==2.7.3
numpy==1.20.2
oauthlib==3.1.0
opt-einsum==3.3.0
packaging==20.9
pandas==1.2.4
pandocfilters==1.4.3
parsel==1.6.0
parso==0.8.2
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.2.0
plac==1.1.3
plotly==4.14.3
preshed==3.0.5
priority==1.3.0
prometheus-client==0.10.1
promise==2.3
prompt-toolkit==3.0.18
Protego==0.1.16
protobuf==3.15.8
ptyprocess==0.7.0
pyasn1==0.4.8
pyasn1-modules==0.2.8
pybind11==2.6.2
pycountry==20.7.3
pycparser==2.20
PyDispatcher==2.0.5
pydot==1.4.2
pyemd==0.5.1
Pygments==2.8.1
pyLDAvis==3.3.1
pynndescent==0.5.2
pyOpenSSL==20.0.1
pyparsing==2.4.7
Pyphen==0.10.0
pyrsistent==0.17.3
PySocks==1.7.1
python-dateutil==2.8.1
pytz==2021.1
PyWavelets==1.1.1
PyYAML==5.4.1
pyzmq==22.0.3
qtconsole==5.0.3
QtPy==1.9.0
queuelib==1.5.0
rdflib==5.0.0
readability-lxml==0.8.1
regex==2021.4.4
requests==2.25.1
requests-oauthlib==1.3.0
retrying==1.3.3
rouge-score==0.0.4
rsa==4.7.2
s3transfer==0.3.7
sacremoses==0.0.44
scikit-image==0.18.1
scikit-learn==0.23.2
scipy==1.4.1
Scrapy==2.5.0
seaborn==0.11.1
Send2Trash==1.5.0
sentencepiece==0.1.91
service-identity==18.1.0
sgmllib3k==1.0.0
six==1.15.0
sklearn==0.0
smart-open==5.0.0
sniffio==1.2.0
soupsieve==2.2.1
spacy==2.3.2
SPARQLWrapper==1.8.5
srsly==1.0.5
stanza==1.2
stopwordsiso==0.6.1
sumy==0.8.1
tabulate==0.8.9
tensorboard==2.2.2
tensorboard-plugin-wit==1.8.0
tensorflow==2.2.0
tensorflow-addons==0.12.1
tensorflow-datasets==4.2.0
tensorflow-estimator==2.2.0
tensorflow-metadata==0.29.0
termcolor==1.1.0
terminado==0.9.4
testpath==0.4.4
textacy==0.10.1
textdistance==4.2.0
thinc==7.4.1
threadpoolctl==2.1.0
tifffile==2021.4.8
tokenizers==0.9.3
tomlkit==0.7.0
toolz==0.11.1
torch==1.8.1
tornado==6.1
tqdm==4.60.0
traitlets==5.0.5
transformers==3.5.1
tweepy==3.9.0
Twisted==21.2.0
typeguard==2.12.0
typing-extensions==3.7.4.3
umap-learn==0.5.1
Unidecode==1.2.0
urllib3==1.26.4
w3lib==1.22.0
wasabi==0.8.2
wcwidth==0.2.5
webencodings==0.5.1
Werkzeug==1.0.1
widgetsnbextension==3.5.1
Wikipedia-API==0.5.4
wordcloud==1.8.1
wrapt==1.12.1
xmltodict==0.12.0
zope.interface==5.4.0
btap38 run-test: commands[5] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

___________________________________ summary ____________________________________
  btap38: commands succeeded
  congratulations :)

Process finished with exit code 0
```