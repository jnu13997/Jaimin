(frankmocap) C:\Mocap\Frankmocap>install_win_full_body.bat

(frankmocap) C:\Mocap\Frankmocap>rem ####### installing files pre packed

(frankmocap) C:\Mocap\Frankmocap>REM pip install whl/faster_rcnn-0.1-cp37-cp37m-win_amd64.whl

(frankmocap) C:\Mocap\Frankmocap>pip install whl/detectron2-0.3-cp37-cp37m-win_amd64.whl
ERROR: detectron2-0.3-cp37-cp37m-win_amd64.whl is not a supported wheel on this platform.

(frankmocap) C:\Mocap\Frankmocap>pip install whl/opendr-0.73-py3-none-any.whl
Processing c:\mocap\frankmocap\whl\opendr-0.73-py3-none-any.whl
Requirement already satisfied: chumpy>=0.58 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from opendr==0.73) (0.70)
Requirement already satisfied: Cython in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from opendr==0.73) (0.29.24)
Requirement already satisfied: matplotlib in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from opendr==0.73) (3.4.2)
Requirement already satisfied: six>=1.11.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from chumpy>=0.58->opendr==0.73) (1.16.0)
Requirement already satisfied: scipy>=0.13.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from chumpy>=0.58->opendr==0.73) (1.7.0)
Requirement already satisfied: numpy<1.23.0,>=1.16.5 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from scipy>=0.13.0->chumpy>=0.58->opendr==0.73) (1.20.2)
Requirement already satisfied: cycler>=0.10 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib->opendr==0.73) (0.10.0)
Requirement already satisfied: pyparsing>=2.2.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib->opendr==0.73) (2.4.7)
Requirement already satisfied: python-dateutil>=2.7 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib->opendr==0.73) (2.8.2)
Requirement already satisfied: kiwisolver>=1.0.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib->opendr==0.73) (1.3.1)
Requirement already satisfied: pillow>=6.2.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib->opendr==0.73) (8.3.1)
opendr is already installed with the same version as the provided wheel. Use --force-reinstall to force an installation of the wheel.

(frankmocap) C:\Mocap\Frankmocap>pip install whl/PyOpenGL-3.1.5-cp37-cp37m-win_amd64.whl
ERROR: PyOpenGL-3.1.5-cp37-cp37m-win_amd64.whl is not a supported wheel on this platform.

(frankmocap) C:\Mocap\Frankmocap>pip install whl/PyOpenGL_accelerate-3.1.5-cp37-cp37m-win_amd64.whl
ERROR: PyOpenGL_accelerate-3.1.5-cp37-cp37m-win_amd64.whl is not a supported wheel on this platform.

(frankmocap) C:\Mocap\Frankmocap>pip install -r requirements_alter.txt
Requirement already satisfied: pip in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 1)) (21.1.3)
Collecting gdown
  Using cached gdown-3.13.0-py3-none-any.whl
Requirement already satisfied: requests in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 3)) (2.26.0)
Collecting gitpython
  Using cached GitPython-3.1.18-py3-none-any.whl (170 kB)
Collecting opencv-python
  Using cached opencv_python-4.5.3.56-cp38-cp38-win_amd64.whl (34.9 MB)
Collecting pycocotools
  Using cached pycocotools-2.0.2.tar.gz (23 kB)
Collecting pafy
  Using cached pafy-0.5.5-py2.py3-none-any.whl (35 kB)
Requirement already satisfied: youtube-dl in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 8)) (2021.6.6)
Requirement already satisfied: scipy in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 9)) (1.7.0)
Requirement already satisfied: pillow>=7.1.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 10)) (8.3.1)
Collecting easydict
  Using cached easydict-1.9-py3-none-any.whl
Requirement already satisfied: cython in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 12)) (0.29.24)
Collecting cffi
  Using cached cffi-1.14.6-cp38-cp38-win_amd64.whl (179 kB)
Collecting msgpack
  Using cached msgpack-1.0.2-cp38-cp38-win_amd64.whl (69 kB)
Requirement already satisfied: pyyaml in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 16)) (5.4.1)
Requirement already satisfied: tensorboardX in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 17)) (2.4)
Requirement already satisfied: tqdm in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 18)) (4.61.2)
Collecting jinja2
  Using cached Jinja2-3.0.1-py3-none-any.whl (133 kB)
