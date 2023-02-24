# CARE - Model Example for Inference 

This repository contains a model example for inference with the [CARE Broker](https://github.com/UKPLab/CARE_broker). \
It is built on top of the [Huggingface pipeline](https://huggingface.co/docs/transformers/main_classes/pipelines) 
and can be modified to support any NLP task supported by the pipeline. \
See the CARE and Broker documentation for more information.

## Requirements

* [Docker](https://docs.docker.com/get-docker/)
* [Docker Compose](https://docs.docker.com/compose/install/)

## Build and Run

Build the Docker images

```bash
make build
```

Start the Docker containers

```bash
make run
```

Rebuild the Docker images without using the cache

```bash
make rebuild
```

Clean the Docker images

```bash
make clean
```

## Contact 

_Maintainers:_

* Dennis Zyska (dennis.zyska@tu-darmstadt.de) 
* Nils Dycke (nils.dycke@tu-darmstadt.de)

Don't hesitate to send us an e-mail or report an issue, if something is broken (and it shouldn't be) or if you have further questions.

https://www.ukp.tu-darmstadt.de \
https://www.tu-darmstadt.de


### Disclaimer

This repository contains experimental software and is published for the sole purpose of giving additional background details on the respective publication.\
The software is only tested on unix systems and is not guaranteed to work on other operating systems.

### References

* [PythonSocketIO](https://python-socketio.readthedocs.io)