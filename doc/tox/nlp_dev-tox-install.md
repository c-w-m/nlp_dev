# NLP Development `tox` Installation

The default project environment:
```shell
/home/cwm/git/git.c-w-m/nlp_dev/.venv/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 8:13 PM ...
nlp_dev37 create: /home/cwm/git/git.c-w-m/nlp_dev/.tox/nlp_dev37
nlp_dev37 installdeps: jupyterlab, -rrequirements.txt
nlp_dev37 installed: anyio==2.2.0,appdirs==1.4.4,argon2-cffi==20.1.0,async-generator==1.10,attrs==20.3.0,Babel==2.9.0,backcall==0.2.0,bleach==3.3.0,certifi==2020.12.5,cffi==1.14.5,chardet==4.0.0,Cython==0.29.23,decorator==5.0.7,defusedxml==0.7.1,deprecation==2.1.0,distlib==0.3.1,entrypoints==0.3,filelock==3.0.12,idna==2.10,importlib-metadata==3.4.0,importlib-resources==5.1.0,ipykernel==5.5.3,ipython==7.22.0,ipython-genutils==0.2.0,jedi==0.18.0,Jinja2==2.11.3,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-packaging==0.9.1,jupyter-server==1.6.2,jupyterlab==3.0.14,jupyterlab-pygments==0.1.2,jupyterlab-server==2.4.0,MarkupSafe==1.1.1,mistune==0.8.4,nbclassic==0.2.7,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.3.0,packaging==20.9,pandocfilters==1.4.3,parso==0.8.2,pexpect==4.8.0,pickleshare==0.7.5,pluggy==0.13.1,prometheus-client==0.10.1,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,pycparser==2.20,Pygments==2.8.1,pyparsing==2.4.7,pyrsistent==0.17.3,python-dateutil==2.8.1,pytz==2021.1,pyzmq==22.0.3,requests==2.25.1,Send2Trash==1.5.0,six==1.15.0,sniffio==1.2.0,terminado==0.9.4,testpath==0.4.4,toml==0.10.2,tomlkit==0.7.0,tornado==6.1,tox==3.22.0,traitlets==5.0.5,typing-extensions==3.7.4.3,urllib3==1.26.4,virtualenv==20.4.2,wcwidth==0.2.5,webencodings==0.5.1,zipp==3.4.0
nlp_dev37 run-test-pre: PYTHONHASHSEED='649239372'
nlp_dev37 run-test: commands[0] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
nlp_dev37 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
nlp_dev37 run-test: commands[2] | python -m pip list --format=columns
Package             Version
------------------- ---------
anyio               2.2.0
appdirs             1.4.4
argon2-cffi         20.1.0
async-generator     1.10
attrs               20.3.0
Babel               2.9.0
backcall            0.2.0
bleach              3.3.0
certifi             2020.12.5
cffi                1.14.5
chardet             4.0.0
Cython              0.29.23
decorator           5.0.7
defusedxml          0.7.1
deprecation         2.1.0
distlib             0.3.1
entrypoints         0.3
filelock            3.0.12
idna                2.10
importlib-metadata  3.4.0
importlib-resources 5.1.0
ipykernel           5.5.3
ipython             7.22.0
ipython-genutils    0.2.0
jedi                0.18.0
Jinja2              2.11.3
json5               0.9.5
jsonschema          3.2.0
jupyter-client      6.1.12
jupyter-core        4.7.1
jupyter-packaging   0.9.1
jupyter-server      1.6.2
jupyterlab          3.0.14
jupyterlab-pygments 0.1.2
jupyterlab-server   2.4.0
MarkupSafe          1.1.1
mistune             0.8.4
nbclassic           0.2.7
nbclient            0.5.3
nbconvert           6.0.7
nbformat            5.1.3
nest-asyncio        1.5.1
notebook            6.3.0
packaging           20.9
pandocfilters       1.4.3
parso               0.8.2
pexpect             4.8.0
pickleshare         0.7.5
pip                 21.0.1
pluggy              0.13.1
prometheus-client   0.10.1
prompt-toolkit      3.0.18
ptyprocess          0.7.0
py                  1.10.0
pycparser           2.20
Pygments            2.8.1
pyparsing           2.4.7
pyrsistent          0.17.3
python-dateutil     2.8.1
pytz                2021.1
pyzmq               22.0.3
requests            2.25.1
Send2Trash          1.5.0
setuptools          54.0.0
six                 1.15.0
sniffio             1.2.0
terminado           0.9.4
testpath            0.4.4
toml                0.10.2
tomlkit             0.7.0
tornado             6.1
tox                 3.22.0
traitlets           5.0.5
typing-extensions   3.7.4.3
urllib3             1.26.4
virtualenv          20.4.2
wcwidth             0.2.5
webencodings        0.5.1
wheel               0.36.2
zipp                3.4.0
nlp_dev37 run-test: commands[3] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
nlp_dev37 run-test: commands[4] | pip freeze
anyio==2.2.0
appdirs==1.4.4
argon2-cffi==20.1.0
async-generator==1.10
attrs==20.3.0
Babel==2.9.0
backcall==0.2.0
bleach==3.3.0
certifi==2020.12.5
cffi==1.14.5
chardet==4.0.0
Cython==0.29.23
decorator==5.0.7
defusedxml==0.7.1
deprecation==2.1.0
distlib==0.3.1
entrypoints==0.3
filelock==3.0.12
idna==2.10
importlib-metadata==3.4.0
importlib-resources==5.1.0
ipykernel==5.5.3
ipython==7.22.0
ipython-genutils==0.2.0
jedi==0.18.0
Jinja2==2.11.3
json5==0.9.5
jsonschema==3.2.0
jupyter-client==6.1.12
jupyter-core==4.7.1
jupyter-packaging==0.9.1
jupyter-server==1.6.2
jupyterlab==3.0.14
jupyterlab-pygments==0.1.2
jupyterlab-server==2.4.0
MarkupSafe==1.1.1
mistune==0.8.4
nbclassic==0.2.7
nbclient==0.5.3
nbconvert==6.0.7
nbformat==5.1.3
nest-asyncio==1.5.1
notebook==6.3.0
packaging==20.9
pandocfilters==1.4.3
parso==0.8.2
pexpect==4.8.0
pickleshare==0.7.5
pluggy==0.13.1
prometheus-client==0.10.1
prompt-toolkit==3.0.18
ptyprocess==0.7.0
py==1.10.0
pycparser==2.20
Pygments==2.8.1
pyparsing==2.4.7
pyrsistent==0.17.3
python-dateutil==2.8.1
pytz==2021.1
pyzmq==22.0.3
requests==2.25.1
Send2Trash==1.5.0
six==1.15.0
sniffio==1.2.0
terminado==0.9.4
testpath==0.4.4
toml==0.10.2
tomlkit==0.7.0
tornado==6.1
tox==3.22.0
traitlets==5.0.5
typing-extensions==3.7.4.3
urllib3==1.26.4
virtualenv==20.4.2
wcwidth==0.2.5
webencodings==0.5.1
zipp==3.4.0
nlp_dev37 run-test: commands[5] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

___________________________________ summary ____________________________________
  nlp_dev37: commands succeeded
  congratulations :)

Process finished with exit code 0

```