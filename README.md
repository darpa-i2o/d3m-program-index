# Data-driven discovery of models (D3M) program index

A list of D3M-related tools and their repository URLs

## Pipeline infrastructure and tools

[d3m core package](https://gitlab.com/datadrivendiscovery/d3m)

[common primitives](https://gitlab.com/datadrivendiscovery/common-primitives)

[TA3-TA2 API](https://gitlab.com/datadrivendiscovery/ta3ta2-api)

[simple-TA3](https://gitlab.com/datadrivendiscovery/simple-ta3)

## TA1 Components

[BYU Primitives](https://github.com/byu-dml/d3m-primitives)

BYU-DML machine learning algorithms or primitives created for DARPA's D3M project. These primitives are wrapped to fit within the D3M ecosystem.

[Common Primitives](https://gitlab.com/datadrivendiscovery/common-primitives/)

A collection of primitives and pipelines from multiple teams.

[JHU Primitives](https://github.com/neurodata/primitives-interfaces)

A collection of JHU Python interfaces for TA1 primitives in the D3M project.

[RPI Primitives](https://github.com/zijun-rpi/d3m-primitives)

RPI primitives for D3M project. Executable pipelines are included.

[ISI Data Cleaning Primitives](https://github.com/usc-isi-i2/dsbox-cleaning), [ISI Featurization Primitives](https://github.com/usc-isi-i2/dsbox-featurizer)

A collection of ISI primitives for data cleaning and featurization.

[BBN Primitives](https://gitlab.datadrivendiscovery.org/BBN/d3m-bbn-primitives/tree/d3m.api2019.1.21.a)

BBN primitives and pipelines for D3M project. 

[CMU Find Projections Primitives](https://gitlab.datadrivendiscovery.org/sray/find_projections), [CMU Fastlvm Primitives](https://gitlab.datadrivendiscovery.org/cmu/fastlvm)

A collection of CMU primitives for D3M project.
## TA2 Systems

[ISI DSBox System](https://github.com/usc-isi-i2/dsbox-ta2)

ISI's template-based automated machine learning system.

## TA3 Systems

## DataMart

DataMarts are data search engines. Given a problem and an dataset, those system can provide additional, relevant data and augment the initial dataset to enable the construction of a better model.

### NYU's DataMart system

* [Publicly-accessible address](https://datamart.d3m.vida-nyu.org/)
* [Source code](https://gitlab.com/ViDA-NYU/datamart/datamart)
* [Data augmentation examples](https://gitlab.com/ViDA-NYU/datamart/datamart/tree/master/examples) through the API
* Python packages: [datamart](https://pypi.org/project/datamart/), [datamart-materialize](https://pypi.org/project/datamart-materialize/), [datamart-augmentation](https://pypi.org/project/datamart-augmentation/)

### USC ISI's DataMart system

* [Source code](https://github.com/usc-isi-i2/datamart/tree/development)
* [College Debt example](https://github.com/usc-isi-i2/datamart/blob/development/example/college_example/college_example.ipynb)
* [FIFA Man of the Match example](https://github.com/usc-isi-i2/datamart/blob/development/example/fifa_example/fifa_example.ipynb)
* [REST example](https://github.com/usc-isi-i2/datamart/blob/development/example/rest_example/example.md)
