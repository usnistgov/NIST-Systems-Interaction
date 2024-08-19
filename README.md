# Overview

Systems level and integration testing are an integral part of the design and development of Automated Vehicles (AVs). Measurement science plays a pivotal role in testing to ensure the safe and efficient operation of AVs. This science establishes a common understanding of the units of measurement, crucial in linking human activities. This paper describes the significance of measurement in studying interactions between key system technologies in AVs, including artificial intelligence (AI), sensing/perception, communications, and cybersecurity. To address the complexities of these interactions, a novel, adaptable, and interactive framework is introduced. This framework considers both designed and emergent interactions between these system technologies, and enables exploration of tailored experiments by AV developers and investigators as well as allowing flexibility of filtering for focused experimentation. Moreover, the framework serves as a valuable tool for AV designers and safety regulators to aid in establishing robust design and assessment approaches. This work highlights the necessity of a common framework to comprehensively test AVs and therefore emphasizes the importance of gaining a holistic understanding of system technology interactions. Finally, the framework aims to understand how to mitigate potential influences leading to AV malfunctions to advance the development and deployment of safe and reliable automated vehicles. In future, the framework can be expanded to include additional elements, such as infrastructure or other vehicles to analyze information provided to automated vehicles allowing experts from various domains to collaborate, create similar models, and integrate them when feasible.

## Features


This repository is for the System Technology Interaction Model (STIM), a comprehensive model designed to advance the development and deployment of safe and reliable autonomous vehicles (AVs). While the STIM was demonstrated with four key system technologies (cybersecurity, communication, artificial intelligence, and perception), it is adaptable for use with additional system technologies and even expanded further allowing the inclusion of additional elements such as roadways infrastructure and other vehicles, enhancing its utility in analyzing information provided to autonomous vehicles. This promotes innovation in roadway simplification and information provision. The collaborative potential of this framework, enabling experts to develop and integrate domain-specific models, further advancing system technology interactions.


The proposed STIM consists of three primary objectives: 1) To provide a holistic understanding of system technology interactions (STIs) and their influences on AV performance, 2) To support the design, testing, and validation of AV systems by characterizing both desired and undesired interactions between system technologies, and 3) To serve as a valuable tool for AV developers, investigators, and safety regulators. The flexibility of the model allows for customization to accommodate diverse AV architectures and feature configurations, which enables designs tailored to specific AV requirements. Additionally, its ability to filter and focus on specific scenarios offers focused component testing and assessment.

The STIM is currently implemented in two formats: 1) OWL (Web Ontology Language) is used for data sharing, providing a standardized way to represent and exchange information across different systems, enhancing data interoperability. 2) A graph database is used to leverage the inherent structure of graph databases to efficiently handle complex queries about system technology interactions and offer a clear and structured model that mirrors real-world scenarios. This dual implementation ensures that STIM is both versatile in data sharing and powerful in data analysis, which makes it a robust tool for studying STIs in AVs. 

Looking ahead, future iterations of this model could benefit from the integration of large datasets containing crash information, enabling further exploration and expansion of the influences affecting AV systems. By using additional relevant data, this framework has the potential to enhance our understanding of complex interactions within AV systems and contribute to the development of safer and more reliable autonomous vehicles in the future.

## Usage

- The OWL model can be explored with Protege.
- The graph database model was developed using Neo4j. Please refer to `GraphDatabase/Instructions_to_run_STIM.pdf` for installation instructions.

## Status

While a stable version of the model has been developed, additional instances continue to be added.

# License

This project is licensed under the terms described in the LICENSE.md file.

# Contact

- OWL model: Zeid Kootbally (zeid.kootbally@nist.gov)
- Graph database: Mahima Arora (mahima.arora@nist.gov) and Edward Griffor (edward.griffor@nist.gov)

# Credits

- Edward Griffor (edward.griffor@nist.gov)
- Mahima Arora (mahima.arora@nist.gov)
- Zeid Kootbally (zeid.kootbally@nist.gov)
