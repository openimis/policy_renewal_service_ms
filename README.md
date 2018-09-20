# openIMIS - Policy Renewal Windows Service

The openIMIS Policy Renewal Windows Service is a service which is executed periodically
to check if there are policies that have to be renewed and mark them appropriately. 
It is built as Windows service, running in the background. 

## Getting Started

These instructions will get you a copy of the project up and running on your local 
machine for development and testing purposes. See deployment for notes on how to 
deploy the project on a live system.

### Prerequisites

In order to use and develop the openIMIS Policy Renewal Windows Service on your local 
machine, you first need to install:

* [openIMIS Database](https://github.com/openimis/database_ms_sqlserver)
* [openIMIS Web Application](https://github.com/openimis/web_app_vb) (optional, 
but facilitates the insuree registration for testing of this component)


### Installing

To make a copy of this project on your local machine, please clone the repository.

```
git clone https://github.com/openimis/policy_renewal_service_vb
```

You can then compile and execute the service. All configuration (database connection, 
schedule) is donned within the Settings form found by opening the menu from the task tray. 

## Deployment

For deployment please read the 
[installation manual](https://openimis.readthedocs.io/en/latest/web_application_installation.html#install-windows-services).

## Built With

* [Visual Studio](https://visualstudio.microsoft.com/) 

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/openimis/policy_renewal_service_vb/tags). 

<!--## User Manual 

The user manual can be read on [openimis.readthedocs.io](http://openimis.readthedocs.io/en/latest/user_manual.html).
-->

## License

Copyright (c) Swiss Agency for Development and Cooperation (SDC)

This project is licensed under the GNU AGPL v3 License - see the [LICENSE.md](LICENSE.md) file for details.