Requirement already satisfied: smplx in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 20)) (0.1.28)
Requirement already satisfied: sklearn in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 21)) (0.0)
Requirement already satisfied: opendr in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 22)) (0.73)
Requirement already satisfied: chumpy in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from -r requirements_alter.txt (line 23)) (0.70)
Requirement already satisfied: filelock in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from gdown->-r requirements_alter.txt (line 2)) (3.0.12)
Requirement already satisfied: six in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from gdown->-r requirements_alter.txt (line 2)) (1.16.0)
Requirement already satisfied: urllib3<1.27,>=1.21.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from requests->-r requirements_alter.txt (line 3)) (1.26.6)
Requirement already satisfied: charset-normalizer~=2.0.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from requests->-r requirements_alter.txt (line 3)) (2.0.2)
Requirement already satisfied: idna<4,>=2.5 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from requests->-r requirements_alter.txt (line 3)) (3.2)
Requirement already satisfied: certifi>=2017.4.17 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from requests->-r requirements_alter.txt (line 3)) (2021.5.30)
Requirement already satisfied: PySocks!=1.5.7,>=1.5.6 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from requests->-r requirements_alter.txt (line 3)) (1.7.1)
Requirement already satisfied: gitdb<5,>=4.0.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from gitpython->-r requirements_alter.txt (line 4)) (4.0.7)
Requirement already satisfied: smmap<5,>=3.0.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from gitdb<5,>=4.0.1->gitpython->-r requirements_alter.txt (line 4)) (4.0.0)
Requirement already satisfied: numpy>=1.17.3 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from opencv-python->-r requirements_alter.txt (line 5)) (1.20.2)
Requirement already satisfied: setuptools>=18.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from pycocotools->-r requirements_alter.txt (line 6)) (52.0.0.post20210125)
Requirement already satisfied: matplotlib>=2.1.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from pycocotools->-r requirements_alter.txt (line 6)) (3.4.2)
Requirement already satisfied: kiwisolver>=1.0.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib>=2.1.0->pycocotools->-r requirements_alter.txt (line 6)) (1.3.1)
Requirement already satisfied: cycler>=0.10 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib>=2.1.0->pycocotools->-r requirements_alter.txt (line 6)) (0.10.0)
Requirement already satisfied: python-dateutil>=2.7 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib>=2.1.0->pycocotools->-r requirements_alter.txt (line 6)) (2.8.2)
Requirement already satisfied: pyparsing>=2.2.1 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from matplotlib>=2.1.0->pycocotools->-r requirements_alter.txt (line 6)) (2.4.7)
Requirement already satisfied: pycparser in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from cffi->-r requirements_alter.txt (line 13)) (2.20)
Requirement already satisfied: protobuf>=3.8.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from tensorboardX->-r requirements_alter.txt (line 17)) (3.17.3)
Requirement already satisfied: colorama in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from tqdm->-r requirements_alter.txt (line 18)) (0.4.4)
Requirement already satisfied: MarkupSafe>=2.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from jinja2->-r requirements_alter.txt (line 19)) (2.0.1)
Requirement already satisfied: torch>=1.0.1.post2 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from smplx->-r requirements_alter.txt (line 20)) (1.6.0)
Requirement already satisfied: future in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from torch>=1.0.1.post2->smplx->-r requirements_alter.txt (line 20)) (0.18.2)
Requirement already satisfied: scikit-learn in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from sklearn->-r requirements_alter.txt (line 21)) (0.24.2)
Requirement already satisfied: joblib>=0.11 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from scikit-learn->sklearn->-r requirements_alter.txt (line 21)) (1.0.1)
Requirement already satisfied: threadpoolctl>=2.0.0 in c:\users\jaimi\miniconda3\envs\frankmocap\lib\site-packages (from scikit-learn->sklearn->-r requirements_alter.txt (line 21)) (2.2.0)
Building wheels for collected packages: pycocotools
  Building wheel for pycocotools (setup.py) ... error
  ERROR: Command errored out with exit status 1:
   command: 'C:\Users\jaimi\miniconda3\envs\frankmocap\python.exe' -u -c 'import io, os, sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\jaimi\\AppData\\Local\\Temp\\pip-install-7ruenb_3\\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\\setup.py'"'"'; __file__='"'"'C:\\Users\\jaimi\\AppData\\Local\\Temp\\pip-install-7ruenb_3\\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\\setup.py'"'"';f = getattr(tokenize, '"'"'open'"'"', open)(__file__) if os.path.exists(__file__) else io.StringIO('"'"'from setuptools import setup; setup()'"'"');code = f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' bdist_wheel -d 'C:\Users\jaimi\AppData\Local\Temp\pip-wheel-sw01s8bu'
       cwd: C:\Users\jaimi\AppData\Local\Temp\pip-install-7ruenb_3\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\
  Complete output (23 lines):
  running bdist_wheel
  running build
  running build_py
  creating build
  creating build\lib.win-amd64-3.8
  creating build\lib.win-amd64-3.8\pycocotools
  copying pycocotools\coco.py -> build\lib.win-amd64-3.8\pycocotools
  copying pycocotools\cocoeval.py -> build\lib.win-amd64-3.8\pycocotools
  copying pycocotools\mask.py -> build\lib.win-amd64-3.8\pycocotools
  copying pycocotools\__init__.py -> build\lib.win-amd64-3.8\pycocotools
  running build_ext
  cythoning pycocotools/_mask.pyx to pycocotools\_mask.c
  C:\Users\jaimi\miniconda3\envs\frankmocap\lib\site-packages\Cython\Compiler\Main.py:369: FutureWarning: Cython directive 'language_level' not set, using 2 for now (Py2). This will change in a later release! File: C:\Users\jaimi\AppData\Local\Temp\pip-install-7ruenb_3\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\pycocotools\_mask.pyx
    tree = Parsing.p_module(s, pxd, full_module_name)
  building 'pycocotools._mask' extension
  creating build\temp.win-amd64-3.8
  creating build\temp.win-amd64-3.8\Release
  creating build\temp.win-amd64-3.8\Release\common
  creating build\temp.win-amd64-3.8\Release\pycocotools
  C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.16.27023\bin\HostX86\x64\cl.exe /c /nologo /Ox /W3 /GL /DNDEBUG /MD -IC:\Users\jaimi\miniconda3\envs\frankmocap\lib\site-packages\numpy\core\include -I./common -IC:\Users\jaimi\miniconda3\envs\frankmocap\include -IC:\Users\jaimi\miniconda3\envs\frankmocap\include "-IC:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.16.27023\ATLMFC\include" "-IC:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.16.27023\include" /Tc./common/maskApi.c /Fobuild\temp.win-amd64-3.8\Release\./common/maskApi.obj
  maskApi.c
  ./common/maskApi.c(8): fatal error C1083: Cannot open include file: 'math.h': No such file or directory
  error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Community\\VC\\Tools\\MSVC\\14.16.27023\\bin\\HostX86\\x64\\cl.exe' failed with exit status 2
  ----------------------------------------
  ERROR: Failed building wheel for pycocotools
  Running setup.py clean for pycocotools
