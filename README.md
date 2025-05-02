# Binary-Sequence-Forecasting

Hybrid Attention for Binary Sequence Forecasting

> Combining n-Gram Embeddings, Count-Aware Self-Attention, and Recency-Weighted ARMA for Multi-Horizon Distributional Predictions


[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)	![GitHub License](https://img.shields.io/github/license/shortthirdman/Binary-Sequence-Forecasting?style=for-the-badge)	![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/shortthirdman/Binary-Sequence-Forecasting?style=for-the-badge)	![GitHub repo size](https://img.shields.io/github/repo-size/shortthirdman/Binary-Sequence-Forecasting?style=for-the-badge)	[![Static Badge](https://img.shields.io/badge/Jupyter_Notebooks_Python3-1-brightgreen?style=for-the-badge&logo=jupyter&logoSize=auto&label=Jupyter%20Notebooks%20(Python3))](/notebooks)

---

### Local Development

  - Create a Python virtual environment and activate
	
	```shell
	$ python -m venv --upgrade-deps --clear dev
	$ export PIP_CONFIG_FILE=".\pip.conf"
	```
 
	```shell
	# PowerShell
 	$ .\dev\Scripts\Activate.ps1
 	```
 
	```shell
	# Linux/macOS
	$ source dev/bin/activate
	```
    
    ```shell
	# Windows Command Prompt
    $ .\dev\Scripts\activate.bat
  	```

  - Install the packages and dependencies as listed in requirements file
	
	```shell
	$ pip install -U -r requirements.txt --no-cache-dir --disable-pip-version-check
	```

  - Start your development `Jupyter Notebook` or `Jupyter Lab` server
	
	```shell
	$ jupyter lab --notebook-dir=.\notebooks --no-browser
	```

  - Install the below packages to run the Python script
  
    ```shell
	$ pip install -q numpy pandas matplotlib scikit-learn torch
	```

---