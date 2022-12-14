## OMP Helps Drive IT/OT Convergence with OPC UA Connector

### Release of the OMP Industrial OPC UA Connector
The worlds of information technology (IT) and operational technology (OT) are fast converging in manufacturing settings. As manufacturing floor operations become connected via the Internet of Things (IoT), IT and OT systems must be interoperable and able to communicate.

OPC UA is the primary vendor-independent machine protocol at the production asset level. IT systems don’t have support for OPC UA but follow streaming approaches to connectivity. Until now, there were no standalone, industrial connectors for OPC UA available that convert OPC UA to a neutral format (e.g., MQTT or Kafka) and can be purely controlled by messages. That’s why the OMP IoT Connectivity Working Group saw the need for connector software that can run at the edge.

Today, the OMP has released its <a href="https://github.com/OpenManufacturingPlatform/iotcon-opc-ua-connector-dotnet" target="_blank">open-source OPC UA connector</a> to link automation equipment to the world of IT- and cloud systems. The connector is already in permanent usage in production critical systems at the BMW Group and allows streaming of OPC UA data to MQTT or Kafka endpoints.

Due to its ongoing application in worldwide manufacturing plants, the connector offers a proven feature set tailored for production. This includes the support of registered reads/writes (OPC 10000-4) which increases speed by a factor of 10, especially on Siemens PLCs (see <a href="https://cache.industry.siemens.com/dl/dl-media/906/109776906/att_1032258/v1/109776906_OPCUA_6_Performance_WBT_EN/start.html?lang=en" target="_blank">here</a>). High-throughput data access is possible with minimal impact on the controller’s cycle time. Also, there is support for structured data types to get consistent access to complex data structures for use by MES systems. Special attention was also paid to logging messages in order to easily pinpoint errors during operation or setup.

The connector supports northbound connections to arbitrary MQTT or Kafka brokers. This results in an easy setup system without dependencies on other services. Changes and data exchange are possible during runtime configuration via the streaming interfaces (MQTT or Kafka).

![image](https://user-images.githubusercontent.com/3258579/207704008-b9a331f9-2836-4fb3-af6e-a0da628b1aee.png)

The connector can be installed standalone on edge devices or be orchestrated on container platforms such as Kubernetes. It supports <a href="" target="_blank">OPC UA in Version v1.04</a> and is available under the MIT license. Following the OMP principle of openness, our code base is publicly available and ready for further extensions.

Get further information on GitHub:
<a href="https://github.com/OpenManufacturingPlatform/iotcon-opc-ua-connector-dotnet" target="_blank">https://github.com/OpenManufacturingPlatform/iotcon-opc-ua-connector-dotnet</a>
