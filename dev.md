https://pytorch.org/get-started/locally/

https://zhuanlan.zhihu.com/p/618230920

pip install -i https://pypi.mirrors.ustc.edu.cn/simple/ -U pyside6-essentials

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121  #cu121

Successfully installed torch-2.2.2+cu121

不是 pip install -i https://pypi.mirrors.ustc.edu.cn/simple/ -U torch==2.2.2+cpu

------------------------
## run
p

  Attempting uninstall: xlrd
    Found existing installation: xlrd 1.2.0
    Uninstalling xlrd-1.2.0:
      Successfully uninstalled xlrd-1.2.0
  Attempting uninstall: urllib3
    Found existing installation: urllib3 1.26.5
    Uninstalling urllib3-1.26.5:
      Successfully uninstalled urllib3-1.26.5
  Attempting uninstall: shiboken6
    Found existing installation: shiboken6 6.7.0
    Uninstalling shiboken6-6.7.0:
      Successfully uninstalled shiboken6-6.7.0
  Attempting uninstall: python-dateutil
    Found existing installation: python-dateutil 2.8.1
    Uninstalling python-dateutil-2.8.1:
      Successfully uninstalled python-dateutil-2.8.1
  Attempting uninstall: psutil
    Found existing installation: psutil 5.9.4
    Uninstalling psutil-5.9.4:
      Successfully uninstalled psutil-5.9.4
  Attempting uninstall: numpy
    Found existing installation: numpy 1.26.3
    Uninstalling numpy-1.26.3:
      Successfully uninstalled numpy-1.26.3
  Attempting uninstall: lxml
    Found existing installation: lxml 4.9.2
    Uninstalling lxml-4.9.2:
      Successfully uninstalled lxml-4.9.2
  Attempting uninstall: idna
    Found existing installation: idna 2.10
    Uninstalling idna-2.10:
      Successfully uninstalled idna-2.10
  Attempting uninstall: chardet
    Found existing installation: chardet 4.0.0
    Uninstalling chardet-4.0.0:
      Successfully uninstalled chardet-4.0.0
  Attempting uninstall: requests
    Found existing installation: requests 2.25.1
    Uninstalling requests-2.25.1:
      Successfully uninstalled requests-2.25.1
  Attempting uninstall: PySide6-Essentials
    Found existing installation: PySide6_Essentials 6.7.0
    Uninstalling PySide6_Essentials-6.7.0:
      Successfully uninstalled PySide6_Essentials-6.7.0
  Attempting uninstall: openai
    Found existing installation: openai 1.23.1
    Uninstalling openai-1.23.1:
      Successfully uninstalled openai-1.23.1
Successfully installed InstructorEmbedding-1.0.1 Markdown-3.6 PyAudio-0.2.14 PyMuPDF-1.24.0 PyMuPDFb-1.24.0 PySide6-6.6.2 PySide6-Addons-6.6.2 PySide6-Essentials-6.6.2 accelerate-0.28.0 aiohttp-3.9.5 aiosignal-1.3.1 av-12.0.0 backoff-2.2.1 chardet-5.2.0 charset-normalizer-3.3.2 click-8.1.7 cloudpickle-2.2.1 coloredlogs-15.0.1 ctranslate2-4.1.0 dataclasses-json-0.6.4 dataclasses-json-speakeasy-0.5.11 datasets-2.19.0 dill-0.3.8 docx2txt-0.8 einops-0.7.0 emoji-2.10.1 et-xmlfile-1.1.0 filetype-1.2.0 frozenlist-1.4.1 huggingface-hub-0.22.2 humanfriendly-10.0 idna-3.6 importlib-metadata-7.1.0 joblib-1.3.2 jsonpatch-1.33 jsonpath-python-1.0.6 jsonpointer-2.4 langchain-0.1.14 langchain-community-0.0.31 langchain-core-0.1.45 langchain-text-splitters-0.0.1 langdetect-1.0.9 langsmith-0.1.50 llvmlite-0.42.0 lxml-5.1.0 markdown-it-py-3.0.0 marshmallow-3.20.2 mdurl-0.1.2 more-itertools-10.2.0 msg-parser-1.2.0 multidict-6.0.5 multiprocess-0.70.16 mypy-extensions-1.0.0 nltk-3.8.1 numba-0.59.1 numpy-1.26.4 olefile-0.47 openai-1.14.3 openai-whisper-20231117 openpyxl-3.1.2 optimum-1.18.0 orjson-3.10.1 packaging-23.2 pandas-2.2.1 psutil-5.9.8 pyarrow-16.0.0 pyarrow-hotfix-0.6 pygments-2.17.2 pypandoc-1.13 pyreadline3-3.4.1 python-dateutil-2.8.2 python-docx-1.1.0 python-iso639-2024.2.7 python-magic-0.4.27 rapidfuzz-3.6.1 regex-2023.12.25 requests-2.31.0 rich-13.7.1 safetensors-0.4.3 scikit-learn-1.4.2 scipy-1.12.0 sentence-transformers-2.6.1 sentencepiece-0.2.0 shiboken6-6.6.2 sounddevice-0.4.6 tabulate-0.9.0 tblib-1.7.0 termcolor-2.4.0 threadpoolctl-3.4.0 tiktoken-0.6.0 tiledb-0.27.1 tiledb-cloud-0.12.6 tiledb-vector-search-0.2.0 timm-0.9.16 tokenizers-0.15.2 transformers-4.39.3 typing-inspect-0.9.0 tzdata-2024.1 unstructured-0.12.6 unstructured-client-0.18.0 urllib3-1.26.18 xlrd-2.0.1 xxhash-3.4.1 yarl-1.9.4 zipp-3.18.1

