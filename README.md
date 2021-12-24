Origen del proyecto:
  Este proyecto se basa en la configuración de OpenLdap, expuesta en el proyecto de git: https://github.com/Ramhm/openldap

Requisitos:
  tener instalado docker y docker-compose

Notas importantes:
  1. este proyecto no contiene dockerfile, por lo que no se realiza una imagen con el. Este se basa en imagenes expuestas en el repositorio docker
     para openldap y phpldapadmin
  2. La implementacion del docker-compose de este proyecto, se realizó con base a los planteado en la documentación del proyecto git: https://github.com/Ramhm/openldap
  3. para ejecutar los contenedores, en ambiente de desarrolo,se debe correr el siguiente comando en la consola de comandos: docker-compose -f loca.yml up

  4. para ejecutar los contenedores, en ambiente de staging,se debe correr el siguiente comando en la consola de comandos: docker-compose -f production.yml up

  5. para ingresar al administrador solo debe digitar "localhost" en la barra de dirección del navegador.

