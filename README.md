# Explicación
Después de configurar el fichero .travis.yml, Travis ha iniciado dos construcciones simultáneas del código. Al ejecutar **mvn clean build** en la fase **script:** se han descargado todas las dependencias definidas en el fichero pom.xml, posteriormente se ha compilado el código del proyecto y se ha empaquetado. Ambas construcciones han sido satisfactorias.
