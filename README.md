# python-data-science
List of useful Python packages for data science:

### PyData stack
- [numpy](http://www.numpy.org/)
- [scipy](https://docs.scipy.org/doc/scipy/reference/)
- [pandas](https://pandas.pydata.org/)
- [jupyter](https://jupyter.org/)
- [statsmodels](https://www.statsmodels.org/stable/index.html)

### Profiling
- [pandas-profiling](https://github.com/pandas-profiling/pandas-profiling)
- [memory_profiler](https://github.com/pythonprofilers/memory_profiler)
- [py-spy](https://github.com/benfred/py-spy/blob/master/README.md)
- [pyflame](https://github.com/uber/pyflame) ❗ (Does not support Windows)

### Forecasting
- [pyramid-arima](https://github.com/tgsmith61591/pyramid)
- [fbprophet](https://facebook.github.io/prophet/) - time series forecasting (additive model) which performs best with high frequency data
- [pyflux](https://github.com/RJT1990/pyflux) - time series library

### Niche stats libraries
- [lifelines](https://github.com/CamDavidsonPilon/lifelines) - survival analysis
- [convoys](https://better.engineering/convoys/)

### "Large Data" libraries
- [dask](https://dask.org/)
- [pyarrow](https://arrow.apache.org/) - Python bindings for Apache [Arrow](https://arrow.apache.org/)
- [fastparquet](https://github.com/dask/fastparquet)
- [vaex](https://github.com/maartenbreddels/vaex)
- [modin](https://github.com/modin-project/modin) - pandas on [Ray](https://ray-project.github.io/) execution framework
- [dampr](https://github.com/Refefer/Dampr)
- [datatable](https://github.com/h2oai/datatable) - pandas equivalent for performing big data (up to 100GB) operations on a single-node machine, at the maximum speed possible

### visualization libraries
- [PyViz](http://pyviz.org/) stack
- [Plotly](https://plot.ly/python/)
- [Dash](https://github.com/plotly/dash) - dashboard library from plotly
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [altair](https://github.com/justinbois/altair-catplot)
- [pdvega](https://github.com/altair-viz/pdvega)
- [chartify](https://github.com/spotify/chartify)
- [dataspyre](https://github.com/adamhajari/spyre) - dashboard framework with flask backend
- [folium](https://github.com/python-visualization/folium)
- [geoplot](https://github.com/ResidentMario/geoplot)
- [plotnine](https://github.com/has2k1/plotnine) - clone of R's ggplot2
- [joypy](https://github.com/sbebo/joypy)
- [bqplot](https://github.com/bloomberg/bqplot)
- [jmpy](https://github.com/beltashazzer/jmpy)
- [pyqtgraph](http://www.pyqtgraph.org/)
- [probscale](https://github.com/matplotlib/mpl-probscale) - probability scaled axis
- [adjustText](https://github.com/Phlya/adjustText) - add non-overlapping annotated text

### Jupyter Notebook Related
- [ipysheet](https://github.com/QuantStack/ipysheet)
- [ipypivot](https://github.com/PierreMarion23/ipypivot)
- [papermill + scrapbook](https://github.com/nteract/papermill) - parameterized notebooks
- [nteract-scapbook](https://github.com/nteract/scrapbook) - for passing data between notebooks
- [jupytext](https://github.com/mwouts/jupytext) - edit notebooks as text files

### database related
- [pyodbc](https://github.com/mkleehammer/pyodbc)
- [turbodbc](https://turbodbc.readthedocs.io/en/latest/)
- [ipython-sql](https://github.com/catherinedevlin/ipython-sql)
- [sqlalchemy](https://www.sqlalchemy.org/)
- [sqlalchemy-turbodbc](https://github.com/dirkjonker/sqlalchemy-turbodbc)

### ETL or data engineering related sorted from lightest to heaviest framework
- [papermill + scrapbook](https://github.com/nteract/papermill) - parameterized notebooks
- [dequindre](https://github.com/vogt4nick/dequindre)
- [petl](https://github.com/petl-developers/petl)
- [bonobo](https://www.bonobo-project.org/)
- [pypeln](https://github.com/cgarciae/pypeln/)
- [botflow](https://github.com/kkyon/botflow)
- [mara data integration](https://github.com/mara/data-integration)
- [dbt](https://www.getdbt.com/)
- [Luigi](https://github.com/spotify/luigi) from Spotify - works with Windows
- [Apache Airflow](https://airflow.apache.org/) - Windows not supported

### Data validation and cleaning frameworks
- [cerberus](https://github.com/pyeve/cerberus)
- [great_expectations](https://github.com/great-expectations/great_expectations)
- [pandera](https://github.com/cosmicBboy/pandera)
- [pyjanitor](https://pyjanitor.readthedocs.io/)
- [schema](https://github.com/keleshev/schema)
- [PandasSchema](https://github.com/TMiguelT/PandasSchema)
- [engarde](https://github.com/TomAugspurger/engarde)

### Machine Learning Related - mostly for tabular data or non-NN
- [scikit-learn](https://scikit-learn.org/stable/)
- [sklearn-pandas](https://github.com/scikit-learn-contrib/sklearn-pandas)
- [imbalanced-learn](https://github.com/scikit-learn-contrib/imbalanced-learn)
- [hyperopt-sklearn](https://github.com/hyperopt/hyperopt-sklearn) - not pip installable yet
- [tpot](https://github.com/EpistasisLab/tpot)
- [xgboost](https://xgboost.readthedocs.io/en/latest/)
- [lightgbm](https://github.com/Microsoft/LightGBM)
- [DMTK](http://www.dmtk.io/) - Microsoft Distributed Machine Learning Toolkit
- [fastText](https://fasttext.cc/)

### Deep learning
- [Netron](https://github.com/lutzroeder/Netron) - visualize NNs
- [BlingFire](https://github.com/Microsoft/BlingFire)  -Microsoft Bing team, a tokenizer designed for fast-speed and quality tokenization of Natural Language text

### Webscraping
- [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [mechanicalsoup](https://mechanicalsoup.readthedocs.io/en/stable/)
- [selenium](https://www.seleniumhq.org/) - headless-browser framework for extracting javascript data
- [scrapy](https://scrapy.org/) - OOP framework
- [newspaper3k](https://newspaper.readthedocs.io) - easily extract text from articles
- [requests-html](https://github.com/kennethreitz/requests-html)

### Utilities
- [tldr-python-client](https://github.com/tldr-pages/tldr-python-client) - replacement for man pages
- bropages](http://bropages.org/) - 
```sudo apt-get install ruby-dev, sudo gem install bropages```
- [howdoi](https://github.com/gleitz/howdoi)
- [inspect](https://docs.python.org/3/library/inspect.html)
- [prettypandas](https://prettypandas.readthedocs.io/en/latest/)
- [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy)
- [fuzzymatcher](https://github.com/RobinL/fuzzymatcher)
- [pytest](https://docs.pytest.org/en/latest/)
- [requests](http://docs.python-requests.org/en/master/)
- [psutil](https://github.com/giampaolo/psutil)

### CLI
- [click](https://click.palletsprojects.com/en/7.x/) - for making CLI
- [fire](https://github.com/google/python-fire) - for making CLI
- [questionary](https://github.com/tmbo/questionary)

### Progress Bars
- [tqdm](https://github.com/tqdm/tqdm)
- [fastprogress](https://github.com/fastai/fastprogress)

### Misc.
- [glances](https://nicolargo.github.io/glances/) - CPU/memory monitoring
- [pendulum](https://pendulum.eustace.io/) - a better datetime library, better than arrow
- [visidata](https://jsvine.github.io/intro-to-visidata/index.html) - free, open-source tool that lets you quickly open, explore, summarize, and analyze datasets in your computer’s terminal
- [schedule](https://github.com/dbader/schedule) - job scheduling for humans
- [pyautogui](https://pyautogui.readthedocs.io/en/latest/)
- [ptpython](https://github.com/prompt-toolkit/ptpython) - better REPL
- [xlwings](https://www.xlwings.org/) - Excel VBA, but with Python instead
- [openpyxl](https://openpyxl.readthedocs.io/en/stable/)
- [scriptedforms](https://github.com/SimonBiggs/scriptedforms)
- [black](https://github.com/ambv/black) - source code formatter

### debugging
- [ipdb](https://github.com/gotcha/ipdb)
- [pudb](https://github.com/inducer/pudb) - Windows not supported, need cygwin

### logging
- [loguru](https://github.com/Delgan/loguru)
