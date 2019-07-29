# Awesome Python [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python frameworks, libraries, software and resources.

Inspired by [awesome-php](https://github.com/ziadoz/awesome-php).

- [Awesome Python](#awesome-python)
    - [Algorithms and Design Patterns](#algorithms-and-design-patterns)
    - [ChatOps Tools](#chatops-tools)
    - [Code Analysis](#code-analysis)
    - [Command-line Interface Development](#command-line-interface-development)
    - [Command-line Tools](#command-line-tools)
    - [Data Analysis](#data-analysis)
    - [Data Validation](#data-validation)
    - [Data Visualization](#data-visualization)
    - [Deep Learning](#deep-learning)
    - [HTML Manipulation](#html-manipulation)
    - [Machine Learning](#machine-learning)
    - [Natural Language Processing](#natural-language-processing)
    - [Network Virtualization](#network-virtualization)
    - [RESTful API](#restful-api)
    - [Search](#search)
    - [Web Content Extracting](#web-content-extracting)
    - [Web Crawling](#web-crawling)
    - [Web Frameworks](#web-frameworks)
- [Services](#services)
    - [Code Quality](#code-quality)

---

## Algorithms and Design Patterns

*Python implementation of algorithms and design patterns.*

* [algorithms](https://github.com/keon/algorithms) - Minimal examples of data structures and algorithms in Python.
* [PyPattyrn](https://github.com/tylerlaberge/PyPattyrn) - A simple yet effective library for implementing common design patterns.
* [python-patterns](https://github.com/faif/python-patterns) - A collection of design patterns in Python.
* [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) - Fast, pure-Python implementation of SortedList, SortedDict, and SortedSet types.

## ChatOps Tools

*Libraries for chatbot development.*

* [errbot](https://github.com/errbotio/errbot/) - The easiest and most popular chatbot to implement ChatOps.

## Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis](https://github.com/mre/awesome-static-analysis).*

* Code Analysis
    * [coala](https://github.com/coala/coala/) - Language independent and easily extendable code analysis application.
    * [code2flow](https://github.com/scottrogowski/code2flow) - Turn your Python and JavaScript code into DOT flowcharts.
    * [prospector](https://github.com/PyCQA/prospector) - A tool to analyse Python code.
    * [pycallgraph](https://github.com/gak/pycallgraph) - A library that visualises the flow (call graph) of your Python application.
* Code Linters
    * [flake8](https://pypi.org/project/flake8/) - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
    * [pylint](https://www.pylint.org/) - A fully customizable source code analyzer.
    * [pylama](https://github.com/klen/pylama) - A code audit tool for Python and JavaScript.
* Code Formatters
    * [black](https://github.com/python/black) - The uncompromising Python code formatter.
    * [yapf](https://github.com/google/yapf) - Yet another Python code formatter from Google.
* Static Type Checkers
    * [mypy](http://mypy-lang.org/) - Check variable types during compile time.
    * [pyre-check](https://github.com/facebook/pyre-check) - Performant type checking.
* Static Type Annotations Generators
    * [MonkeyType](https://github.com/Instagram/MonkeyType) - A system for Python that generates static type annotations by collecting runtime types

## Command-line Interface Development

*Libraries for building command-line applications.*

* Command-line Application Development
    * [cement](http://builtoncement.com/) - CLI Application Framework for Python.
    * [click](http://click.pocoo.org/dev/) - A package for creating beautiful command line interfaces in a composable way.
    * [cliff](https://docs.openstack.org/developer/cliff/) - A framework for creating command-line programs with multi-level commands.
    * [clint](https://github.com/kennethreitz/clint) - Python Command-line Application Tools.
    * [docopt](http://docopt.org/) - Pythonic command line arguments parser.
    * [python-fire](https://github.com/google/python-fire) - A library for creating command line interfaces from absolutely any Python object.
    * [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) - A library for building powerful interactive command lines.
* Terminal Rendering
    * [asciimatics](https://github.com/peterbrittain/asciimatics) - A package to create full-screen text UIs (from interactive forms to ASCII animations).
    * [bashplotlib](https://github.com/glamp/bashplotlib) - Making basic plots in the terminal.
    * [colorama](https://pypi.org/project/colorama/) - Cross-platform colored terminal text.
    * [tqdm](https://github.com/tqdm/tqdm) - Fast, extensible progress bar for loops and CLI.

## Command-line Tools

*Useful CLI-based tools for productivity.*

* Productivity Tools
    * [cookiecutter](https://github.com/audreyr/cookiecutter) - A command-line utility that creates projects from cookiecutters (project templates).
    * [doitlive](https://github.com/sloria/doitlive) - A tool for live presentations in the terminal.
    * [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers via the command line.
    * [PathPicker](https://github.com/facebook/PathPicker) - Select files out of bash output.
    * [percol](https://github.com/mooz/percol) - Adds flavor of interactive selection to the traditional pipe concept on UNIX.
    * [thefuck](https://github.com/nvbn/thefuck) - Correcting your previous console command.
    * [tmuxp](https://github.com/tony/tmuxp) - A [tmux](https://github.com/tmux/tmux) session manager.
    * [try](https://github.com/timofurrer/try) - A dead simple CLI to try out python packages - it's never been easier.
* CLI Enhancements
    * [httpie](https://github.com/jakubroztocil/httpie) - A command line HTTP client, a user-friendly cURL replacement.
    * [kube-shell](https://github.com/cloudnativelabs/kube-shell) - An integrated shell for working with the Kubernetes CLI.
    * [mycli](https://github.com/dbcli/mycli) - A Terminal Client for MySQL with AutoCompletion and Syntax Highlighting.
    * [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting.
    * [saws](https://github.com/donnemartin/saws) - A Supercharged [aws-cli](https://github.com/aws/aws-cli).

## Data Analysis

*Libraries for data analyzing.*

* [Blaze](https://github.com/blaze/blaze) - NumPy and Pandas interface to Big Data.
* [Open Mining](https://github.com/mining/mining) - Business Intelligence (BI) in Pandas interface.
* [Orange](https://orange.biolab.si/) - Data mining, data visualization, analysis and machine learning through visual programming or scripts.
* [Pandas](http://pandas.pydata.org/) - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [Optimus](https://github.com/ironmussa/Optimus) - Agile Data Science Workflows made easy with PySpark.

## Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [Cerberus](https://github.com/pyeve/cerberus) - A lightweight and extensible data validation library.
* [colander](https://docs.pylonsproject.org/projects/colander/en/latest/) - Validating and deserializing data obtained via XML, JSON, an HTML form post.
* [jsonschema](https://github.com/Julian/jsonschema) - An implementation of [JSON Schema](http://json-schema.org/) for Python.
* [schema](https://github.com/keleshev/schema) - A library for validating Python data structures.
* [Schematics](https://github.com/schematics/schematics) - Data Structure Validation.
* [valideer](https://github.com/podio/valideer) - Lightweight extensible data validation and adaptation library.
* [voluptuous](https://github.com/alecthomas/voluptuous) - A Python data validation library.

## Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization).*

* [Altair](https://github.com/altair-viz/altair) - Declarative statistical visualization library for Python.
* [Bokeh](https://github.com/bokeh/bokeh) - Interactive Web Plotting for Python.
* [bqplot](https://github.com/bloomberg/bqplot) - Interactive Plotting Library for the Jupyter Notebook
* [Dash](https://plot.ly/products/dash/) - Built on top of Flask, React and Plotly aimed at analytical web applications.
    * [awesome-dash](https://github.com/Acrotrend/awesome-dash)
* [ggplot](https://github.com/yhat/ggpy) - Same API as ggplot2 for R.
* [Matplotlib](http://matplotlib.org/) - A Python 2D plotting library.
* [Pygal](http://www.pygal.org/en/latest/) - A Python SVG Charts Creator.
* [PyGraphviz](https://pypi.org/project/pygraphviz/) - Python interface to [Graphviz](http://www.graphviz.org/).
* [PyQtGraph](http://www.pyqtgraph.org/) - Interactive and realtime 2D/3D/Image plotting and science/engineering widgets.
* [Seaborn](https://github.com/mwaskom/seaborn) - Statistical data visualization using Matplotlib.
* [VisPy](https://github.com/vispy/vispy) - High-performance scientific visualization based on OpenGL.


## Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning).*

* [caffe](https://github.com/BVLC/caffe) - A fast open framework for deep learning..
* [keras](https://github.com/keras-team/keras) - A high-level neural networks library and capable of running on top of either TensorFlow or Theano.
* [mxnet](https://github.com/dmlc/mxnet) - A deep learning framework designed for both efficiency and flexibility.
* [pytorch](https://github.com/pytorch/pytorch) - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
* [SerpentAI](https://github.com/SerpentAI/SerpentAI) - Game agent framework. Use any video game as a deep learning sandbox.
* [tensorflow](https://github.com/tensorflow/tensorflow) - The most popular Deep Learning framework created by Google.
* [Theano](https://github.com/Theano/Theano) - A library for fast numerical computation.

## HTML Manipulation

*Libraries for working with HTML and XML.*

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.

## Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python).*

* [H2O](https://github.com/h2oai/h2o-3) - Open Source Fast Scalable Machine Learning Platform.
* [Metrics](https://github.com/benhamner/Metrics) - Machine learning evaluation metrics.
* [NuPIC](https://github.com/numenta/nupic) - Numenta Platform for Intelligent Computing.
* [scikit-learn](http://scikit-learn.org/) - The most popular Python library for Machine Learning.
* [Spark ML](http://spark.apache.org/docs/latest/ml-guide.html) - [Apache Spark](http://spark.apache.org/)'s scalable Machine Learning library.
* [vowpal_porpoise](https://github.com/josephreisinger/vowpal_porpoise) - A lightweight Python wrapper for [Vowpal Wabbit](https://github.com/JohnLangford/vowpal_wabbit/).
* [xgboost](https://github.com/dmlc/xgboost) - A scalable, portable, and distributed gradient boosting library.

## Natural Language Processing

*Libraries for working with human languages.*

- General
    * [gensim](https://github.com/RaRe-Technologies/gensim) - Topic Modelling for Humans.
    * [langid.py](https://github.com/saffsd/langid.py) - Stand-alone language identification system.
    * [nltk](http://www.nltk.org/) - A leading platform for building Python programs to work with human language data.
    * [pattern](https://github.com/clips/pattern) - A web mining module for the Python.
    * [polyglot](https://github.com/aboSamoor/polyglot) - Natural language pipeline supporting hundreds of languages.
    * [pytext](https://github.com/facebookresearch/pytext) - A natural language modeling framework based on PyTorch.
    * [PyTorch-NLP](https://github.com/PetrochukM/PyTorch-NLP) - A toolkit enabling rapid deep learning NLP prototyping for research.
    * [spacy](https://spacy.io/) - A library for industrial-strength natural language processing in Python and Cython.
    * [stanfordnlp](https://github.com/stanfordnlp/stanfordnlp) - The Stanford NLP Group's official Python library, supporting 50+ languages.

## Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [mininet](https://github.com/mininet/mininet) - A popular network emulator and API written in Python.
* [pox](https://github.com/noxrepo/pox) - A Python-based SDN control applications, such as OpenFlow SDN controllers.

## RESTful API

*Libraries for developing RESTful APIs.*

* Django
    * [django-rest-framework](http://www.django-rest-framework.org/) - A powerful and flexible toolkit to build web APIs.
    * [django-tastypie](http://tastypieapi.org/) - Creating delicious APIs for Django apps.
* Flask
    * [eve](https://github.com/pyeve/eve) - REST API framework powered by Flask, MongoDB and good intentions.
    * [flask-api-utils](https://github.com/marselester/flask-api-utils) - Taking care of API representation and authentication for Flask.
    * [flask-api](http://www.flaskapi.org/) - Browsable Web APIs for Flask.
    * [flask-restful](https://github.com/flask-restful/flask-restful) - Quickly building REST APIs for Flask.
    * [flask-restless](https://github.com/jfinkels/flask-restless) - Generating RESTful APIs for database models defined with SQLAlchemy.
* Pyramid
    * [cornice](https://github.com/Cornices/cornice) - A RESTful framework for Pyramid.
* Framework agnostic
    * [apistar](https://github.com/encode/apistar) - A smart Web API framework, designed for Python 3.
    * [falcon](http://falconframework.org/) - A high-performance framework for building cloud APIs and web app backends.
    * [hug](https://github.com/timothycrosley/hug) - A Python 3 framework for cleanly exposing APIs.
    * [restless](https://github.com/toastdriven/restless) - Framework agnostic REST framework based on lessons learned from Tastypie.
    * [ripozo](https://github.com/vertical-knowledge/ripozo) - Quickly creating REST/HATEOAS/Hypermedia APIs.
    * [sandman](https://github.com/jeffknupp/sandman) - Automated REST APIs for existing database-driven systems.

## Search

*Libraries and software for indexing and performing search queries on data.*

* [elasticsearch-py](https://www.elastic.co/guide/en/elasticsearch/client/python-api/current/index.html) - The official low-level Python client for [Elasticsearch](https://www.elastic.co/products/elasticsearch).
* [elasticsearch-dsl-py](https://github.com/elastic/elasticsearch-dsl-py) - The official high-level Python client for Elasticsearch.
* [django-haystack](https://github.com/django-haystack/django-haystack) - Modular search for Django.
* [pysolr](https://github.com/django-haystack/pysolr) - A lightweight Python wrapper for [Apache Solr](https://lucene.apache.org/solr/).
* [whoosh](http://whoosh.readthedocs.io/en/latest/) - A fast, pure Python search engine library.

## Web Content Extracting

*Libraries for extracting web contents.*

* [html2text](https://github.com/Alir3z4/html2text) - Convert HTML to Markdown-formatted text.

## Web Crawling

*Libraries to automate web scraping.*

* [cola](https://github.com/chineking/cola) - A distributed crawling framework.
* [feedparser](https://pythonhosted.org/feedparser/) - Universal feed parser.
* [grab](https://github.com/lorien/grab) - Site scraping framework.
* [MechanicalSoup](https://github.com/MechanicalSoup/MechanicalSoup) - A Python library for automating interaction with websites.
* [pyspider](https://github.com/binux/pyspider) - A powerful spider system.
* [robobrowser](https://github.com/jmcarp/robobrowser) - A simple, Pythonic library for browsing the web without a standalone web browser.
* [scrapy](https://scrapy.org/) - A fast high-level screen scraping and web crawling framework.
* [portia](https://github.com/scrapinghub/portia) - Visual scraping for Scrapy.

## Web Frameworks

*Full stack web frameworks.*

* [Django](https://www.djangoproject.com/) - The most popular web framework in Python.
    * [awesome-django](https://github.com/shahraizali/awesome-django)

# Services

Online tools and APIs to simplify development.

## Code Quality

* [Codacy](https://www.codacy.com/) - Automated Code Review to ship better code, faster.
* [Codecov](https://codecov.io/) - Code coverage dashboard.
* [CodeFactor](https://www.codefactor.io/) - Automated Code Review for Git.
* [Landscape](https://landscape.io/) - Hosted continuous Python code metrics.
* [PEP 8 Speaks](https://pep8speaks.com/) - GitHub integration to review code style.
