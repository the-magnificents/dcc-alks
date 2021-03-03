# Geospatial Computing Platform

**Date:** 12 March 2021

**Time:** 10:00

**Program:**
* Architectural aspects o the Geospatial Computing Platform
* Demo 

## Speaker  

**Serkan Girgin**. Serkan is an Assistant Professor in the ITC Faculty, University of Twente; and the head of the [Centre fo Expertise in Big Geodata Science.](https://www.itc.nl/research/research-facilities/labs-resources/itc-big-geodata/)


## Summary

This talk will focus on the architectural aspects of a computing cluster using specialized NVIDIA Jetson AGX computing units and different specialized servers for the Geospatial Computing Platform. The platform allows fast parallel and distributed computing. Each computing unit has 8-core ARM v8.2a 64-bit CPU, 512-core Volta GPU with Tensor Cores, 32GB 256-bit LPDDR4 RAM, and 10 TB dedicated storage. They operate at 10–30W ensuring low energy footprint, albeit high performance.

Each computing unit can be used individually for geospatial data analysis and computing purposes by leveraging their multi-core processing capabilities. But they can also be used all together as a single cluster for big data computing. The platform features managed and ready-to-use Dask, Apache Hadoop, and Apache Spark clusters. All clusters can be monitored through web interfaces.

The platform provides each user with a containerized and isolated working environment that ensures privacy. User's assets are protected against hardware failures by replicated storage with minimum two copies. Software packages are ready to use out-ot-the-box, without any further setup required. They are also kept up to date. Most of the packages are manually configured and fine-tuned to ensure best performance by utilizing multi-threaded and GPU-assisted low-level libraries. The default interface of the platform is JupyterLab, which enables users can work with interactive notebooks and documents through text and code editors, terminals, and other custom components (e.g. map widgets). For more information read this [newsletter.](
https://www.itc.nl/research/research-facilities/labs-resources/itc-big-geodata/newsletter/issue/2021-1/#geospatial-computing-platform)