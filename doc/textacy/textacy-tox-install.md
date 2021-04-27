# textacy

`tox.ini` installation:
```setup
/home/cwm/git/git.c-w-m/nlp_dev/.tox/nlp_dev37/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 11:54 AM ...
textacy37 create: /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37
textacy37 installdeps: -rrequirements.txt
textacy37 develop-inst: /home/cwm/git/git.c-w-m/nlp_dev/src/textacy
textacy37 installed: anyio==2.2.0,appdirs==1.4.4,argon2-cffi==20.1.0,async-generator==1.10,attrs==20.3.0,Babel==2.9.0,backcall==0.2.0,beautifulsoup4==4.9.3,bleach==3.3.0,blis==0.7.4,cachetools==4.2.1,catalogue==2.0.3,certifi==2020.12.5,cffi==1.14.5,chardet==4.0.0,click==7.1.2,cycler==0.10.0,cymem==2.0.5,Cython==0.29.23,cytoolz==0.11.0,decorator==4.4.2,defusedxml==0.7.1,deprecation==2.1.0,distlib==0.3.1,entrypoints==0.3,filelock==3.0.12,future==0.18.2,idna==2.10,importlib-metadata==3.4.0,importlib-resources==5.1.0,ipykernel==5.5.3,ipython==7.22.0,ipython-genutils==0.2.0,jedi==0.18.0,jellyfish==0.8.2,Jinja2==2.11.3,joblib==1.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-packaging==0.9.1,jupyter-server==1.6.2,jupyterlab==3.0.14,jupyterlab-pygments==0.1.2,jupyterlab-server==2.4.0,kiwisolver==1.3.1,MarkupSafe==1.1.1,matplotlib==3.4.1,mistune==0.8.4,murmurhash==1.0.5,nbclassic==0.2.7,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,networkx==2.5.1,notebook==6.3.0,numpy==1.20.2,oauthlib==3.1.0,packaging==20.9,pandocfilters==1.4.3,parso==0.8.2,pathy==0.4.0,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.2.0,pluggy==0.13.1,preshed==3.0.5,prometheus-client==0.10.1,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,pycld2==0.41,pycparser==2.20,pydantic==1.7.3,Pygments==2.8.1,pyparsing==2.4.7,Pyphen==0.10.0,pyrsistent==0.17.3,python-dateutil==2.8.1,python-twitter==3.5,pytz==2021.1,PyYAML==5.4.1,pyzmq==22.0.3,requests==2.25.1,requests-oauthlib==1.3.0,scikit-learn==0.24.1,scipy==1.6.2,Send2Trash==1.5.0,six==1.15.0,smart-open==3.0.0,sniffio==1.2.0,soupsieve==2.2.1,spacy==3.0.5,spacy-legacy==3.0.2,srsly==2.4.1,terminado==0.9.4,testpath==0.4.4,-e git+https://github.com/c-w-m/textacy.git@ae0741c0795920e60c5d90ade3d7880f2afcf435#egg=textacy&subdirectory=../../../src/textacy,thinc==8.0.2,threadpoolctl==2.1.0,toml==0.10.2,tomlkit==0.7.0,toolz==0.11.1,tornado==6.1,tox==3.22.0,tqdm==4.60.0,traitlets==5.0.5,typer==0.3.2,typing-extensions==3.7.4.3,urllib3==1.26.4,virtualenv==20.4.2,wasabi==0.8.2,wcwidth==0.2.5,webencodings==0.5.1,wikipedia==1.4.0,zipp==3.4.0
textacy37 run-test-pre: PYTHONHASHSEED='3818399097'
textacy37 run-test: commands[0] | python setup.py develop
running develop
running egg_info
writing src/textacy.egg-info/PKG-INFO
writing dependency_links to src/textacy.egg-info/dependency_links.txt
writing requirements to src/textacy.egg-info/requires.txt
writing top-level names to src/textacy.egg-info/top_level.txt
reading manifest file 'src/textacy.egg-info/SOURCES.txt'
reading manifest template 'MANIFEST.in'
no previously-included directories found matching 'docs/build/'
warning: no previously-included files matching '__pycache__' found anywhere in distribution
warning: no previously-included files matching '*.py[cod]' found anywhere in distribution
writing manifest file 'src/textacy.egg-info/SOURCES.txt'
running build_ext
Creating /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages/textacy.egg-link (link to src)
textacy 0.11.0 is already the active version in easy-install.pth

Installed /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/src
Processing dependencies for textacy==0.11.0
Searching for tqdm==4.60.0
Best match: tqdm 4.60.0
Adding tqdm 4.60.0 to easy-install.pth file
Installing tqdm script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for spacy==3.0.5
Best match: spacy 3.0.5
Adding spacy 3.0.5 to easy-install.pth file
Installing spacy script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for scikit-learn==0.24.1
Best match: scikit-learn 0.24.1
Adding scikit-learn 0.24.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for scipy==1.6.2
Best match: scipy 1.6.2
Adding scipy 1.6.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for requests==2.25.1
Best match: requests 2.25.1
Adding requests 2.25.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for Pyphen==0.10.0
Best match: Pyphen 0.10.0
Adding Pyphen 0.10.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for numpy==1.20.2
Best match: numpy 1.20.2
Adding numpy 1.20.2 to easy-install.pth file
Installing f2py script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin
Installing f2py3 script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin
Installing f2py3.7 script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for networkx==2.5.1
Best match: networkx 2.5.1
Adding networkx 2.5.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for joblib==1.0.1
Best match: joblib 1.0.1
Adding joblib 1.0.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for jellyfish==0.8.2
Best match: jellyfish 0.8.2
Adding jellyfish 0.8.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for cytoolz==0.11.0
Best match: cytoolz 0.11.0
Adding cytoolz 0.11.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for cachetools==4.2.1
Best match: cachetools 4.2.1
Adding cachetools 4.2.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for preshed==3.0.5
Best match: preshed 3.0.5
Adding preshed 3.0.5 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for wasabi==0.8.2
Best match: wasabi 0.8.2
Adding wasabi 0.8.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for srsly==2.4.1
Best match: srsly 2.4.1
Adding srsly 2.4.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for typing-extensions==3.7.4.3
Best match: typing-extensions 3.7.4.3
Adding typing-extensions 3.7.4.3 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for thinc==8.0.2
Best match: thinc 8.0.2
Adding thinc 8.0.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for setuptools==54.0.0
Best match: setuptools 54.0.0
Adding setuptools 54.0.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for murmurhash==1.0.5
Best match: murmurhash 1.0.5
Adding murmurhash 1.0.5 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for typer==0.3.2
Best match: typer 0.3.2
Adding typer 0.3.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for Jinja2==2.11.3
Best match: Jinja2 2.11.3
Adding Jinja2 2.11.3 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for spacy-legacy==3.0.2
Best match: spacy-legacy 3.0.2
Adding spacy-legacy 3.0.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for pydantic==1.7.3
Best match: pydantic 1.7.3
Adding pydantic 1.7.3 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for blis==0.7.4
Best match: blis 0.7.4
Adding blis 0.7.4 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for packaging==20.9
Best match: packaging 20.9
Adding packaging 20.9 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for importlib-metadata==3.4.0
Best match: importlib-metadata 3.4.0
Adding importlib-metadata 3.4.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for catalogue==2.0.3
Best match: catalogue 2.0.3
Adding catalogue 2.0.3 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for pathy==0.4.0
Best match: pathy 0.4.0
Adding pathy 0.4.0 to easy-install.pth file
Installing pathy script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for cymem==2.0.5
Best match: cymem 2.0.5
Adding cymem 2.0.5 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for threadpoolctl==2.1.0
Best match: threadpoolctl 2.1.0
Adding threadpoolctl 2.1.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for certifi==2020.12.5
Best match: certifi 2020.12.5
Adding certifi 2020.12.5 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for chardet==4.0.0
Best match: chardet 4.0.0
Adding chardet 4.0.0 to easy-install.pth file
Installing chardetect script to /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/bin

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for urllib3==1.26.4
Best match: urllib3 1.26.4
Adding urllib3 1.26.4 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for idna==2.10
Best match: idna 2.10
Adding idna 2.10 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for decorator==4.4.2
Best match: decorator 4.4.2
Adding decorator 4.4.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for toolz==0.11.1
Best match: toolz 0.11.1
Adding toolz 0.11.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for click==7.1.2
Best match: click 7.1.2
Adding click 7.1.2 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for MarkupSafe==1.1.1
Best match: MarkupSafe 1.1.1
Adding MarkupSafe 1.1.1 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for pyparsing==2.4.7
Best match: pyparsing 2.4.7
Adding pyparsing 2.4.7 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for zipp==3.4.0
Best match: zipp 3.4.0
Adding zipp 3.4.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Searching for smart-open==3.0.0
Best match: smart-open 3.0.0
Adding smart-open 3.0.0 to easy-install.pth file

Using /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/.tox/textacy37/lib/python3.7/site-packages
Finished processing dependencies for textacy==0.11.0
textacy37 run-test: commands[1] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
textacy37 run-test: commands[2] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
textacy37 run-test: commands[3] | python -m pip list --format=columns
Package             Version   Location
------------------- --------- -----------------------------------------------
anyio               2.2.0
appdirs             1.4.4
argon2-cffi         20.1.0
async-generator     1.10
attrs               20.3.0
Babel               2.9.0
backcall            0.2.0
beautifulsoup4      4.9.3
bleach              3.3.0
blis                0.7.4
cachetools          4.2.1
catalogue           2.0.3
certifi             2020.12.5
cffi                1.14.5
chardet             4.0.0
click               7.1.2
cycler              0.10.0
cymem               2.0.5
Cython              0.29.23
cytoolz             0.11.0
decorator           4.4.2
defusedxml          0.7.1
deprecation         2.1.0
distlib             0.3.1
entrypoints         0.3
filelock            3.0.12
future              0.18.2
idna                2.10
importlib-metadata  3.4.0
importlib-resources 5.1.0
ipykernel           5.5.3
ipython             7.22.0
ipython-genutils    0.2.0
jedi                0.18.0
jellyfish           0.8.2
Jinja2              2.11.3
joblib              1.0.1
json5               0.9.5
jsonschema          3.2.0
jupyter-client      6.1.12
jupyter-core        4.7.1
jupyter-packaging   0.9.1
jupyter-server      1.6.2
jupyterlab          3.0.14
jupyterlab-pygments 0.1.2
jupyterlab-server   2.4.0
kiwisolver          1.3.1
MarkupSafe          1.1.1
matplotlib          3.4.1
mistune             0.8.4
murmurhash          1.0.5
nbclassic           0.2.7
nbclient            0.5.3
nbconvert           6.0.7
nbformat            5.1.3
nest-asyncio        1.5.1
networkx            2.5.1
notebook            6.3.0
numpy               1.20.2
oauthlib            3.1.0
packaging           20.9
pandocfilters       1.4.3
parso               0.8.2
pathy               0.4.0
pexpect             4.8.0
pickleshare         0.7.5
Pillow              8.2.0
pip                 21.0.1
pluggy              0.13.1
preshed             3.0.5
prometheus-client   0.10.1
prompt-toolkit      3.0.18
ptyprocess          0.7.0
py                  1.10.0
pycld2              0.41
pycparser           2.20
pydantic            1.7.3
Pygments            2.8.1
pyparsing           2.4.7
Pyphen              0.10.0
pyrsistent          0.17.3
python-dateutil     2.8.1
python-twitter      3.5
pytz                2021.1
PyYAML              5.4.1
pyzmq               22.0.3
requests            2.25.1
requests-oauthlib   1.3.0
scikit-learn        0.24.1
scipy               1.6.2
Send2Trash          1.5.0
setuptools          54.0.0
six                 1.15.0
smart-open          3.0.0
sniffio             1.2.0
soupsieve           2.2.1
spacy               3.0.5
spacy-legacy        3.0.2
srsly               2.4.1
terminado           0.9.4
testpath            0.4.4
textacy             0.11.0    /home/cwm/git/git.c-w-m/nlp_dev/src/textacy/src
thinc               8.0.2
threadpoolctl       2.1.0
toml                0.10.2
tomlkit             0.7.0
toolz               0.11.1
tornado             6.1
tox                 3.22.0
tqdm                4.60.0
traitlets           5.0.5
typer               0.3.2
typing-extensions   3.7.4.3
urllib3             1.26.4
virtualenv          20.4.2
wasabi              0.8.2
wcwidth             0.2.5
webencodings        0.5.1
wheel               0.36.2
wikipedia           1.4.0
zipp                3.4.0
textacy37 run-test: commands[4] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
textacy37 run-test: commands[5] | pip freeze
anyio==2.2.0
appdirs==1.4.4
argon2-cffi==20.1.0
async-generator==1.10
attrs==20.3.0
Babel==2.9.0
backcall==0.2.0
beautifulsoup4==4.9.3
bleach==3.3.0
blis==0.7.4
cachetools==4.2.1
catalogue==2.0.3
certifi==2020.12.5
cffi==1.14.5
chardet==4.0.0
click==7.1.2
cycler==0.10.0
cymem==2.0.5
Cython==0.29.23
cytoolz==0.11.0
decorator==4.4.2
defusedxml==0.7.1
deprecation==2.1.0
distlib==0.3.1
entrypoints==0.3
filelock==3.0.12
future==0.18.2
idna==2.10
importlib-metadata==3.4.0
importlib-resources==5.1.0
ipykernel==5.5.3
ipython==7.22.0
ipython-genutils==0.2.0
jedi==0.18.0
jellyfish==0.8.2
Jinja2==2.11.3
joblib==1.0.1
json5==0.9.5
jsonschema==3.2.0
jupyter-client==6.1.12
jupyter-core==4.7.1
jupyter-packaging==0.9.1
jupyter-server==1.6.2
jupyterlab==3.0.14
jupyterlab-pygments==0.1.2
jupyterlab-server==2.4.0
kiwisolver==1.3.1
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
notebook==6.3.0
numpy==1.20.2
oauthlib==3.1.0
packaging==20.9
pandocfilters==1.4.3
parso==0.8.2
pathy==0.4.0
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.2.0
pluggy==0.13.1
preshed==3.0.5
prometheus-client==0.10.1
prompt-toolkit==3.0.18
ptyprocess==0.7.0
py==1.10.0
pycld2==0.41
pycparser==2.20
pydantic==1.7.3
Pygments==2.8.1
pyparsing==2.4.7
Pyphen==0.10.0
pyrsistent==0.17.3
python-dateutil==2.8.1
python-twitter==3.5
pytz==2021.1
PyYAML==5.4.1
pyzmq==22.0.3
requests==2.25.1
requests-oauthlib==1.3.0
scikit-learn==0.24.1
scipy==1.6.2
Send2Trash==1.5.0
six==1.15.0
smart-open==3.0.0
sniffio==1.2.0
soupsieve==2.2.1
spacy==3.0.5
spacy-legacy==3.0.2
srsly==2.4.1
terminado==0.9.4
testpath==0.4.4
-e git+https://github.com/c-w-m/textacy.git@ae0741c0795920e60c5d90ade3d7880f2afcf435#egg=textacy&subdirectory=../../../src/textacy
thinc==8.0.2
threadpoolctl==2.1.0
toml==0.10.2
tomlkit==0.7.0
toolz==0.11.1
tornado==6.1
tox==3.22.0
tqdm==4.60.0
traitlets==5.0.5
typer==0.3.2
typing-extensions==3.7.4.3
urllib3==1.26.4
virtualenv==20.4.2
wasabi==0.8.2
wcwidth==0.2.5
webencodings==0.5.1
wikipedia==1.4.0
zipp==3.4.0
textacy37 run-test: commands[6] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

___________________________________ summary ____________________________________
  textacy37: commands succeeded
  congratulations :)

Process finished with exit code 0

```