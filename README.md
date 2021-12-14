# DEF-PIPE
DEF-PIPE provides a visual design for implementing Big Data pipelines based on a DSL, including storing and loading the pipeline definitions and displaying them in a user interface where domain experts declare the pipeline structure. Furthermore, it enables data scientists to define the content by configuring each step and injecting code or customising generic predefined step templates. 
DEF-PIPE provides the following functionality: 

- DSL described by a context-free grammar captures the distributed data pipeline syntax and semantics and provides data serialisation and de-serialisation format. 

- Graphical user interface enables domain scientists to graphically describe, configure, deploy, and simulate data pipelines using a corresponding DSL compiler capturing its definitions and documentation. 

- Predefined pipeline and step templates provide a library of existing implementations for injection and reuse into the current pipeline. 

The architecture of DEF-PIPE consists of four components: 

- Schema editor allows a graphical construction of the Big Data pipelines through drag-and-drop operations of the step descriptions stored in the template library. 

- Templates editor is a graphical component for describing pipeline steps through their parameters and resource requirements. A templates library stores the steps’ textual descriptions for subsequent pipeline design purposes. 

- DSL editor allows describing pipelines in a textual form. The templates library also stores the complete pipeline descriptions for further redesign and reuse. 

- Pipeline repository stores Big Data pipelines using their DSL representation. 

- Public API enables external interaction, including integration with the DIS-PIPE, SIM-PIPE and ADA-PIPE tools. 
