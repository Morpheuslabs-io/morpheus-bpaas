[![Morpheus Logo](https://avatars1.githubusercontent.com/u/34614083?s=200&amp;v=4)](http://morpheuslabs.io/)
# Morpheus Labs

# MORPHEUS BLOCKCHAIN PLATFORM AS SERVICE BPaaS
This is the entry point for the public regarding our development progress.
## Disclaimer
Our aim is to provide high transparency about our platform development progress. We care that our users get to know about our continuous effort into the development. Our aim is to make public everything the user needs in order to use our platform:
 - Sample applications for different blockchain technologies that will be possible to deploy in our platform
 - Technology stack recipes that we use in order to automate the blockchain deveopment
 - Language Services agents able to facilitate smart contract development in our CDE
 - Other open source components are dedicated to facilitate the user interaction/integration with our platform core components

 However, for the core modules of our proprietary code will be maintained in private repositories.

# Description
Our project aims to create a Blockchain Platform As Service that simplifies and expedites blockchain application development.
Our first goal is to give to project teams the flexibility to easy choose between different programming languages and blockchain runtimes that better suit your needs. To achieve the goal we are creating end-to-end solution for faster development in Blockchain.

![Morpheus BPaaS](./img/ML_Archi.png) The image above shows the high level architecture. The technologies shown are only exemplificative as the final choice may vary in time.

![ML BPaaS App](./img/App-Arch-01.PNG) The image above is an high level application architecture showing the Key components of the ML BPaaS.

##  CDE
  - Cloud IDE. Our IDE is a custom implementation of the opensource Eclipse Che (https://www.eclipse.org/che/), one of the most powerful cloud IDE for collaborative development. We are also adding remote project development capabilities (via SSH/WebHTTPs) to make local IDEs like VSCode (https://github.com/Microsoft/vscode) and Atom via Nuclide (https://github.com/facebook/nuclide) able to connect to our CDE.
  - For Blockchain Developers we provide dedicated Workspaces Orchestration for Organisations/Teams/Subteams
  - Git capabilities for teams repositories and Version Control
  - Blockchain runtimes as single (eg. only dev machine) or multiple machines(eg. Dev Machine, Test, Live Nodes, Other..)
  - A list of preconfigured blockchain development stacks for various development needs. All new stack recipes , aside the existing predefined by our team, will be published in https://github.com/Morpheuslabs-io/BaaS-recipes. A stack recipe is like a composer file that compose up the entire technology stack necessary for code, teste nd deploy.
  - Developers shall be able to select any blockchain and develop it in any language they are competent in. For this purpose using our CDE we aim to give a plenty of language services choice (eg. Go, Python, Java, Solidity, C++, .Net ...). Our effort to add more languages in our cloud CDE started here https://github.com/Morpheuslabs-io/morpheus-cde

  For more information about Morpheus BPaaS CDE https://github.com/Morpheuslabs-io/morpheus-cde

##  App Store (App Library)
Application store is a crowdsourced marketplace to curate all blockchain-based applications. It allows seekers to browse for ideas that suit their businesses and purchase ready-to-use or customised products; it also allows contributors to promote their applications.

  For more information about App Store https://github.com/Morpheuslabs-io/morpheus-app-store

## Blockchain Sample Application
### Ethereum based sample applications
  This repo is dedicated to our collection of samples DApps and smart contract related apps. These application may have been modified from the original samples applications available in other repositories, to be used in Morpheus Labs BPaaS. The sample applications can be used as Tutorial or a starting point for further prototyping.
  https://github.com/Morpheuslabs-io/ethereum-sample-apps
## Blockchain Operation Console
The Operations console aggregates the operational activities required to monitor and manage the Blockchain network provisioned on the platform. The Blockchain network are are managed by Blockchain Operation Console are Ethereum, HyperLedger Fabric, NEM (https://nemlibrary.com/) and Multichain. More blockcahin networks will be added in future. Details about "Blockchain Operation Console" https://github.com/Morpheuslabs-io/morpheus-ops-console.

## Membership Management

This module manages platform service subscription for all the users. The following diagram shows the high level flow.

![ML BPaaS_Membership](./img/membership.PNG)






