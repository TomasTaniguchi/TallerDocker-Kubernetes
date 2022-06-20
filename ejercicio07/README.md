## Ejercicio N°4

**JobVacancy**

- Se estan ejecutando dos contenedores, _ejercicio07_web_1_ y _ejercicio07_db_1_
- Los contenedores estan basados en las siguientes imagenes.
  web: _nicopaez/jobvacancy-ruby:1.3.0_
  DB: _postgres:latest_
  Se puede validar utilizando _docker images_
- Puedo leer el docker-compose y entender/saber a que refiere cada campo "key":"value" dado que son transparentes, pero no se toda la teoría detrás.
- Aunque cada contenedor corre de forma aislada entre si, estos estan en la misma "network" por ende se pueden comunicar.
  Utilizando _docker network ls_ podemos validar esto, en el listado estara **ejercicio07_default** el cual pertenece a los contenedores creados por el compose.
