## Beyond Code – tools and techniques for delivering better aspect models
In recent years, artificial intelligence and machine learning (AI/ML), advances in compute power, the advent of the Cloud, and the Internet of Things (IoT) have converged to enable a technological renaissance in the manufacturing industry that many refer to as digital transformation.  The use of advanced modeling techniques such as digital twinning, predictive maintenance capabilities driven by AI, and the vast amounts of data we can collect and share have enabled manufacturers across vertical industries to make advances in productivity, safety, and quality like never before.

But as technology leaders, CSOs, CTOs, and CEOs often have to make tough choices around the best time to implement new technologies.  The delicate balance between being a technology early adopter or a laggard has real consequences for a company’s bottom line.

### How do we define an emerging technology?
Five attributes are most closely associated with the emerging technology stage. These are:

* radical novelty – this can mean either recent as far as time or use uptake
* relatively fast growth
* coherence
* prominent impact
* uncertainty and ambiguity.[i]

Many technologies that contribute to digital transformation in manufacturing today share the above attributes.  Perhaps the most vexing for corporate decision-makers is uncertainty and ambiguity.  Technological innovations can be costly to deploy and take focus away from other initiatives.  It is uncertainty around implementation feasibility, ROI, longevity, and other bottom-line driven impacts that often keep the C-suite on the fence about adopting new technology.

[i] [https://www.sciencedirect.com/science/article/abs/pii/S0048733315001031](https://www.sciencedirect.com/science/article/abs/pii/S0048733315001031)

### What happens when technology begins to mature?
A mature technology is a technology that has been in use for long enough that most of its initial faults and inherent problems have been removed or reduced by further development. Its performance characteristics are also expected to be well understood with well-established design specifications.

Key indicators of a mature technology include:

* the ease of use for both non-experts and professionals, meaning tools exist to facilitate the technology’s implementation
* adoption of the technology has moved beyond early adopters and is considered standard operating practice
* standards are in place to ensure consistent performance of the new technology
* a reduction in the rate of new breakthrough advances related to it—inventions related to an emerging technology are usually rapid and diverse, advances to a mature technology usually provide incremental improvements. [i]

Executives who wait for a technology to be fully mature may find their early adopter competitors have gained a long-term advantage by adopting that technology when it is still emerging.

[i] [https://en-academic.com/dic.nsf/enwiki/5336102](https://en-academic.com/dic.nsf/enwiki/5336102)

### Digital Transformation Maturity in Manufacturing
Most of the technologies associated with digital transformation in manufacturing are closer to the emerging stage than the mature stage. One of the most important functions of the Open Manufacturing Platform is to create specifications and tools that usher in digital transformation in the manufacturing industry and move technologies such as digital twins from the emerging stage to the mature stage.

One of these tools is the BAMM Aspect Meta Model.  A meta model is a model that defines the constructs and properties used by aspect models.  In other words, an aspect meta model provides the machine-readable language or semantics used across an entire system of aspect models.  The aspect meta model enables the reuse of attributes from one aspect model to the next.

First published in May of 2021, the group has created the [BAMM Aspect Meta Model specification](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/v1.0.0/index.html), also known as BAMM.  BAMM allows the creation of models to describe the semantics of the data being exchanged via digital twins by defining their domain-specific aspects.  The specification defines a framework for how an aspect of a Digital Twin should be described in terms of both information about the runtime data structure and information that is not part of the runtime data.  It specifies the elements from which an aspect model can be built as well as the following data descriptors:

* Namespace and Versions
* Data Types
* Characteristics
* Constraints
* Entities
* Units
* Aspects

The primary benefit of BAMM is that it standardizes the creation of domain-specific models and also makes them reusable such that the created aspects can be used in several different digital twins.  Modularity and reusability simplify the creation of digital twins for highly complex systems. As an open-source approach, it can be used free of charge to realize data homogenization projects and help create sustainable synergies between companies, developers, and users.

### Updates in BAMM 2.0.0
In the third quarter of 2022, the SD-WG published BAMM version 2.0.0.  The major feature update is around the idea of Entity Inheritance. The [new abstract entity meta model element](https://openmanufacturingplatform.github.io/sds-bamm-aspect-meta-model/bamm-specification/snapshot/modeling-guidelines.html#declaring-abstract-entities) and extends attribute can be used to define a hierarchy of entities in an aspect model. This allows a user to define a collection of different components sharing a common set of properties.

### Introducing the Aspect Model Editor
In addition to the updated BAMM, the OMP SDS working group has recently introduced a brand-new tool, the Aspect Model Editor. The [Aspect Model Editor](https://openmanufacturingplatform.github.io/sds-documentation/ame-guide/4.0.0/introduction.html) is a visual editor for aspect models, which automatically validates the models against the open-source BAMM. All concepts, possibilities, and restrictions defined by the BAMM Aspect Meta Model are incorporated in the Aspect Model Editor in a convenient way with a smart user flow.

Typically, aspect models are edited as code, that is, text based. With the Aspect Model Editor, code gets visualized so that relationships and dependencies within the model can be understood quickly and easily. Aspect models can be exported as TTL files and imported from TTL files at any moment during the work on the model. Hence, the Aspect Model Editor caters to all working preferences.

![image](https://user-images.githubusercontent.com/3258579/204357660-cdddc9e7-d37d-4e0a-ae0f-c457b9c5ed97.png)

The Aspect Model Editor focuses on practitioners, such as domain experts or data experts, who intend to efficiently build reusable aspect models for the data and data sources of their domain.  Especially for expert teams who model aspects together, the visual representation of aspect models provides a low entry barrier and facilitates collaboration.

In addition, constant background validation ensures that your aspect models correspond to the BAMM Aspect Meta Model, enabling reuse of your aspect models and automation of the downstream process steps.

Users can find the Editor available in the OMP GitHub repository at: [https://openmanufacturingplatform.github.io/sds-documentation/ame-guide/4.0.0/introduction.html](https://openmanufacturingplatform.github.io/sds-documentation/ame-guide/4.0.0/introduction.html)

