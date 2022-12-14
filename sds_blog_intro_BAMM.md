## Introducing the BAMM Aspect Meta Model for Digital Twins


### What is a digital twin?
(2021/06/01) - During their entire lifecycle, assets like sensors, vehicles, or machines are generating a great amount of manufacturing, production, and field data – the basis for all value-adding digital applications like condition monitoring or quality management. With increasing digitalization, the volume of data-producing components, as well as data-consuming applications, is continuously growing, as is the distance between sender and receiver.

That is why data needs context in order to be understood by all recipients. Here, Digital Twins come into play. They are digital representatives of the real asset, processing the incoming data into generally understandable information by coupling it to context and providing a standardized semantic model. Since not everyone needs the same set of information, a Digital Twin is a collection of various aspects of an asset. An aspect can, for example, bundle all information about machine malfunctions.

### What is an Aspect Meta Model and how are they used?
Aspects are characterized by aspect models that describe formally how an aspect is structured.  The model describes things like the units of measurement and possible value range for a temperature sensor in a way that is readable by machines.  This allows for faster, more automated responses to the data as it is received.

A meta model is a model that defines the constructs and properties used by aspect models.  In other words, an aspect meta model provides the machine-readable language or semantics used across an entire system of aspect models.  The aspect meta model enables the reuse of attributes from one aspect model to the next.

### Introducing the Open Manufacturing Platform’s Semantic Data Structuring Working Group and the BAMM Aspect Meta Model
The Semantic Data Structuring Working Group officially started in September of 2020. In this working group, a semantic data-structuring layer will be developed that addresses the needs to share, join and reuse heterogeneous data of the manufacturing domain by applying common semantics for various stakeholders through comprehensive semantic data homogenization and by conveying manufacturing data along with contextual information.

As one of their first deliverables, the group has created the [BAMM Aspect Meta Model specification](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/v1.0.0/index.html), also known as BAMM.  BAMM allows the creation of models to describe the semantics of digital twins by defining their domain-specific aspects.  The specification defines a framework for how an aspect of a Digital Twin should be described in terms of both information about the runtime data structure and information that is not part of the runtime data.  It specifies the elements from which an aspect model can be built as well as the following data descriptors:

* Namespace and Versions
* Data Types
* Characteristics
* Constraints
* Entities
* Units
* Aspects

The primary benefit of BAMM is that it standardizes the creation of domain-specific models and also makes them reusable such that the created aspects can be used in several different digital twins.  The modularity and reusability simplify the creation of digital twins for highly complex systems. As an open-source approach, it can be used free of charge to realize data homogenization projects and helps to create sustainable synergies between companies, developers, and users.

The specification is hosted on GitHub, a free hosting service for software development and version control using Git: [https://github.com/OpenManufacturingPlatform/sds-bamm-aspect-meta-model](https://github.com/OpenManufacturingPlatform/sds-bamm-aspect-meta-model)

An accompanying whitepaper can be found [here](https://github.com/OpenManufacturingPlatform/openmanufacturingplatform.github.io/raw/master/docs/sds/OMP-Semantic-Data-Structuring-Whitepaper.pdf)
