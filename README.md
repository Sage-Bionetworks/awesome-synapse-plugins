# Awesome Synapse
A curated list of packages and tools using Synapse R, Python, React clients inspired by other awesome-* lists.

- [Portals](#portals)
- [R](#r)
  * [Shiny](#shiny)
- [Python](#python)
- [Java](#java)
- [Workflow](#workflow)
- [Lists](#lists)
- [Organizations](#rganizations)


## Portals
* [portals](https://github.com/Sage-Bionetworks/portals) - React component based configurations that generate community portals built on top of Synapse
* [Collaboration Portal](https://github.com/Sage-Bionetworks/sagebio-collaboration-portal) - Prototype Collaboration Portal
* [Agora](https://github.com/Sage-Bionetworks/Agora)

## R
* [syndccutils](https://github.com/Sage-Bionetworks/syndccutils) - Code for managing data coordinating operations (e.g., development of the CSBC/PS-ON Knowledge Portal and individual Center pages) for Sage-supported communities through Synapse.
* [synapseAnnotations](https://github.com/Sage-Bionetworks/synapseAnnotations/) - Sage Bionetworks derived standards for annotating content in Synapse. This provide a mechanism for defining, managing, and implementing controlled vocabularies when annotating content in Synapse.
* [sagethemes](https://github.com/Sage-Bionetworks/sagethemes) - The sagethemes package provides plot color palettes and themes that use the Sage Bionetworks branded colors.
* [challengerutils](https://github.com/Sage-Bionetworks/challengerutils) - The R version of `challengeutils`
* [dccmonitor](https://github.com/Sage-Bionetworks/dccmonitor) - This package is intended to assist Sage Bionetworks data curators to check the status of metadata and documentation files uploaded via the dccvalidator shiny application
* [mhealthtools](https://github.com/Sage-Bionetworks/mhealthtools) - A modular R package for extracting features from mobile sensor data
* [synapseforms](https://github.com/Sage-Bionetworks/synapseforms) - Wrappers for the [Synapse Forms Services API](https://docs.synapse.org/rest/#org.sagebionetworks.repo.web.controller.FormController).
* [knit2synapse](https://github.com/Sage-Bionetworks/knit2synapse) - Knit Rmarkdown files to Synapse wikis

### Shiny
* [SynapseShinyApp](https://github.com/Sage-Bionetworks/SynapseShinyApp) - Basic Shiny application for use on Sage Bionetwork's Synapse web portal.
* [data curator app](https://github.com/Sage-Bionetworks/data_curator) - Shiny application to annotate and ingest metadata (manifest) files
* [dccvalidator](https://sage-bionetworks.github.io/dccvalidator/index.html) - package and Shiny app to perform data validation and QA/QC
* [projectLive](https://github.com/Sage-Bionetworks/projectLive) - Track the impact of our funding partners in real time
* [Synodos_NF2](https://github.com/Sage-Bionetworks/Synodos_NF2_SyDE_shinyApp) - Synodos Data Explorer(SyDE) Shiny App
* [PCBC](https://github.com/Sage-Bionetworks/PCBCDataExplorer) - PCBC Shiny Application
* [shinyModules](https://github.com/Sage-Bionetworks/shinyModules) - independent shiny modules for plug n play between applications


## Python
* [s3-synapse-sync](https://github.com/Sage-Bionetworks/s3-synapse-sync) - Lambda function code to index files in S3 buckets by creating filehandles on Synapse, triggered by file changes to S3.
* [schematic](https://github.com/Sage-Bionetworks/schematic) - Python package for Biomedical Data model and Data Ingress Management
* [challengeutils](https://github.com/Sage-Bionetworks/challengeutils/pull/204/files) - Synapse challenge utility functions + more
* [synapseformation](https://github.com/Sage-Bionetworks/synapseformation) - Client for using [Synapse Formation templates](https://github.com/Sage-Bionetworks/synapse-formation-templates).
* [synapseMonitor](https://github.com/Sage-Bionetworks/synapseMonitor) - Monitor a Synapse Project / entities scoped by a Synapse file view.
* [synapsegenie](https://github.com/Sage-Bionetworks/synapsegenie) - Crawl through Synapse files to validate and process them given a plugin file format registry.
* [prov-service](https://github.com/Sage-Bionetworks/prov-service) - lightweight implementation of the Synapse Activity services, based on the PROV spec



## Java
* [SynapseWorkflowOrchestrator](https://github.com/Sage-Bionetworks/SynapseWorkflowOrchestrator) - Links one or more Synapse Evaluation queues to a workflow engine. Each Evaluation queue is associated with a workflow template. Each submission is a workflow job, an instance of the workflow template. Upon submission to the Evaluation queue the Workflow Orchestrator initiates and tracks the workflow job, sending progress notifications and uploading log files.
* [NRGRSynapseGlue](https://github.com/Sage-Bionetworks/NRGRSynapseGlue) - This is the integration of NRGR and Synapse, linking data access approval in NRGR to data access in Synapse.
* [EvaluationStatistics](https://github.com/Sage-Bionetworks/EvaluationStatistics) - This application computes statistics on the evaluation queues in Synapse.
* [Synapse-User-Geolocation](https://github.com/Sage-Bionetworks/Synapse-User-Geolocation) - An application to geolocate all Synapse users and display them on a map.



## Workflow

* [CWL Synapse Client](https://github.com/Sage-Bionetworks-Workflows/dockstore-tool-synapseclient) - CWL interface to Synapse command line.
* [nextflow Synapse Client](https://github.com/Sage-Bionetworks/synapse-nextflow) - Nextflow interface to Synapse command line.
* [rare-disease-workflows](https://github.com/Sage-Bionetworks/rare-disease-workflows) - Workflows for processing rare disease data on Synapse.


## Lists
* [Data Coordination Tools](https://github.com/Sage-Bionetworks/data-coordination-tools) - This repository gathers existing tools used for data coordination at Sage.


## Organizations
* [Sage-Bionetworks-Workflows](https://github.com/Sage-Bionetworks-Workflows) - List of dockstore tools and workflows.
* [Sage-Bionetworks-Challenges](https://github.com/Sage-Bionetworks-Challenges) - Sage Bionetworks hosts crowdsourcing challenges that examine questions in biology and medicine.
