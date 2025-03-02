# Mi primer repositorio
Parte 6: Resolución de conflictos
<El conflicto surgió porque ambas ramas (main y dev) modificaron la misma línea en el archivo script.js. Git no pudo decidir cuál de las dos versiones mantener y, por lo tanto, generó un conflicto. Este conflicto se detectó cuando intentamos realizar una fusión con git merge dev, lo que mostró el mensaje de conflicto en la terminal.
Para resolverlo, abrimos el archivo, editamos las líneas en conflicto y decidimos qué versión mantener o combinar. Después de editar el archivo, lo añadimos al área de preparación y confirmamos los cambios con un commit. Esto resolvió el conflicto y completó la fusión correctamente.>
Parte 7: Investigación sobre colaboración en equipo con Git y GitHub
Preguntas de investigación:
1.¿Qué es un repositorio remoto y en qué se diferencia de uno local?
<Un repositorio remoto es un repositorio alojado en un servidor (por ejemplo, en GitHub), mientras que un repositorio local es el que se encuentra en tu máquina.>
2.¿Qué es un "fork" en GitHub y cómo se usa en proyectos colaborativos?
<Un fork es una copia de un repositorio, que permite a los desarrolladores modificar el código sin afectar al repositorio original. Es común en proyectos de código abierto.>
3.¿Qué es un "pull request" (PR) y cuál es su propósito? Describe el flujo de trabajo típico.
<Un pull request es una solicitud para fusionar cambios desde una rama o repositorio a otro. Se usa en flujos de trabajo colaborativos para revisar y discutir los cambios antes de integrarlos.>
4.¿Qué son los "issues" y los "proyectos" en GitHub? ¿Para qué sirven?
<Issues son problemas o tareas que necesitan ser resueltos, y proyectos permiten organizar el trabajo y hacer seguimiento de los avances.>
5.Explica la importancia de las ramas en un entorno de trabajo colaborativo. ¿Cómo se suelen organizar las ramas en proyectos grandes (ejemplo: main, dev, feature)?
<Las ramas permiten a los desarrolladores trabajar en diferentes características sin interferir con la rama principal. En proyectos grandes, las ramas comunes son main, dev, y ramas específicas para características (feature).>