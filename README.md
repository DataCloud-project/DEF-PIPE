<p align="center"><img width=50% src="https://raw.githubusercontent.com/DataCloud-project/toolbox/master/docs/img/datacloud_logo.png"></p>&nbsp;

[![GitHub Issues](https://img.shields.io/github/issues/DataCloud-project/DEF-PIPE.svg)](https://github.com/DataCloud-project/DEF-PIPE/issues)
[![License](https://img.shields.io/badge/license-Apache2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# DEF-PIPE

DEF-PIPE provides a visual design for implementing Big Data pipelines based on a Domain-Specific Language (DSL), including storing and loading the pipeline definitions and displaying them in a user interface where domain experts declare the pipeline structure. Furthermore, it enables data scientists to define the content by configuring each step and injecting code or customising generic predefined step templates.

DEF-PIPE provides the following functionality: 

- [DEF-PIPE DSL](https://github.com/DataCloud-project/DEF-PIPE-DSL) which defines a DSL and a context-free grammar that captures the distributed data pipeline syntax and semantics and provides data serialisation and de-serialisation format. 

- [DEF-PIPE Frontend](https://github.com/DataCloud-project/DEF-PIPE-Frontend), which is a graphical user interface that enables domain scientists to graphically describe, configure, deploy, and simulate data pipelines using a corresponding DSL compiler capturing its definitions and documentation. 

- [DEF-PIPE Pluggable container templates](https://github.com/DataCloud-project/DEF-PIPE-pluggable-container-templates), which are predefined pipeline and step templates comprising a library of existing implementations for injection and reuse in defining big data pipelines. 
