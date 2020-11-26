# pdi-config

## Introducción
La plataforma de interoperabilidad de AGESIC es una solución que brinda capacidades de integración y middleware entre proveedores y consumidores de servicios. Entre otras, provee la funcionalidad de ruteo de invocaciones a servicios, esto permite ocultar los endpoints a los consumidores y aplicar maniobras sobre los mismos de forma transparente para los consumidores. Todas las invocaciones a servicios a través de la plataforma serán redireccionadas por medio del servicio de ruteo.

## Descripción de la solución
Este proyecto contiene los archivos de configuración de toda la solución, ya sea ![pdi-ruteo](https://github.com/AGESIC-UY/pdi-ruteo) o ![publish-and-suscribe](https://github.com/AGESIC-UY/publish-and-suscribe). En particular, se encuentra un archivo de configuración para cada uno de los microservicios de cada proyecto, donde cada uno se separa de acuerdo a los distintos ambientes que se tengan. Obviamente esto puede ser adaptado a los ambientes que disponga para ejecutar. Además, se pueden encontrar archivos de configuración para el consumo de servicios de la PDI.

## Ejecución
Para utilizar este proyecto se debe disponibilizar en un repositorio Git, accesible por los microservicios que se vayan a utilizar. La URL de acceso a este repositorio se deberá configurar en el microservicio _config_ que se encuentra en el proyecto ![pdi-core](https://github.com/AGESIC-UY/pdi-core).

## Contacto
Por cualquier duda o consulta, puede comunicarse a arquitectura@agesic.gub.uy

---

## Introduction
AGESIC's interoperability platform is a solution that provides integration and middleware capabilities between service providers and consumers. It provides the functionality of routing of invocations to services, among others, allowing to hide endpoints from consumers and operate transparently with them. All invocations to services through the platform will be redirected through the routing service.

## Solution description
This project contains the configuration files to run the solutions, either ![pdi-routing](https://github.com/AGESIC-UY/pdi-ruteo) or ![publish-and-subscribe](https://github.com/AGESIC-UY/publish-and-subscribe). There is a configuration file for each of the microservices in each project, and they are splited according to the different environments we can execute. Obviously this can be modified according to your environments. In addition, you can find configuration files for the consumption of PDI services.

## Execution
To use this project, it must be made available in a Git repository, accessible by the microservices that will be executed. The access URL to this repository must be configured in the _config_ microservice found in the project! [Pdi-core] (https://github.com/AGESIC-UY/pdi-core).

## Contact
If you require any further information, please contact arquitectura@agesic.gub.uy


