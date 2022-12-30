---
title: "Project Organization"
date: 2022-11-01T16:32:53+01:00
---

The open-electrons project has been organized into several sub-projects or sub-modules where each of the project or module does
one thing. Currently, it consists of the following high level projects:

**ocpp-scala**

This project aims to capture and abstract the messages and data types around the OCPP protocol. It also attempts to define
and group the request and response based on the sender and receiver which could either be a Charging Station (CS) or a
Charging Station Management System (CSMS). Have a [look here](https://github.com/open-electrons/ocpp-scala) for the project's 
source code repository. Have a look here for the latest [releases](https://github.com/open-electrons/ocpp-scala/releases) 
and [packages](https://github.com/orgs/open-electrons/packages?repo_name=ocpp-scala). Please note that only the OCPP
protocol version 2.0.1 is supported.

**ocpi-scala**

This project aims to capture and abstract the messages and data types around the OCPI protocol. It also attempts to define
and group the request and response based on the sender and receiver which could either be a Charge Point Operator (CPO) or a
Charging Station Management System (CSMS). Have a [look here](https://github.com/open-electrons/ocpi-scala) for the project's 
source code repository. Have a look here for the latest [releases](https://github.com/open-electrons/ocpi-scala/releases) 
and [packages](https://github.com/orgs/open-electrons/packages?repo_name=ocpi-scala). Please note that only the OCPP
protocol version 2.2 is supported.

**ocpp-example-server**

This project serves as a reference implementation by using the ocpp-scala project as a library. It defines and abstracts
the Websocket implementation as laid out by the OCPP specification. This should represent the behavior of a CSMS to which
several CS might connect. Have a [look here](https://github.com/open-electrons/ocpp-example-server) 
for the project's source code repository.

**emsp-platform-server**

This project serves as a reference implementation by using the ocpp-scala and ocpi-scala projects as a library. It defines 
the use cases needed for the operation of an eMobility Service Provider (eMSP). Have a 
[look here](https://github.com/open-electrons/emsp-platform) for the project's source code repository.
