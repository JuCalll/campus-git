# campus-git

Este es el repositorio de CampusStatus, del Campus Digital.

En este caso, su función es reportar, por medio de la consola, si la instancia del campus se encuentra disponible.

En este repositorio se puede encontrar el siguiente contenido:

* CampusStatus.java: Encargado de imprimir el estado de la instancia.

¿Qué diferencia observó entre un archivo modificado, preparado y confirmado?

* Al modificar un archivo cambia dentro del directorio de trabajo, pero en ese caso, Git no lo considera como parte del registro, identificando el archivo como modified, donde el cambio solo existe en el disco. El archivo preparado, después del comando git add, pasa al área de preparación, donde se organiza el contenido exacto del siguiente commit. Básicamente el cambio ya fue seleccionado, pero no registrado. El archivo confirmado, con el git commit ya forma parte del historial con un identificador único, y a partir de ese punto es recuperable. La diferencia práctica es que la preparación permite decidir qué entra y qué no en cada registro, en lugar de confirmar todo lo que se haya tocado.

¿Por qué tres commits pequeños son más útiles que uno solo?

* Cada commit responde a una intención específica, y de esa manera, el historial se puede leer como una explicación de la evolución contínua del proyecto. Si ocurre un error en el proceso, se puede identificar el commit exacto en el que falló, y de esa manera revertir el problema. Además, un commit pequeño es revisable: se entiende fácil, y es sencillo de corregir.

¿Qué mensaje de commit considera más claro y por qué?

* "feat: se incluyó el nombre la instancia dentro del mensaje de estado del proyecto", principalmente porque nombra la intención clara del cambio sin dar vueltas.



Estado del Proyecto



\## Uso del repositorio