Failed to build pycocotools
Installing collected packages: pycocotools, pafy, opencv-python, msgpack, jinja2, gitpython, gdown, easydict, cffi
    Running setup.py install for pycocotools ... error
    ERROR: Command errored out with exit status 1:
     command: 'C:\Users\jaimi\miniconda3\envs\frankmocap\python.exe' -u -c 'import io, os, sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\jaimi\\AppData\\Local\\Temp\\pip-install-7ruenb_3\\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\\setup.py'"'"'; __file__='"'"'C:\\Users\\jaimi\\AppData\\Local\\Temp\\pip-install-7ruenb_3\\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\\setup.py'"'"';f = getattr(tokenize, '"'"'open'"'"', open)(__file__) if os.path.exists(__file__) else io.StringIO('"'"'from setuptools import setup; setup()'"'"');code = f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\jaimi\AppData\Local\Temp\pip-record-7kg6nb2d\install-record.txt' --single-version-externally-managed --compile --install-headers 'C:\Users\jaimi\miniconda3\envs\frankmocap\Include\pycocotools'
         cwd: C:\Users\jaimi\AppData\Local\Temp\pip-install-7ruenb_3\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\
    Complete output (21 lines):
    running install
    running build
    running build_py
    creating build
    creating build\lib.win-amd64-3.8
    creating build\lib.win-amd64-3.8\pycocotools
    copying pycocotools\coco.py -> build\lib.win-amd64-3.8\pycocotools
    copying pycocotools\cocoeval.py -> build\lib.win-amd64-3.8\pycocotools
    copying pycocotools\mask.py -> build\lib.win-amd64-3.8\pycocotools
    copying pycocotools\__init__.py -> build\lib.win-amd64-3.8\pycocotools
    running build_ext
    skipping 'pycocotools\_mask.c' Cython extension (up-to-date)
    building 'pycocotools._mask' extension
    creating build\temp.win-amd64-3.8
    creating build\temp.win-amd64-3.8\Release
    creating build\temp.win-amd64-3.8\Release\common
    creating build\temp.win-amd64-3.8\Release\pycocotools
    C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.16.27023\bin\HostX86\x64\cl.exe /c /nologo /Ox /W3 /GL /DNDEBUG /MD -IC:\Users\jaimi\miniconda3\envs\frankmocap\lib\site-packages\numpy\core\include -I./common -IC:\Users\jaimi\miniconda3\envs\frankmocap\include -IC:\Users\jaimi\miniconda3\envs\frankmocap\include "-IC:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.16.27023\ATLMFC\include" "-IC:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Tools\MSVC\14.16.27023\include" /Tc./common/maskApi.c /Fobuild\temp.win-amd64-3.8\Release\./common/maskApi.obj
    maskApi.c
    ./common/maskApi.c(8): fatal error C1083: Cannot open include file: 'math.h': No such file or directory
    error: command 'C:\\Program Files (x86)\\Microsoft Visual Studio\\2017\\Community\\VC\\Tools\\MSVC\\14.16.27023\\bin\\HostX86\\x64\\cl.exe' failed with exit status 2
    ----------------------------------------
