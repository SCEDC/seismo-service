# seismo-service
The Seismo-Service project's primary objective is to make seismic processing code more portable and more scalable.
Contributors aim to do this by adopting a service-oriented architecture, where major components are 
accessible as services with a URL endpoint. Calls to these services return formats in json or other standards
commonly used in the seismic monitoring community.

At the Southern California Seismic Network, these services are currently used in two post-processing pipelines that interface with the AQMS realtime monitoring system. One, hypoPN, is an event post-processing system that is based on the AQMS hypomag module. The second, ST-Proc, is an automatic processing pipeline for subnet triggers. For more about these projects, please see the following publication:

Tepp, G., Yu, E., Bhaskaran, A., Tam, R., Zhu, W., Newman, Z., Jaski, E., & Scheckel, N. (2025). Improvements from incorporating machine learning algorithms into near real-time operational post-processing. Scientific Reports, 15(1), 28938, doi:10.1038/s41598-025-14491-1.

This project is a work in progress and will be updated continually when new components are released.

## Services

### Data-choice

### Data-retrieval

### Picker
https://gitlab.com/aqms-swg/aqms.nextgen/hypopn-lambda

### Pick-filter

### Associator
https://gitlab.com/aqms-swg/aqms.nextgen/associator

## Data flows
We can take the output from a service and make it the input for another to construct a pipeline that results in a product such as an earthquake catalog.

### Pipeline Scripts
### Message Library
A library for working with these formats with our services can be found at https://pypi.org/project/postprocessing-seismo-lib/0.1.1/
### Notebooks

## Formats
Formats, examples, and their specifications used in our services can be found at https://github.com/SCEDC/process-formats.
These formats are based on work done by NEIC (https://code.usgs.gov/ghsc/neic/utilities/earthquake-detection-formats)
We are working with the NEIC and the rest of the ANSS community to form standard formats that could be used by any seismic processing system. 


## Acknowledgement
If you use software from this project, please cite the SCEDC:

SCEDC (2013). Southern California Earthquake Center. Caltech. Dataset. doi:10.7909/C3WD3xH1
