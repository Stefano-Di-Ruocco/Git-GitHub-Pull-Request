# ¿Qué es una Pull Request ?

Una Pull Request (Solicitud de Extracción o Fusión) es un mecanismo utilizado en plataformas de control de versiones como GitHub, GitLab o Bitbucket. Permite a los desarrolladores notificar a los miembros del equipo que han completado una funcionalidad en una rama secundaria y desean fusionar esos cambios en la rama principal (generalmente `main` o `master`).

## ¿Para qué sirve?
Sirve principalmente para facilitar la revisión de código y la colaboración. Antes de integrar el código nuevo, el equipo puede discutir los cambios, sugerir mejoras y asegurarse de que no haya errores, manteniendo así la calidad del proyecto.

## Ventajas
* **Calidad del código:** Permite que otros ojos revisen el trabajo, encontrando bugs que el autor original podría haber pasado por alto.
* **Seguridad:** Protege la rama principal de cambios rotos o incompletos.
* **Documentación histórica:** Queda un registro claro de quién hizo qué cambios y, lo más importante, *por qué* se hicieron (a través de los comentarios en la PR).
* **Feedback y aprendizaje:** Es una herramienta excelente para que los desarrolladores junior aprendan de los senior mediante comentarios en el código.

## Desventajas
* **Cuello de botella:** Si el equipo tarda mucho en revisar las PR, el desarrollo se detiene y se acumulan cambios pendientes.
* **Contexto:** A veces es difícil para el revisor entender el contexto completo del cambio sin una buena descripción.
* **Conflictos:** Cuanto más tiempo pase una PR abierta, más probabilidades hay de que surjan conflictos de fusión con otros cambios.