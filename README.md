# mljc-spherical-ml-workshop

If you're running the notebooks in a GitHub Codespace, run these terminal commands in order first. You are likely to run into errors if you try these exact commands on your personal computer, so you'll unfortunately have to find another way to get the key packages (`torch`, `torch-harmonics`, `earth2grid`) installed. Visit the documentation of those packages for more help.

`python -m venv venv`

`source venv/bin/activate`

`pip install --upgrade pip`

`pip install setuptools`

`pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu`

`pip install --no-build-isolation -r requirements.txt`
