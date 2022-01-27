<p align="center"><img width=50% src="https://raw.githubusercontent.com/DataCloud-project/toolbox/master/docs/img/datacloud_logo.png"></p>&nbsp;

[![GitHub Issues](https://img.shields.io/github/issues/DataCloud-project/DEF-PIPE.svg)](https://github.com/DataCloud-project/DEF-PIPE/issues)

# DEF-PIPE

DEF-PIPE provides a visual design for implementing Big Data pipelines based on a DSL, including storing and loading the pipeline definitions and displaying them in a user interface where domain experts declare the pipeline structure. Furthermore, it enables data scientists to define the content by configuring each step and injecting code or customising generic predefined step templates. 
DEF-PIPE provides the following functionality: 

- DSL described by a context-free grammar captures the distributed data pipeline syntax and semantics and provides data serialisation and de-serialisation format. 

- Graphical user interface enables domain scientists to graphically describe, configure, deploy, and simulate data pipelines using a corresponding DSL compiler capturing its definitions and documentation. 

- Predefined pipeline and step templates provide a library of existing implementations for injection and reuse into the current pipeline. 

From a high-level view, the system has three main components: 
- Visual Designer: An application providing the user interface for building data pipelines and defining templates. The Visual Designer communicate with the REST API for data persistent.

- REST API Web Server: A web API providing a central interface for operations such as managing pipelines and templates data, transforming pipelines into DSL.

- Database: A simple relational database for storing pipelines and templates.

![This is an image](https://github.com/DataCloud-project/DEF-PIPE/blob/main/docs/high-level-components.png)
