# Guía básica de Git y GitHub

## Control de versiones para el alumnado de 2º ASIR del IES Clara del Rey

**Git** es un sistema de *control de versiones distribuido* que permite guardar el historial de cambios de un proyecto. En el ciclo de ASIR del IES Clara del Rey lo usamos en máquinas virtuales Ubuntu para entregar las prácticas. Para empezar a usarlo se ejecuta `git init` y, para guardar cambios, `git commit`.

### Comandos básicos

```bash
git clone git@github.com:usuario/repositorio.git
git add fichero.txt
git commit -m "Mensaje del commit"
git push
```

### Pasos para trabajar con un repositorio

1. Clonar el repositorio remoto.
2. Hacer cambios en los ficheros.
3. Confirmar los cambios con un commit.
4. Subir los cambios a GitHub con push.

### Ventajas de usar Git

- Guarda el historial completo del proyecto.
- Permite trabajar en ramas independientes.
- Facilita el trabajo en equipo.
- Permite volver a versiones anteriores.

### Enlaces

- Web oficial del instituto: [IES Clara del Rey](https://site.educa.madrid.org/ies.claradelrey.madrid/)
- Más información sobre ramas en el documento secundario: [Ver detalles](docs/detalles.md)

### Sistema operativo utilizado en las prácticas

![Logo de Ubuntu](assets/mi-imagen.png)

### Nuestro centro: IES Clara del Rey

![IES Clara del Rey](https://upload.wikimedia.org/wikipedia/commons/thumb/2/28/I.e.s._clara_del_rey_%28Prosperidad%2C_Madrid%29.jpg/960px-I.e.s._clara_del_rey_%28Prosperidad%2C_Madrid%29.jpg)

*Imagen: "I.e.s. clara del rey (Prosperidad, Madrid)" por ANAGSPC, Wikimedia Commons, licencia CC BY-SA 4.0.*

### Tabla de comandos

| Comando | Función | Ejemplo |
|---------|---------|---------|
| git clone | Copia un repositorio remoto | `git clone git@github.com:user/repo.git` |
| git commit | Guarda los cambios en el historial | `git commit -m "mensaje"` |
| git push | Sube los cambios al remoto | `git push origin main` |
