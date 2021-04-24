# mvn-releases

Utiliza el plugin "maven-release" para crear releases con tag de versiones

Comandos:

- Nuevo branch para la versión de la release

  mvn release:branch -DbranchName=release-x.x.x

- Branch listo para desplegar en pro

  mvn release:preprare ---> Crea la versión de la nueva release y prepara el siguiente -SNAPSHOT <br/>
  mvn release:perform  ---> Genera el tag de la versión, la cual será mezclada con nuestro repositorio main y desplegado en producción.




 
