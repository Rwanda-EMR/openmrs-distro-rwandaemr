![alt tag](readme/rbc_logo.png)
# Artifacts for the OpenMRS distribution for Rwanda

This repository maintains the 'distro POM' for the OpenMRS distribution for Rwanda. It downloads and brings in one place all artifacts needed by the distribution, simply run:
```
mvn clean package
```
### Target inventory:

* `openmrs_modules/`
<br/>The required set of OpenMRS modules.
* `openmrs_config/`
<br/>The OpenMRS bespoke configuration (more [here](https://github.com/Rwanda-EMR/openmrs-config-rwandaemr.git)) to be processed by the [Initializer module](https://github.com/mekomsolutions/openmrs-module-initializer).
* `openmrs_core/`
The target version of OpenMRS Core.
