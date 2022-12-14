## OMP BAMM 2.0 Helps Deliver on the Promise of Digital Twins

### The Promise of Digital Twins
(2021/12/21) - Digital transformation is the reimagining of organizations in the digital age. It is commonly defined as the process of using digital technologies to create or modify organizational processes, technology, structure, and data processing and storage practices to meet changing market or regulatory demands.  Of the many technologies created to aid digital transformation, digital twins can be one of the most beneficial for increasing efficiency.

A digital twin is a digital representation of physical assets, devices, and systems within an organization.  The concept can be applied to almost any type of organization and allows for in-depth analysis to aid in decision-making in a virtual setting before implementation.  Gartner recommends creating a digital twin of your organization to help navigate digital transformation and reduce the risk of failure.

In the manufacturing industry, digital twins can be deployed in a wide variety of use cases, including system planning and optimization, employee training, and predictive maintenance. A digital twin can be launched across an entire organization or a single production line.

### Where the BAMM Fits In
It is easy to see that across industries and oftentimes even within the same organization, various digital twins may have very different submodels to represent the different aspects of an asset.

Since not everyone needs the same set of information, a digital twin is a collection of various aspects of an asset. An aspect can, for example, bundle all information about machine malfunctions.  Problems arise when digital twins are built in silos where various aspects are described in different ways or given different names, for example.  To help standardize various aspects and reduce fragmentation, it is useful to have agreed-upon semantics around those aspects.

Aspects are characterized by aspect models that formally describe how an aspect is structured.  The model describes things like the units of measurement and possible value range for a temperature sensor in a way that is readable by machines.  This allows for faster, more automated responses to the data as it is received.

A meta model is a model that defines the constructs and properties used by aspect models.  In other words, an aspect meta model provides the machine-readable language or semantics used across an entire system of aspect models.  The aspect meta model enables the reuse of attributes from one aspect model to the next.

OMP’s Semantic Data Structuring Working Group (SDS-WG) defined a semantic data-structuring layer that addresses the needs to share, join, and reuse heterogeneous data in the manufacturing domain by applying common semantics for various stakeholders through comprehensive semantic data homogenization and by conveying manufacturing data along with contextual information.

First published in May of 2021, the group has created the [BAMM Aspect Meta Model specification](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/v1.0.0/index.html), also known as BAMM.  BAMM allows the creation of models to describe the semantics of digital twins by defining their domain-specific aspects.  The specification defines a framework for how an aspect of a digital twin should be described in terms of both information about the runtime data structure and information that is not part of the runtime data.  It specifies the elements from which an aspect model can be built as well as the following data descriptors:

* Namespace and Versions
* Data Types
* Characteristics
* Constraints
* Entities
* Units
* Aspects

The primary benefit of BAMM is that it standardizes the creation of domain-specific models and also makes them reusable. The modularity, extensibility, and reusability simplify the creation of aspect models used to describe the semantics of the different aspects of a digital twin. As an open-source approach, it can be used free of charge to realize data homogenization projects and helps to create sustainable synergies between companies, developers, and users.

### Updates in BAMM 2.0
In November of 2021, the SDS-WG published [BAMM version 2.0](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/2.0.0-M1/index.html).  The major feature update is around the idea of Entity Inheritance. The [new abstract entity meta model element](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/snapshot/modeling-guidelines.html#declaring-abstract-entities) together with the extends attribute can be used to define a hierarchy of entities in an aspect model. This allows a user to define a collection of different components sharing a common set of properties, for example.

[Access the BAMM v2.0](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/2.0.0-M1/index.html)
