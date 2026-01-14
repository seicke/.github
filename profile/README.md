<h1 align="center">Welcome to the <a href="https://eclipse.dev/basyx/">Eclipse BaSyx</a> community!</h1><br>

<p align="center">
  <a href="https://eclipse.dev/basyx/">
    <img src="https://www.eclipse.org/basyx/img/basyxlogo.png" alt="BaSyx logo">
  </a>
</p>

<p align="center">
  Eclipse BaSyx is the world's most versatile, extensible, and feature-packed open-source software <br> for working with Asset Administration Shells
</p>

---

## Table of Contents
- [Getting Started](#getting-started)
- [Repository Overview](#repository-overview)
  - [Eclipse BaSyx Java](#eclipse-basyx-java)
  - [Eclipse BaSyx Go](#eclipse-basyx-go)
  - [Eclipse BaSyx Python](#eclipse-basyx-python)
  - [Eclipse BaSyx TypeScript](#eclipse-basyx-typescript)
  - [Eclipse BaSyx .Net](#eclipse-basyx-net)
  - [Eclipse BaSyx Rust](#eclipse-basyx-rust)
  - [Eclipse BaSyx AAS Web UI](#eclipse-basyx-aas-web-ui)
  - [Eclipse BaSyx DataBridge](#eclipse-basyx-databridge)
  - [Eclipse BaSyx Applications](#eclipse-basyx-applications)
  - [Eclipse BaSyx Helm Charts](#eclipse-basyx-helm-charts)
- [Metamodel V2.0.1 SDKs (Deprecated)](#metamodel-v201-sdks-deprecated)

---

## Getting Started

> [!IMPORTANT]
> A great starting point for everything BaSyx is [BaSyx.org](https://basyx.org).  
> There, you’ll find our official documentation, additional resources, and a handy [Starter Kit](https://basyx.org/get-started/introduction) for downloading your tailored BaSyx setup.

---

## Repository Overview

Eclipse BaSyx hosts a multitude SDKs, components and applications. These include:

### Eclipse BaSyx Java
BaSyx Java V2 is fully compliant with Specification of the Asset Administration Shell Version 3. Its SDK, off-the-shelf components, documentation and examples are contained in [basyx-java-server-sdk](https://github.com/eclipse-basyx/basyx-java-server-sdk).

For its documentation, see [BaSyx Wiki](https://wiki.basyx.org/en/latest/content/user_documentation/basyx_components/v2/index.html).

### Eclipse BaSyx Go
BaSyx Go off-the-shelf components, documentation and examples are contained in [basyx-go-components](https://github.com/eclipse-basyx/basyx-go-components).

### Eclipse BaSyx Python
The [BaSyx-Python-SDK](https://github.com/eclipse-basyx/basyx-python-sdk) is an implementation of the specification of the  Asset Administration Shell in Python 3. 
It comes with JSON, XML and AASX adapters, a compliance tool, backend infrastructure and extensive [documentation](https://basyx-python-sdk.readthedocs.io/en/latest/)

### Eclipse BaSyx TypeScript
The [BaSyx-TypeScript-SDK](https://github.com/eclipse-basyx/basyx-typescript-sdk) provides client functionalities fully compliant with the Asset Administration Shell Version 3.
It is intended to be used to develop web applications using Typescript. In addition, it also provides useful utility functions for working with AAS data.

### Eclipse BaSyx .Net
BaSyx .Net is hosted in [basyx-dotnet](https://github.com/eclipse-basyx/basyx-dotnet).

### Eclipse BaSyx Rust
BaSyx Rust SDK is hosted in [basyx-rust-sdk](https://github.com/eclipse-basyx/basyx-rust-sdk). The SDK can be consumed via [crates.io](https://crates.io/crates/basyx-rs). Starting from crate version 0.2.x, it is fully compliant with the Specification of the Asset Administration Shell (Part 1: Metamodel) Version 3. 

### Eclipse BaSyx AAS Web UI
Visualize and interact with AAS in a user friendly way. The AAS Web UI allows easy management of AAS, Submodels and ConceptDescriptions while using the BaSyx off-the-shelf components. The source code is hosted in [basyx-aas-web-ui](https://github.com/eclipse-basyx/basyx-aas-web-ui).

For its documentation, see [BaSyx Wiki](https://wiki.basyx.org/en/latest/content/user_documentation/basyx_components/web_ui/index.html).

### Eclipse BaSyx DataBridge
Integrating existing assets with AAS has never been easier. Leverage the powerful DataBridge provided in [basyx-databridge](https://github.com/eclipse-basyx/basyx-databridge) for achieving quick integration without any programming expertise needed.

### Eclipse BaSyx Applications
BaSyx provides versatile applications, e.g., for database connections or OPC UA integration on-the-fly. The code for them is hosted in [basyx-applications](https://github.com/eclipse-basyx/basyx-applications).

### Eclipse BaSyx Helm Charts
This repository includes Helm Charts for all BaSyx components. You can find the Helm Charts in the [charts repository](https://github.com/eclipse-basyx/charts).

---

## Metamodel V2.0.1 SDKs (Deprecated)
> [!WARNING]
> Don't use those deprecated SDKs when starting a new project with BaSyx.  
> If you need support migrating to the new Version, plese send a mail to basyx-dev@eclipse.org
> 
Additionally to the SDKs supporting Version 3 of the API and metamodel, BaSyx provides SDKs for metamodel V2.0.1. However, since this version of the metamodel is deprecated, we strongly recommend using the SDKs listed above. 

### Eclipse BaSyx Java V1
BaSyx Java V1 is fully compliant with Details of the AAS Part 1 V2.0.1 and defines its own [API](https://app.swaggerhub.com/organizations/BaSyx). The SDK Is contained in [basyx-java-sdk](https://github.com/eclipse-basyx/basyx-java-sdk), its off-the-shelf components are provided in [basyx-java-components](https://github.com/eclipse-basyx/basyx-java-components).
For its documentation, see [BaSyx Wiki](http://basyx-wiki.readthedocs.io/) as well as [basyx-java-examples](https://github.com/eclipse-basyx/basyx-java-examples).

### Eclipse BaSyx C++
BaSyx C++ SDK is hosted in [basyx-cpp-sdk](https://github.com/eclipse-basyx/basyx-cpp-sdk).
