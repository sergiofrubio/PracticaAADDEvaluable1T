## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

# PracticaEvaluableAccesoDatos1T


Este programa contiene las clases Principal, Libro, Autor, Préstamo para la gestión de una biblioteca.

Para iniciar el programa compilaremos la clase Principal, donde se nos abrirá una terminal y, mediante ésta, podremos agregar, modificar, actualizar y eliminar libros, autores y préstamos de nuestra biblioteca.

## Libro

La clase libro contiene un menú con las opciones añadir, mostrar, modificar, eliminar libros.

## Autor

La clase autor contiene un menú con las opciones añadir, mostrar, modificar, eliminar autores.

Estas clases guardan los libros y autores en archivos binarios.

## Préstamo

La clase préstamo contiene un menú con las opciones añadir, mostrar y hacer devolución de los préstamos de la biblioteca. Esta información se almacena en documentos de texto.

## Principal

La clase principal, que es la que inica el programa, contiene un menú con las opciones necesarias para gestionar los libros, autores y préstamos de la biblioteca, así como la exportación e importación de libros y autores en XML.

Los archivos prestamos.txt, libros.bin y autores.bin se guardan en la carpeta de tu proyecto. Son rutas relativas.