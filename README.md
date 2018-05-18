# Elementary-python-functions
An  overview over useful python functions


Setup:

https://www.anaconda.com/download/



Updating:

command for updating anaconda navigator -> "conda update anaconda-navigator"

command for updating the anaconda engine -> "conda update -n base conda"

Make sure it is ready to use -> conda info



Get packages from GitHub:

The answers are outdated. You simply have to conda install pip and git. Then you can use pip normally:
Activate your conda environment

conda install git pip

pip install git+git://github.com/scrappy/scrappy@master



Pytorch package:

You can install pytorch on windows through conda using this command:

conda install -c peterjc123 pytorch

https://stackoverflow.com/questions/45906706/pytorch-install-with-anaconda-error




Dealing with different version of Python:

Current environment ->conda info --env

Inistalling environment for ver2-> conda create -n Python27 python=2.7

https://stackoverflow.com/questions/37442494/is-it-ok-having-both-anacondas-2-7-and-3-5-installed-in-the-same-time

https://stackoverflow.com/questions/30170468/how-to-run-spyder-in-virtual-environment

Errors:

1- The system cannot find the path specified: 'C:\\Program Files (x86)\\Microsoft Visual Studio 14.0\\VC\\PlatformSDK\\lib'

solution-> this error comes up when you don't have Windows SDK installed.

More infromation-> https://github.com/kpu/kenlm/issues/90


2. ModuleNotFoundError: No module named 'urllib2'

solution-> the urllib2 in python2 has been change in divided to different functions. You can replace two following commands:
"from urllib2 import urlopen" -> "from urllib.request import urlopen"

More information: https://www.youtube.com/watch?v=KtxFr6NpHUU


