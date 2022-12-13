## Announcing the Semantic Stack JavaScript SDK and the JS SDK Aspect Model Loader

In November of 2021, the OMP SDS Working Group delivered a vital tool called the SDS SDK, which contains artifacts and resources for all parties intending to use, extend, or integrate with the BAMM Aspect Meta Model, including solution developers, domain experts, or OEMs. At its core are elements that help users work with the BAMM Aspect Meta Model (BAMM), including components to load and validate models and generate artifacts such as static classes and documentation. To fully leverage BAMM, features include language-specific meta-model implementations, code generators, validators, etc.

One of the first language-specific implementations is the Semantic Stack JavaScript SDK.  The Aspect Model Loader is the first released component of the JavaScript SDK and is available as OSS at https://github.com/OpenManufacturingPlatform/sds-sdk-js-aspect-model-loader.  The SDK provides the tools for developers to leverage information from an Aspect Model to produce JavaScript UIs by supporting loading and traversing an Aspect Model within your JavaScript code. This makes semantic knowledge natively available in JavaScript and provides an easy, quick, and robust developer experience when working with Aspect APIs.

### Why JavaScript?
JavaScript is a popular language for working with web applications, and it is well-suited for parsing .ttl files into native TypeScript objects. This is because JavaScript has a rich ecosystem of libraries and tools that make it easy to work with different data formats, including .ttl files.

One of the critical reasons why JavaScript is a good choice is its support for regular expressions. Regular expressions are a powerful tool for matching patterns in text, and they are often used in parsing applications to extract information from files. In JavaScript, regular expressions are built into the language and are easy to use. This makes it simple to write code that can extract information from a .ttl file and convert it into a native TypeScript object.

Another reason why JavaScript is well-suited is its support for object-oriented programming. TypeScript is an object-oriented language, and JavaScript has many features that make it easy to work with objects. This includes support for classes, inheritance, and other object-oriented concepts. This makes it easy to create TypeScript classes that can represent the data in a .ttl file and use them to manipulate and work with it.

JavaScript has a rich ecosystem of libraries and tools that make it easy to work with different data formats. This includes libraries such as the popular N3.js library. These libraries make it easy to read, write, and manipulate .ttl files in JavaScript, which makes it easy to integrate .ttl parsing into a web application.

Where to Access the SDS SDK
The BAMM SDK v2.1 is available at https://github.com/OpenManufacturingPlatform/sds-sdk/releases. The JavaScript Aspect Model Loader, specifically, can be found at https://github.com/OpenManufacturingPlatform/sds-sdk-js-aspect-model-loader.
