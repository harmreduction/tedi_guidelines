# TEDI guidelines expansion for data collection and sharing

The mexican project (Programa de Análisis de sustancias - **PAS**) is working together with the NGO [Deliberar](https://deliberar.org/) towards building a national early alert system with their government (**Observatorio Nacional de Drogas**). The Organization of American States (OAS) has entrusted Deliberar representatives to be its advisors for the development of the observatory.

The development of **PAS** provides a suitable framework for developing an open source and standardized toolset for any organization offering Drug-Checking services.
The toolset will enable an organization to be ready to collect data and will provide them with an easy way to share their data with a global early warning system (i.e. TEDI, [EMCDDA](https://www.emcdda.europa.eu/)). 

This repository contains a YAML file with a proposed expansion schema of the [TEDI Guidelines](https://www.tedinetwork.org/guidelines/) for Drug Checking Data collection [`tedi_schema.yaml`](https://github.com/harmreduction/tedi_guidelines/blob/main/tedi_schema.yaml). It's definitions will be implemented during the development and testing of the Observatory's toolset allowing for an oppen contribution to the evaluation and update of the guidelines.


## The general proposal includes:

1. Making the TEDI guidelines [FAIR](https://www.go-fair.org/fair-principles/) compliant by defining:

    -  Data annotation protocols with queriable universal unique identifiers UUIDs (**F**indability)
    -  Data access, sharability, and anonymization protocols (**A**ccessability)
    -  Requirement levels for the fields (**I**nteroperability)
    -  Data types of each field (Variables) (**R**eusability)
    -  A `vocabulary_set` data type for specific fields (I, R)

2. Defining a **TEDI Minimal Standard**.
 
 Based on the current version of the TEDI guidelines, the FAIR-compliant minimal standard will provide an organization with the core information needed for a Drug-Checking service to be able to start working and set up their tools for data collection and sharing.
 
3. Defining TEDI's Standard Expansions -**Xp** that are context-specific:
  
    - Testing methods Xps, expansions for the data collection according to the performed testing method 
    - Types of service Xps, expansions for the data collection according to the type of service (consumption room, festival setting, street outreach)

4. Developing data collection tools implementing the TEDI standards.

    - A prototipe tool using the TEDI schema is under development at: https://github.com/ViewsOnDrugs/deliberar_db

5. Involve existing and future drug-checking services to take part of the development of the standards and data collection tools.

## Sources:

PAS: https://www.analizatusustancia.org/iniciativa.html
TEDI Network https://www.tedinetwork.org/

## Collaborators:

Deliberar https://deliberar.org/
VIVID e.V. https://vivid-hamburg.de/
