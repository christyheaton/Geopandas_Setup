### Getting Started

* If you are familiar with [GitHub](http://www.github.com), fork (if you wish) and clone this repository. If not, click the green Clone or Download button and then select Download ZIP. Unzip the downloaded file to a working directory. Take note of where you put it!

* Install [Miniconda](https://conda.io/miniconda.html) for your operating system. Please choose the latest Python 3.x version. The [installation instructions](https://conda.io/docs/user-guide/install/index.html#regular-installation) might be helpful.

* You should now have access to an Anaconda command prompt, open it like you would any program. Note that you should see `(base)` somewhere in your prompt. This means you're in the base Conda environment, which we will now change. 

Navigate to the directory containing environment.yml (included in the repo).

```bash
cd [location where you saved the repo]/Geopandas_Setup
```

* Create the Conda environment you will need to use Geopandas. Note: it is called `geopandasenv`. **This could take anywhere from 10-30 minutes to finish.**

```bash
conda env create environment.yml
```

* Now you can activate the environment.

```bash
source activate geopandasenv  # macOS and Linux
activate geopandasenv  # Windows.
```

* To test your installation, a Jupyter Notebook is provided in this repository. To open the Jupyter Notebook, in your Anaconda prompt navigated to the Geopandas_Setup directory, type in:

```bash
jupyter notebook
```

This will open a browser and you will see the Jupyter logo at the top. You will also see a link to open Test Geopandas.ipynb. Click it and run the cells to test that setup occurred correctly.

* If you ever want to deactivate the geopandasenv environment, type the following in your Anaconda prompt:

```bash
source deactivate  # macOS and Linux
deactivate  # Windows.
```

* Closing your Anaconda Prompt will also deactivate the environment. Follow the same instructions here to activate it as needed.