❯ python -m pip install -i https://pypi.tuna.tsinghua.edu.cn/simple -r requirements.txt
Looking in indexes: https://pypi.tuna.tsinghua.edu.cn/simple
Collecting openai==1.14.3 (from -r requirements.txt (line 1))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/83/30/f4c71038833912e3e3cd4083b0277d3a0e568e621cfb5c99f28b7c53dae1/openai-1.14.3-py3-none-any.whl (262 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 262.9/262.9 kB 1.2 MB/s eta 0:00:00
Collecting langchain==0.1.14 (from -r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/d5/d0/5e0bbcabe42f9e09c66fa0964b2ecdfee9a92cb2d7f05dd340b93203a40a/langchain-0.1.14-py3-none-any.whl (812 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 812.8/812.8 kB 1.3 MB/s eta 0:00:00
Collecting langchain-community==0.0.31 (from -r requirements.txt (line 3))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/8a/67/6855b4a55e4e150264fd1a51888d20a1ba3c1b7757660f7ec4a14bd3d7a0/langchain_community-0.0.31-py3-none-any.whl (1.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.9/1.9 MB 1.3 MB/s eta 0:00:00
Collecting ctranslate2==4.1.0 (from -r requirements.txt (line 4))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/20/a7/c68ef712a2844bcb3d6bfc61f462ddb0b5fe77eafe8228dafdf95620f428/ctranslate2-4.1.0-cp311-cp311-win_amd64.whl (19.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 19.2/19.2 MB 1.2 MB/s eta 0:00:00
Collecting tiledb==0.27.1 (from -r requirements.txt (line 5))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/6b/9b/b12abdf41d5216b932f28e30440bca5f7475b4423784d734e5a0b91fbe3e/tiledb-0.27.1-cp311-cp311-win_amd64.whl (8.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.5/8.5 MB 1.2 MB/s eta 0:00:00
Collecting tiledb-vector-search==0.2.0 (from -r requirements.txt (line 6))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/ff/e0/04829ae020277c8efb658690cad2bda89922bb459e2df6383e6794511dc3/tiledb_vector_search-0.2.0-cp311-cp311-win_amd64.whl (8.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.1/8.1 MB 1.2 MB/s eta 0:00:00
Collecting PyMuPDF==1.24 (from -r requirements.txt (line 7))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/7e/94/967c04c7e4aa0448eff481afdd1254240cb2cfc802f40af7d1212f0d13df/PyMuPDF-1.24.0-cp311-none-win_amd64.whl (3.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.6/3.6 MB 1.2 MB/s eta 0:00:00
Collecting InstructorEmbedding==1.0.1 (from -r requirements.txt (line 8))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/6c/fc/64375441f43cc9ddc81f76a1a8f516e6d63f5b6ecb67fffdcddc0445f0d3/InstructorEmbedding-1.0.1-py2.py3-none-any.whl (19 kB)
Collecting sentence-transformers==2.6.1 (from -r requirements.txt (line 9))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/ba/20/7ef81df2e07322d95332d07c1c38c597f543c1f666d689a3153ba6fa09e3/sentence_transformers-2.6.1-py3-none-any.whl (163 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 163.3/163.3 kB 1.2 MB/s eta 0:00:00
Collecting pandas==2.2.1 (from -r requirements.txt (line 10))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/61/11/1812ef6cbd7433ad240f72161ce5f84c4c450cede4db080365d371d29117/pandas-2.2.1-cp311-cp311-win_amd64.whl (11.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 11.6/11.6 MB 1.2 MB/s eta 0:00:00
Collecting docx2txt==0.8 (from -r requirements.txt (line 11))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/7d/7d/60ee3f2b16d9bfdfa72e8599470a2c1a5b759cb113c6fe1006be28359327/docx2txt-0.8.tar.gz (2.8 kB)
  Preparing metadata (setup.py) ... done
Collecting python-docx==1.1.0 (from -r requirements.txt (line 12))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/5f/d8/6948f7ac00edf74bfa52b3c5e3073df20284bec1db466d13e668fe991707/python_docx-1.1.0-py3-none-any.whl (239 kB)
Collecting msg-parser==1.2.0 (from -r requirements.txt (line 13))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/15/8b/5738b32acc6acdf92d04d5e691bf70a379e78264e55843542e1888d4a10e/msg_parser-1.2.0-py2.py3-none-any.whl (101 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 101.8/101.8 kB 1.2 MB/s eta 0:00:00
Collecting xlrd==2.0.1 (from -r requirements.txt (line 14))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a6/0c/c2a72d51fe56e08a08acc85d13013558a2d793028ae7385448a6ccdfae64/xlrd-2.0.1-py2.py3-none-any.whl (96 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 96.5/96.5 kB 1.4 MB/s eta 0:00:00
Collecting openpyxl==3.1.2 (from -r requirements.txt (line 15))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/6a/94/a59521de836ef0da54aaf50da6c4da8fb4072fb3053fa71f052fd9399e7a/openpyxl-3.1.2-py2.py3-none-any.whl (249 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 250.0/250.0 kB 1.4 MB/s eta 0:00:00
Collecting unstructured==0.12.6 (from -r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/11/f5/3dee27e6aa8ae4dea1d9ff3574f1e676c15a11510f9b6246eec68d0b7a69/unstructured-0.12.6-py3-none-any.whl (1.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.8/1.8 MB 1.3 MB/s eta 0:00:00
Collecting psutil==5.9.8 (from -r requirements.txt (line 17))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/93/52/3e39d26feae7df0aa0fd510b14012c3678b36ed068f7d78b8d8784d61f0e/psutil-5.9.8-cp37-abi3-win_amd64.whl (255 kB)
Collecting PySide6==6.6.2 (from -r requirements.txt (line 18))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/0c/e3/2a7155a4f776b50f88add0af1e6af2c976e5819ab4fb375cb811157aacd5/PySide6-6.6.2-cp38-abi3-win_amd64.whl (519 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 519.0/519.0 kB 1.2 MB/s eta 0:00:00
Collecting PyAudio==0.2.14 (from -r requirements.txt (line 19))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/82/d8/f043c854aad450a76e476b0cf9cda1956419e1dacf1062eb9df3c0055abe/PyAudio-0.2.14-cp311-cp311-win_amd64.whl (164 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 164.1/164.1 kB 1.2 MB/s eta 0:00:00
Collecting av==12.0.0 (from -r requirements.txt (line 20))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/8a/51/0e5f5e31d834061f5b17ebf53570539f8ad124412b3dbdd5d138f36721a0/av-12.0.0-cp311-cp311-win_amd64.whl (26.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 26.3/26.3 MB 1.4 MB/s eta 0:00:00
Collecting termcolor==2.4.0 (from -r requirements.txt (line 21))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/d9/5f/8c716e47b3a50cbd7c146f45881e11d9414def768b7cd9c5e6650ec2a80a/termcolor-2.4.0-py3-none-any.whl (7.7 kB)
Collecting pypandoc==1.13 (from -r requirements.txt (line 22))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/fc/09/91ab02feebc195a39ce0a39edcafbe866e69ff700a59790e605b3d5f69b1/pypandoc-1.13-py3-none-any.whl (21 kB)
Requirement already satisfied: PyYAML==6.0.1 in c:\users\xxz\appdata\roaming\python\python311\site-packages (from -r requirements.txt (line 23)) (6.0.1)
Collecting Markdown==3.6 (from -r requirements.txt (line 24))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/fc/b3/0c0c994fe49cd661084f8d5dc06562af53818cc0abefaca35bdc894577c3/Markdown-3.6-py3-none-any.whl (105 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 105.4/105.4 kB 1.0 MB/s eta 0:00:00
Collecting transformers==4.39.3 (from -r requirements.txt (line 25))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/15/fc/7b6dd7e1adc0a6407b845ed4be1999e98b6917d0694e57316d140cc85484/transformers-4.39.3-py3-none-any.whl (8.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.8/8.8 MB 1.4 MB/s eta 0:00:00
Collecting accelerate==0.28.0 (from -r requirements.txt (line 26))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a0/11/9bfcf765e71a2c84bbf715719ba520aeacb2ad84113f14803ff1947ddf69/accelerate-0.28.0-py3-none-any.whl (290 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 290.1/290.1 kB 1.1 MB/s eta 0:00:00
Collecting optimum==1.18.0 (from -r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/0a/f4/2163017f8b7690f00d183ff27a02a8cdbeb9c2a5a370a27445786e95d6fb/optimum-1.18.0-py3-none-any.whl (409 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 409.9/409.9 kB 1.3 MB/s eta 0:00:00
Collecting einops==0.7.0 (from -r requirements.txt (line 28))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/29/0b/2d1c0ebfd092e25935b86509a9a817159212d82aa43d7fb07eca4eeff2c2/einops-0.7.0-py3-none-any.whl (44 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 44.6/44.6 kB 440.5 kB/s eta 0:00:00
Collecting scipy==1.12.0 (from -r requirements.txt (line 29))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/9a/25/5b30cb3efc9566f0ebeaeca1976150316353c17031ad7868ef46de5ab8dc/scipy-1.12.0-cp311-cp311-win_amd64.whl (46.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 46.2/46.2 MB 1.3 MB/s eta 0:00:00
Collecting timm==0.9.16 (from -r requirements.txt (line 30))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/68/99/2018622d268f6017ddfa5ee71f070bad5d07590374793166baa102849d17/timm-0.9.16-py3-none-any.whl (2.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.2/2.2 MB 1.3 MB/s eta 0:00:00
Collecting sounddevice==0.4.6 (from -r requirements.txt (line 31))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/39/ae/5e84220bfca4256e4ca2a62a174636089ab6ff671b5f9ddd7e8238587acd/sounddevice-0.4.6-py3-none-win_amd64.whl (199 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 199.7/199.7 kB 1.2 MB/s eta 0:00:00
Requirement already satisfied: platformdirs==4.2.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from -r requirements.txt (line 35)) (4.2.0)
Collecting rich==13.7.1 (from -r requirements.txt (line 36))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/87/67/a37f6214d0e9fe57f6ae54b2956d550ca8365857f42a1ce0392bb21d9410/rich-13.7.1-py3-none-any.whl (240 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 240.7/240.7 kB 1.2 MB/s eta 0:00:00
Collecting openai-whisper==20231117 (from -r requirements.txt (line 37))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/d2/6e/50ace2bf704e5ffc786d20d96403ab0d57c5d6ab8729de7fed8c436687df/openai-whisper-20231117.tar.gz (798 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 798.6/798.6 kB 1.3 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... done
Requirement already satisfied: anyio<5,>=3.5.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (4.3.0)
Requirement already satisfied: distro<2,>=1.7.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (1.9.0)
Requirement already satisfied: httpx<1,>=0.23.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (0.27.0)
Requirement already satisfied: pydantic<3,>=1.9.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (2.7.0)
Requirement already satisfied: sniffio in c:\users\xxz\appdata\roaming\python\python311\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (1.3.1)
Requirement already satisfied: tqdm>4 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (4.66.2)
Requirement already satisfied: typing-extensions<5,>=4.7 in c:\users\xxz\appdata\roaming\python\python311\site-packages (from openai==1.14.3->-r requirements.txt (line 1)) (4.9.0)
Requirement already satisfied: SQLAlchemy<3,>=1.4 in c:\users\xxz\appdata\roaming\python\python311\site-packages (from langchain==0.1.14->-r requirements.txt (line 2)) (2.0.27)
Collecting aiohttp<4.0.0,>=3.8.3 (from langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a4/69/0d415c6d8450842652ce01b29f43416a0f30122b75899de01485623c7850/aiohttp-3.9.5-cp311-cp311-win_amd64.whl (370 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 370.8/370.8 kB 1.2 MB/s eta 0:00:00
Collecting dataclasses-json<0.7,>=0.5.7 (from langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/91/ca/7219b838086086972e662c19e908694bdc6744537fb41b70392501b8b5e4/dataclasses_json-0.6.4-py3-none-any.whl (28 kB)
Collecting jsonpatch<2.0,>=1.33 (from langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/73/07/02e16ed01e04a374e644b575638ec7987ae846d25ad97bcc9945a3ee4b0e/jsonpatch-1.33-py2.py3-none-any.whl (12 kB)
Collecting langchain-core<0.2.0,>=0.1.37 (from langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/31/a9/77dbfa21d7fa97c2927857f6c0cd2bcf143c5a2a92ce14ff2ba0276e89dd/langchain_core-0.1.45-py3-none-any.whl (291 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 291.3/291.3 kB 1.1 MB/s eta 0:00:00
Collecting langchain-text-splitters<0.1,>=0.0.1 (from langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/9d/a1/aec824080111e9b4a4802b51b988032faa193828c865e11233d1b18e88fa/langchain_text_splitters-0.0.1-py3-none-any.whl (21 kB)
Collecting langsmith<0.2.0,>=0.1.17 (from langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/e2/ab/5aee4bceabd5ebc5a6c855f1850d320ecc955fb6bb54a197a1319152be9b/langsmith-0.1.50-py3-none-any.whl (115 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 115.5/115.5 kB 1.1 MB/s eta 0:00:00
Requirement already satisfied: numpy<2,>=1 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from langchain==0.1.14->-r requirements.txt (line 2)) (1.26.3)
Requirement already satisfied: requests<3,>=2 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from langchain==0.1.14->-r requirements.txt (line 2)) (2.25.1)
Requirement already satisfied: tenacity<9.0.0,>=8.1.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from langchain==0.1.14->-r requirements.txt (line 2)) (8.2.3)
Requirement already satisfied: setuptools in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from ctranslate2==4.1.0->-r requirements.txt (line 4)) (68.2.2)
Collecting packaging (from tiledb==0.27.1->-r requirements.txt (line 5))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/49/df/1fceb2f8900f8639e278b056416d49134fb8d84c5942ffaa01ad34782422/packaging-24.0-py3-none-any.whl (53 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 53.5/53.5 kB 554.5 kB/s eta 0:00:00
Collecting tiledb-cloud>=0.11 (from tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/98/79/666ae6addbc6d2fc572b6267da55d2479209f992d038d6c3cdec82f7b67d/tiledb_cloud-0.12.6-py3-none-any.whl (700 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 701.0/701.0 kB 1.2 MB/s eta 0:00:00
Collecting scikit-learn (from tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/79/3d/02d5d3ed359498fec3abdf65407d3c07e3b8765af17464969055aaec5171/scikit_learn-1.4.2-cp311-cp311-win_amd64.whl (10.6 MB)
Collecting PyMuPDFb==1.24.0 (from PyMuPDF==1.24->-r requirements.txt (line 7))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/db/de/b71bf2d7119ddf92583f5104bedb92ee106727b6548829dbd4baa5258310/PyMuPDFb-1.24.0-py3-none-win_amd64.whl (24.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 24.9/24.9 MB 1.3 MB/s eta 0:00:00
Requirement already satisfied: torch>=1.11.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from sentence-transformers==2.6.1->-r requirements.txt (line 9)) (2.3.0+cu121)
Collecting huggingface-hub>=0.15.1 (from sentence-transformers==2.6.1->-r requirements.txt (line 9))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/05/c0/779afbad8e75565c09ffa24a88b5dd7e293c92b74eb09df6435fc58ac986/huggingface_hub-0.22.2-py3-none-any.whl (388 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 388.9/388.9 kB 1.3 MB/s eta 0:00:00
Requirement already satisfied: Pillow in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from sentence-transformers==2.6.1->-r requirements.txt (line 9)) (9.4.0)
Collecting python-dateutil>=2.8.2 (from pandas==2.2.1->-r requirements.txt (line 10))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/ec/57/56b9bcc3c9c6a792fcbaf139543cee77261f3651ca9da0c93f5c1221264b/python_dateutil-2.9.0.post0-py2.py3-none-any.whl (229 kB)
Requirement already satisfied: pytz>=2020.1 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from pandas==2.2.1->-r requirements.txt (line 10)) (2024.1)
Collecting tzdata>=2022.7 (from pandas==2.2.1->-r requirements.txt (line 10))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/65/58/f9c9e6be752e9fcb8b6a0ee9fb87e6e7a1f6bcab2cdc73f02bb7ba91ada0/tzdata-2024.1-py2.py3-none-any.whl (345 kB)
Requirement already satisfied: lxml>=3.1.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from python-docx==1.1.0->-r requirements.txt (line 12)) (4.9.2)
Collecting olefile>=0.46 (from msg-parser==1.2.0->-r requirements.txt (line 13))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/17/d3/b64c356a907242d719fc668b71befd73324e47ab46c8ebbbede252c154b2/olefile-0.47-py2.py3-none-any.whl (114 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 114.6/114.6 kB 1.1 MB/s eta 0:00:00
Collecting et-xmlfile (from openpyxl==3.1.2->-r requirements.txt (line 15))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/96/c2/3dd434b0108730014f1b96fd286040dc3bcb70066346f7e01ec2ac95865f/et_xmlfile-1.1.0-py3-none-any.whl (4.7 kB)
Collecting backoff==2.2.1 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/df/73/b6e24bd22e6720ca8ee9a85a0c4a2971af8497d8f3193fa05390cbd46e09/backoff-2.2.1-py3-none-any.whl (15 kB)
Requirement already satisfied: beautifulsoup4==4.12.3 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from unstructured==0.12.6->-r requirements.txt (line 16)) (4.12.3)
Requirement already satisfied: certifi==2024.2.2 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from unstructured==0.12.6->-r requirements.txt (line 16)) (2024.2.2)
Collecting chardet==5.2.0 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/38/6f/f5fbc992a329ee4e0f288c1fe0e2ad9485ed064cac731ed2fe47dcc38cbf/chardet-5.2.0-py3-none-any.whl (199 kB)
Collecting charset-normalizer==3.3.2 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/57/ec/80c8d48ac8b1741d5b963797b7c0c869335619e13d4744ca2f67fc11c6fc/charset_normalizer-3.3.2-cp311-cp311-win_amd64.whl (99 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 99.9/99.9 kB 1.4 MB/s eta 0:00:00
Collecting click==8.1.7 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/00/2e/d53fa4befbf2cfa713304affc7ca780ce4fc1fd8710527771b58311a3229/click-8.1.7-py3-none-any.whl (97 kB)
Collecting dataclasses-json-speakeasy==0.5.11 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/57/5b/2002d3da4fc37c567287cd89fb08b43c1fb130ce0d757bd3e8f61b1a1f94/dataclasses_json_speakeasy-0.5.11-py3-none-any.whl (28 kB)
Collecting emoji==2.10.1 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/98/00/00d56e704d69cee4a92b1d517676579b4af5f2f8bc72946c464a504705b2/emoji-2.10.1-py2.py3-none-any.whl (421 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 421.5/421.5 kB 1.4 MB/s eta 0:00:00
Collecting filetype==1.2.0 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/18/79/1b8fa1bb3568781e84c9200f951c735f3f157429f44be0495da55894d620/filetype-1.2.0-py2.py3-none-any.whl (19 kB)
Collecting idna==3.6 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/c2/e7/a82b05cf63a603df6e68d59ae6a68bf5064484a0718ea5033660af4b54a9/idna-3.6-py3-none-any.whl (61 kB)
Collecting joblib==1.3.2 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/10/40/d551139c85db202f1f384ba8bcf96aca2f329440a844f924c8a0040b6d02/joblib-1.3.2-py3-none-any.whl (302 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 302.2/302.2 kB 1.3 MB/s eta 0:00:00
Collecting jsonpath-python==1.0.6 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/16/8a/d63959f4eff03893a00e6e63592e3a9f15b9266ed8e0275ab77f8c7dbc94/jsonpath_python-1.0.6-py3-none-any.whl (7.6 kB)
Collecting langdetect==1.0.9 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/0e/72/a3add0e4eec4eb9e2569554f7c70f4a3c27712f40e3284d483e88094cc0e/langdetect-1.0.9.tar.gz (981 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 981.5/981.5 kB 1.4 MB/s eta 0:00:00
  Preparing metadata (setup.py) ... done
Collecting lxml>=3.1.0 (from python-docx==1.1.0->-r requirements.txt (line 12))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/5b/d6/e794d996dec76b773691af78390fe2f419ab7cb5b78a4df982e21ae655b7/lxml-5.1.0-cp311-cp311-win_amd64.whl (3.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.9/3.9 MB 1.4 MB/s eta 0:00:00
Collecting marshmallow==3.20.2 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/57/e9/4368d49d3b462da16a3bac976487764a84dd85cef97232c7bd61f5bdedf3/marshmallow-3.20.2-py3-none-any.whl (49 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 49.4/49.4 kB 622.4 kB/s eta 0:00:00
Collecting mypy-extensions==1.0.0 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/2a/e2/5d3f6ada4297caebe1a2add3b126fe800c96f56dbe5d1988a2cbe0b267aa/mypy_extensions-1.0.0-py3-none-any.whl (4.7 kB)
Collecting nltk==3.8.1 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a6/0a/0d20d2c0f16be91b9fa32a77b76c60f9baf6eba419e5ef5deca17af9c582/nltk-3.8.1-py3-none-any.whl (1.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.5/1.5 MB 1.3 MB/s eta 0:00:00
Collecting numpy<2,>=1 (from langchain==0.1.14->-r requirements.txt (line 2))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/3f/6b/5610004206cf7f8e7ad91c5a85a8c71b2f2f8051a0c0c4d5916b76d6cbb2/numpy-1.26.4-cp311-cp311-win_amd64.whl (15.8 MB)
Collecting packaging (from tiledb==0.27.1->-r requirements.txt (line 5))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/ec/1a/610693ac4ee14fcdf2d9bf3c493370e4f2ef7ae2e19217d7a237ff42367d/packaging-23.2-py3-none-any.whl (53 kB)
Collecting python-dateutil>=2.8.2 (from pandas==2.2.1->-r requirements.txt (line 10))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/36/7a/87837f39d0296e723bb9b62bbb257d0355c7f6128853c78955f57342a56d/python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting python-iso639==2024.2.7 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/01/62/2fed44ba10fe805345fb0e9c46c7f8dcdaf1bffd642f051fcc3db9bf55d8/python_iso639-2024.2.7-py3-none-any.whl (274 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 274.7/274.7 kB 1.3 MB/s eta 0:00:00
Collecting python-magic==0.4.27 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/6c/73/9f872cb81fc5c3bb48f7227872c28975f998f3e7c2b1c16e95e6432bbb90/python_magic-0.4.27-py2.py3-none-any.whl (13 kB)
Collecting rapidfuzz==3.6.1 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/fa/a9/0bcd4017323d40cec6fc1639eddae1f90b5e080be0c62eb34670b69aa009/rapidfuzz-3.6.1-cp311-cp311-win_amd64.whl (1.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 1.3 MB/s eta 0:00:00
Collecting regex==2023.12.25 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a8/01/18232f93672c1d530834e2e0568a80eaab1df12d67ae499b1762ab462b5c/regex-2023.12.25-cp311-cp311-win_amd64.whl (269 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 269.5/269.5 kB 1.3 MB/s eta 0:00:00
Collecting requests<3,>=2 (from langchain==0.1.14->-r requirements.txt (line 2))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/70/8e/0e2d847013cb52cd35b38c009bb167a1a26b2ce6cd6965bf26b47bc0bf44/requests-2.31.0-py3-none-any.whl (62 kB)
Requirement already satisfied: six==1.16.0 in c:\users\xxz\appdata\roaming\python\python311\site-packages (from unstructured==0.12.6->-r requirements.txt (line 16)) (1.16.0)
Requirement already satisfied: soupsieve==2.5 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from unstructured==0.12.6->-r requirements.txt (line 16)) (2.5)
Collecting tabulate==0.9.0 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/40/44/4a5f08c96eb108af5cb50b41f76142f0afa346dfa99d5296fe7202a11854/tabulate-0.9.0-py3-none-any.whl (35 kB)
Collecting typing-inspect==0.9.0 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/65/f3/107a22063bf27bdccf2024833d3445f4eea42b2e598abfbd46f6a63b6cb0/typing_inspect-0.9.0-py3-none-any.whl (8.8 kB)
Collecting unstructured-client==0.18.0 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a6/07/6e0fba885472decf691bb70818858c7996e0509d55c5001546e967614301/unstructured_client-0.18.0-py3-none-any.whl (21 kB)
Collecting urllib3==1.26.18 (from unstructured==0.12.6->-r requirements.txt (line 16))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/b0/53/aa91e163dcfd1e5b82d8a890ecf13314e3e149c05270cc644581f77f17fd/urllib3-1.26.18-py2.py3-none-any.whl (143 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 143.8/143.8 kB 1.1 MB/s eta 0:00:00
Requirement already satisfied: wrapt==1.16.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from unstructured==0.12.6->-r requirements.txt (line 16)) (1.16.0)
Collecting shiboken6==6.6.2 (from PySide6==6.6.2->-r requirements.txt (line 18))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/74/46/00f867c025018148487a1138209513fbd4dcbae70faed052b027499f9c56/shiboken6-6.6.2-cp38-abi3-win_amd64.whl (1.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 1.4 MB/s eta 0:00:00
Collecting PySide6-Essentials==6.6.2 (from PySide6==6.6.2->-r requirements.txt (line 18))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a0/08/eaa29a1e01c13241aacab6bfcf15cf49ae026abeaa1dafc018b42909dbb1/PySide6_Essentials-6.6.2-cp38-abi3-win_amd64.whl (77.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 77.2/77.2 MB 1.2 MB/s eta 0:00:00
Collecting PySide6-Addons==6.6.2 (from PySide6==6.6.2->-r requirements.txt (line 18))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/75/06/97aabf6fe31413616ff9d4165db4802e9991a97eaa04250e731a6cc5d6ab/PySide6_Addons-6.6.2-cp38-abi3-win_amd64.whl (110.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 110.8/110.8 MB 1.2 MB/s eta 0:00:00
Requirement already satisfied: filelock in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from transformers==4.39.3->-r requirements.txt (line 25)) (3.13.1)
Collecting tokenizers<0.19,>=0.14 (from transformers==4.39.3->-r requirements.txt (line 25))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/c1/02/40725eebedea8175918bd59ab80b2174d6ef3b3ef9ac8ec996e84c38d3ca/tokenizers-0.15.2-cp311-none-win_amd64.whl (2.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.2/2.2 MB 1.3 MB/s eta 0:00:00
Collecting safetensors>=0.4.1 (from transformers==4.39.3->-r requirements.txt (line 25))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/cb/f6/19f268662be898ff2a23ac06f8dd0d2956b2ecd204c96e1ee07ba292c119/safetensors-0.4.3-cp311-none-win_amd64.whl (287 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 287.3/287.3 kB 1.4 MB/s eta 0:00:00
Collecting coloredlogs (from optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a7/06/3d6badcf13db419e25b07041d9c7b4a2c331d3f4e7134445ec5df57714cd/coloredlogs-15.0.1-py2.py3-none-any.whl (46 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 46.0/46.0 kB 761.2 kB/s eta 0:00:00
Requirement already satisfied: sympy in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from optimum==1.18.0->-r requirements.txt (line 27)) (1.12)
Collecting datasets (from optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/89/a9/8e097f79d2941a2f96e33f57032957429a79f66c8252ac7fcce586a43406/datasets-2.19.0-py3-none-any.whl (542 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 542.0/542.0 kB 1.5 MB/s eta 0:00:00
Requirement already satisfied: torchvision in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from timm==0.9.16->-r requirements.txt (line 30)) (0.18.0+cu121)
Requirement already satisfied: CFFI>=1.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from sounddevice==0.4.6->-r requirements.txt (line 31)) (1.16.0)
Collecting markdown-it-py>=2.2.0 (from rich==13.7.1->-r requirements.txt (line 36))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/42/d7/1ec15b46af6af88f19b8e5ffea08fa375d433c998b8a7639e76935c14f1f/markdown_it_py-3.0.0-py3-none-any.whl (87 kB)
Collecting pygments<3.0.0,>=2.13.0 (from rich==13.7.1->-r requirements.txt (line 36))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/97/9c/372fef8377a6e340b1704768d20daaded98bf13282b5327beb2e2fe2c7ef/pygments-2.17.2-py3-none-any.whl (1.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 1.3 MB/s eta 0:00:00
Collecting numba (from openai-whisper==20231117->-r requirements.txt (line 37))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/38/f0/ad848815b0adafcf5f238e728933950034355a8d59969772be1cd57606d8/numba-0.59.1-cp311-cp311-win_amd64.whl (2.6 MB)
Collecting more-itertools (from openai-whisper==20231117->-r requirements.txt (line 37))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/50/e2/8e10e465ee3987bb7c9ab69efb91d867d93959095f4807db102d07995d94/more_itertools-10.2.0-py3-none-any.whl (57 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 57.0/57.0 kB 599.7 kB/s eta 0:00:00
Collecting tiktoken (from openai-whisper==20231117->-r requirements.txt (line 37))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/69/ca/0a71c1cdbf36da977bd306d295042087187954c32bfa259fa7afede0608b/tiktoken-0.6.0-cp311-cp311-win_amd64.whl (798 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 798.7/798.7 kB 1.4 MB/s eta 0:00:00
Requirement already satisfied: colorama in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from click==8.1.7->unstructured==0.12.6->-r requirements.txt (line 16)) (0.4.6)
Collecting aiosignal>=1.1.2 (from aiohttp<4.0.0,>=3.8.3->langchain==0.1.14->-r requirements.txt (line 2))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/76/ac/a7305707cb852b7e16ff80eaf5692309bde30e2b1100a1fcacdc8f731d97/aiosignal-1.3.1-py3-none-any.whl (7.6 kB)
Requirement already satisfied: attrs>=17.3.0 in c:\users\xxz\appdata\roaming\python\python311\site-packages (from aiohttp<4.0.0,>=3.8.3->langchain==0.1.14->-r requirements.txt (line 2)) (23.2.0)
Collecting frozenlist>=1.1.1 (from aiohttp<4.0.0,>=3.8.3->langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/b3/21/c5aaffac47fd305d69df46cfbf118768cdf049a92ee6b0b5cb029d449dcf/frozenlist-1.4.1-cp311-cp311-win_amd64.whl (50 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 50.5/50.5 kB 855.7 kB/s eta 0:00:00
Collecting multidict<7.0,>=4.5 (from aiohttp<4.0.0,>=3.8.3->langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/88/aa/ea217cb18325aa05cb3e3111c19715f1e97c50a4a900cbc20e54648de5f5/multidict-6.0.5-cp311-cp311-win_amd64.whl (28 kB)
Collecting yarl<2.0,>=1.0 (from aiohttp<4.0.0,>=3.8.3->langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/27/41/945ae9a80590e4fb0be166863c6e63d75e4b35789fa3a61ff1dbdcdc220f/yarl-1.9.4-cp311-cp311-win_amd64.whl (76 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 76.7/76.7 kB 1.1 MB/s eta 0:00:00
Requirement already satisfied: pycparser in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from CFFI>=1.0->sounddevice==0.4.6->-r requirements.txt (line 31)) (2.22)
Requirement already satisfied: httpcore==1.* in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from httpx<1,>=0.23.0->openai==1.14.3->-r requirements.txt (line 1)) (1.0.5)
Requirement already satisfied: h11<0.15,>=0.13 in c:\users\xxz\appdata\roaming\python\python311\site-packages (from httpcore==1.*->httpx<1,>=0.23.0->openai==1.14.3->-r requirements.txt (line 1)) (0.14.0)
Requirement already satisfied: fsspec>=2023.5.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from huggingface-hub>=0.15.1->sentence-transformers==2.6.1->-r requirements.txt (line 9)) (2024.2.0)
Collecting jsonpointer>=1.9 (from jsonpatch<2.0,>=1.33->langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/12/f6/0232cc0c617e195f06f810534d00b74d2f348fe71b2118009ad8ad31f878/jsonpointer-2.4-py2.py3-none-any.whl (7.8 kB)
Collecting orjson<4.0.0,>=3.9.14 (from langsmith<0.2.0,>=0.1.17->langchain==0.1.14->-r requirements.txt (line 2))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/28/f2/62bdd14f712fbc36afb3e3885abf88b6804324d8ad074f9431adb7d702ab/orjson-3.10.1-cp311-none-win_amd64.whl (139 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 139.1/139.1 kB 1.0 MB/s eta 0:00:00
Collecting mdurl~=0.1 (from markdown-it-py>=2.2.0->rich==13.7.1->-r requirements.txt (line 36))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/b3/38/89ba8ad64ae25be8de66a6d463314cf1eb366222074cfda9ee839c56a4b4/mdurl-0.1.2-py3-none-any.whl (10.0 kB)
Requirement already satisfied: annotated-types>=0.4.0 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from pydantic<3,>=1.9.0->openai==1.14.3->-r requirements.txt (line 1)) (0.6.0)
Requirement already satisfied: pydantic-core==2.18.1 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from pydantic<3,>=1.9.0->openai==1.14.3->-r requirements.txt (line 1)) (2.18.1)
Requirement already satisfied: greenlet!=0.4.17 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from SQLAlchemy<3,>=1.4->langchain==0.1.14->-r requirements.txt (line 2)) (2.0.2)
Collecting cloudpickle<3,>=1.4.1 (from tiledb-cloud>=0.11->tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/15/80/44286939ca215e88fa827b2aeb6fa3fd2b4a7af322485c7170d6f9fd96e0/cloudpickle-2.2.1-py3-none-any.whl (25 kB)
Collecting importlib-metadata (from tiledb-cloud>=0.11->tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/2d/0a/679461c511447ffaf176567d5c496d1de27cbe34a87df6677d7171b2fbd4/importlib_metadata-7.1.0-py3-none-any.whl (24 kB)
Collecting pyarrow>=3.0.0 (from tiledb-cloud>=0.11->tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/51/e6/83d51c9822ea0232548f73e39bc25e9a4b658422100d5b23d7abc9e871b0/pyarrow-16.0.0-cp311-cp311-win_amd64.whl (25.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 25.9/25.9 MB 1.3 MB/s eta 0:00:00
Collecting tblib~=1.7 (from tiledb-cloud>=0.11->tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/f8/cd/2fad4add11c8837e72f50a30e2bda30e67a10d70462f826b291443a55c7d/tblib-1.7.0-py2.py3-none-any.whl (12 kB)
Requirement already satisfied: networkx in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from torch>=1.11.0->sentence-transformers==2.6.1->-r requirements.txt (line 9)) (3.2.1)
Requirement already satisfied: jinja2 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from torch>=1.11.0->sentence-transformers==2.6.1->-r requirements.txt (line 9)) (3.1.2)
Requirement already satisfied: mkl<=2021.4.0,>=2021.1.1 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from torch>=1.11.0->sentence-transformers==2.6.1->-r requirements.txt (line 9)) (2021.4.0)
Collecting sentencepiece!=0.1.92,>=0.1.91 (from transformers[sentencepiece]<4.40.0,>=4.26.0->optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/a2/f6/587c62fd21fc988555b85351f50bbde43a51524caafd63bc69240ded14fd/sentencepiece-0.2.0-cp311-cp311-win_amd64.whl (991 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 991.5/991.5 kB 1.2 MB/s eta 0:00:00
Requirement already satisfied: protobuf in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from transformers[sentencepiece]<4.40.0,>=4.26.0->optimum==1.18.0->-r requirements.txt (line 27)) (4.25.3)
Collecting humanfriendly>=9.1 (from coloredlogs->optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/f0/0f/310fb31e39e2d734ccaa2c0fb981ee41f7bd5056ce9bc29b2248bd569169/humanfriendly-10.0-py2.py3-none-any.whl (86 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 86.8/86.8 kB 1.2 MB/s eta 0:00:00
Collecting pyarrow-hotfix (from datasets->optimum==1.18.0->-r requirements.txt (line 27))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/e4/f4/9ec2222f5f5f8ea04f66f184caafd991a39c8782e31f5b0266f101cb68ca/pyarrow_hotfix-0.6-py3-none-any.whl (7.9 kB)
Collecting dill<0.3.9,>=0.3.0 (from datasets->optimum==1.18.0->-r requirements.txt (line 27))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/c9/7a/cef76fd8438a42f96db64ddaa85280485a9c395e7df3db8158cfec1eee34/dill-0.3.8-py3-none-any.whl (116 kB)
Collecting xxhash (from datasets->optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/b7/3a/74a609706ef4430fe6d041a3b8d209882c15440b695e373fe26d48c6f35c/xxhash-3.4.1-cp311-cp311-win_amd64.whl (29 kB)
Collecting multiprocess (from datasets->optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/50/15/b56e50e8debaf439f44befec5b2af11db85f6e0f344c3113ae0be0593a91/multiprocess-0.70.16-py311-none-any.whl (143 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 143.5/143.5 kB 1.2 MB/s eta 0:00:00
Collecting llvmlite<0.43,>=0.42.0dev0 (from numba->openai-whisper==20231117->-r requirements.txt (line 37))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/f3/bd/3b27a1c8bbbe01b053f5e0c9ca9a37dbc3e39282dfcf596d143ad389f156/llvmlite-0.42.0-cp311-cp311-win_amd64.whl (28.1 MB)
Collecting threadpoolctl>=2.0.0 (from scikit-learn->tiledb-vector-search==0.2.0->-r requirements.txt (line 6))
  Using cached https://pypi.tuna.tsinghua.edu.cn/packages/1e/84/ccd9b08653022b7785b6e3ee070ffb2825841e0dc119be22f0840b2b35cb/threadpoolctl-3.4.0-py3-none-any.whl (17 kB)
Requirement already satisfied: mpmath>=0.19 in c:\users\xxz\.conda\envs\zen17\lib\site-packages (from sympy->optimum==1.18.0->-r requirements.txt (line 27)) (1.3.0)
Collecting pyreadline3 (from humanfriendly>=9.1->coloredlogs->optimum==1.18.0->-r requirements.txt (line 27))
  Downloading https://pypi.tuna.tsinghua.edu.cn/packages/56/fc/a3c13ded7b3057680c8ae95a9b6cc83e63657c38e0005c400a5d018a33a7/pyreadline3-3.4.1-py3-none-any.whl (95 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 95.2/95.2 kB 1.3 MB/s eta 0:00:00