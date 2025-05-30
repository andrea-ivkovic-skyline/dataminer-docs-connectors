---
uid: Connector_help_Axon_ACP_-_GPD100
---

# Axon ACP - GPD100

The GPD100 is a 3 Gb/s, HD, SD embedded domain PCM to Dolby Digital (+) encoder with audio shuffler.

The **Axon ACP - GPD100** connector can be used to display and configure information related to this device.

## About

This connector is automatically generated by the connector **Axon ACP**.

There are different possibilities available for **alarm monitoring** and **trending**.

### Version Info

| Range     | Description                        | DCF Integration     | Cassandra Compliant     |
|------------------|------------------------------------|---------------------|-------------------------|
| 1.0.2.x          | Change in export rules.            | Yes                 | Yes                     |
| 1.0.3.x          | Change in discrete display values. | Yes                 | Yes                     |

### Product Info

| Range | Supported Firmware Version |
|------------------|-----------------------------|
| 1.0.2.x          | 2522, 3128                  |
| 1.0.3.x          | 2522, 3128                  |

## Installation and configuration

### Creation

This element is automatically created by the parent element using the **Axon ACP** connector.

## Usage

This element has the following data pages:

- **General**: This page displays general information about the card: **Card Name**, **Card Description**, **SW Revision**, **HW Revision**, etc.
- **Status**
- **Add-On**
- **Quad Speed**
- **Video**
- **S2020**
- **Miscellaneous**
- **Dolby**
- **Encoder**
- **Loss/Detect**
- **Pro Logic**
- **MD Status**
- **Metadata**
- **DD Metadata**
- **Audio**
- **Embedder**
- **Embedder A**
- **Embedder B**
- **Embedder C**
- **Embedder D**
- **Alarm Priority**: This page displays the event messages of the card, i.e. special messages generated asynchronously on the card.

## DataMiner Connectivity Framework

The Axon ACP connector supports the usage of DCF.

DCF can also be implemented through the DataMiner DCF user interface and through DataMiner third-party connectors (for instance a manager).

Connectivity for this protocol is managed by the parent protocol Axon ACP.

### Interfaces

#### Physical Interfaces

- **SDI Input 1**: A single fixed interface of type **input**.
- **SDI Input 2**: A single fixed interface of type **input**.
- **QUAD-SPEED SYNAPSE Bus Input**: A single fixed interface of type **input**.
- **SDI Output 1**: A single fixed interface of type **output**.
- **SDI Output 2**: A single fixed interface of type **output**.
- **QUAD-SPEED SYNAPSE Bus Output**: A single fixed interface of type **output**.
