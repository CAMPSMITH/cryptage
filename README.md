# cryptage

An analysis tool to assess arbitrage opportunities in Bitcoin and other cryptocurrencies

---

## Technologies

* **Pandas**  - A python library with advanced financial analysis tools.
* **Jupyter Lab** - An IDE used for visualization.
* **anaconda** - A python framework consisting of several tools used in financial analysis, such as Pandas and Jupyter Lab.

---

## Installation Guide
### Prerequisites
#### Anaconda
It is recommended that you have Anaconda installed to facilitate using Pandas and Jupyter notebooks.  It is also recommended to create a virtual environment that includes anaconda and its dependencies.  In this example, the virtual environment will be named *cryptage*.  This convention will be used throughout this document.
* Create and activate an anaconda virtual environment:
```
conda create -n cryptage python=3.7 anaconda
conda activate cryptage
```
#### Pandas
The Pandas library should be pre-installed in the anaconda virtual environment.  
* Check Pandas library
```
conda list pandas
```
Confirm that your virtual environment has a pandas library.  You shoudld get a result similar to 
```
# packages in environment at <user path>/opt/anaconda3/envs/cryptage:
#
# Name                    Version                   Build  Channel
pandas                    1.3.4            py37h743cdd8_0  
```
#### JupyterLab
The JupyterLab IDE should be pre-installed in the anaconda virtual environment.  
* Check JupyterLab
```
conda list jupyterlab
```
Confirm that your virtual environment has a pandas library.  You shoudld get a result similar to 
```
# packages in environment at <user path>/opt/anaconda3/envs/cryptage:
#
# Name                    Version                   Build  Channel
jupyterlab                3.2.1              pyhd3eb1b0_1  
jupyterlab_pygments       0.1.2                      py_0  
jupyterlab_server         2.8.2              pyhd3eb1b0_0  
jupyterlab_widgets        1.0.0              pyhd3eb1b0_1 
```

#### Python Kernal for JupyterLab
* Set up a python kernal for the JupyterLab IDE
```
python -m ipykernel install --user --name cryptage --display-name "Python(cryptage)"
```
Once the kernal is installed, you should get message similar to the following:
```
Installed kernelspec cryptage in <user path>/Library/Jupyter/kernels/cryptage
```

---

## Usage

### Starting JupyterLab IDE
The JupyterLab IDE will be used to run the analytical cnotebook.  To launch JupyterLab, assuming prerequities have been satisfied:
```
jupyter lab
```
This command should automatically start the JupyterLab IDE in your browser.
If it does not, follow the instructions in your terminal to get the local URL and launch Jupiter lab in your browser.

### Running the Cryptage Notebook
Once Jupyter Lab has started in your browser, select the **crypto_arbitrage.ipynb** notebook from the **Left Sidebar**.
![launch Notebook crypto_arbitrage.ipynb](images/Screen%20Shot%202022-04-09%20at%2010.21.55%20PM.png)

---

## Contributors

*  **Martin Smith** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> *email:* msmith92663@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> [<img src="images/LI-In-Bug.png" alt="in" width="20"/>](https://www.linkedin.com/in/smithmartinp/)


---

## References
For further information on the tools and libraries used, review the following references:
* [JupyterLab Documentation and User Guide](https://jupyterlab.readthedocs.io/en/stable/)
* [The JupyterLab Interface](https://jupyterlab.readthedocs.io/en/stable/user/interface.html)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Introducing Pandas Objects](https://jakevdp.github.io/PythonDataScienceHandbook/03.01-introducing-pandas-objects.html)
* [Pandas Visualization Guide](https://pandas.pydata.org/docs/user_guide/visualization.html)

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)