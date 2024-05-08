<p align="center">
  <img src="https://user-images.githubusercontent.com/4206926/49877604-10457580-fe26-11e8-92d7-cd876c4f6454.png" width=350/>
</p>

#

[![Workflow](https://github.com/nccgroup/ScoutSuite/workflows/CI%20Workflow/badge.svg)](https://github.com/nccgroup/ScoutSuite/actions)
[![CodeCov](https://codecov.io/gh/nccgroup/ScoutSuite/branch/master/graph/badge.svg)](https://codecov.io/gh/nccgroup/ScoutSuite)

[![PyPI version](https://badge.fury.io/py/ScoutSuite.svg)](https://badge.fury.io/py/ScoutSuite)
[![PyPI downloads](https://img.shields.io/pypi/dm/scoutsuite)](https://img.shields.io/pypi/dm/scoutsuite)
[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-rossja%2Fncc--scoutsuite-blue)](https://hub.docker.com/r/rossja/ncc-scoutsuite/)
[![Docker Pulls](https://img.shields.io/docker/pulls/rossja/ncc-scoutsuite.svg?style=flat-square)](https://hub.docker.com/r/rossja/ncc-scoutsuite/)

## Description

Scout Suite is an open source multi-cloud security-auditing tool, which enables security posture assessment of cloud environments. Using the APIs exposed by cloud providers, Scout Suite gathers configuration data for manual inspection and highlights risk areas. Rather than going through dozens of pages on the web consoles, Scout Suite presents a clear view of the attack surface automatically.

Scout Suite was designed by security consultants/auditors. It is meant to provide a point-in-time security-oriented view of the cloud account it was run in. Once the data has been gathered, all usage may be performed offline.

The project team can be contacted at <scoutsuite@nccgroup.com>.

### Cloud Provider Support

The following cloud providers are currently supported:

- Amazon Web Services
- Microsoft Azure
- Google Cloud Platform
- Alibaba Cloud (alpha)
- Oracle Cloud Infrastructure (alpha)
- Kubernetes clusters on a cloud provider (alpha)
- DigitalOcean Cloud (alpha)

## Installation

Refer to the [wiki](https://github.com/nccgroup/ScoutSuite/wiki/Setup).

## Usage

Scout Suite is run through the CLI:

![Running Scout Suite](https://user-images.githubusercontent.com/13310971/78389085-22659d00-75b0-11ea-9f22-ea6fcaa6a1cd.gif)

Once this has completed, it will generate an HTML report including findings and Cloud account configuration:

![Scout Suite Report](https://user-images.githubusercontent.com/13310971/77861662-342bf680-71e4-11ea-8eed-ccaeb78c5f45.gif)

The above report was generated by running Scout Suite against https://github.com/nccgroup/sadcloud.

Additional information can be found in the [wiki](https://github.com/nccgroup/ScoutSuite/wiki). 
There are also a number of handy [tools](https://github.com/nccgroup/ScoutSuite/tree/master/tools) for automation of common tasks.