ERROR: Command errored out with exit status 1: 'C:\Users\jaimi\miniconda3\envs\frankmocap\python.exe' -u -c 'import io, os, sys, setuptools, tokenize; sys.argv[0] = '"'"'C:\\Users\\jaimi\\AppData\\Local\\Temp\\pip-install-7ruenb_3\\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\\setup.py'"'"'; __file__='"'"'C:\\Users\\jaimi\\AppData\\Local\\Temp\\pip-install-7ruenb_3\\pycocotools_2f1cd581030c4a0fb833e192c4864ad1\\setup.py'"'"';f = getattr(tokenize, '"'"'open'"'"', open)(__file__) if os.path.exists(__file__) else io.StringIO('"'"'from setuptools import setup; setup()'"'"');code = f.read().replace('"'"'\r\n'"'"', '"'"'\n'"'"');f.close();exec(compile(code, __file__, '"'"'exec'"'"'))' install --record 'C:\Users\jaimi\AppData\Local\Temp\pip-record-7kg6nb2d\install-record.txt' --single-version-externally-managed --compile --install-headers 'C:\Users\jaimi\miniconda3\envs\frankmocap\Include\pycocotools' Check the logs for full command output.

(frankmocap) C:\Mocap\Frankmocap>echo Installing a third-party 2D keypoint detector
Installing a third-party 2D keypoint detector

(frankmocap) C:\Mocap\Frankmocap>python scripts_py/install_pose2d.py
Traceback (most recent call last):
  File "scripts_py/install_pose2d.py", line 3, in <module>
    import git
ModuleNotFoundError: No module named 'git'

(frankmocap) C:\Mocap\Frankmocap>echo Download extra data for body module
Download extra data for body module

(frankmocap) C:\Mocap\Frankmocap>python scripts_py/download_data_body_module.py
Creation of the directory C:\Mocap\Frankmocap/extra_data/body_module failed
Downloading: data.tar.gz
Traceback (most recent call last):
  File "scripts_py/download_data_body_module.py", line 32, in <module>
FileExistsError: [WinError 183] Cannot create a file when that file already exists: 'data' -> 'data_from_spin'
