## ARCHIVO README
Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos

### Zonas de Git
1. Directorio de trabajo
2. Área de preparación
3. Directorio Git

### Flujo de trabajo básico en Git
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiéndolos a tu área de preparación.
3. Confirmas los cambios, lo que toma los archivos tal y como están en el área de preparación y almacena esa copia instantáneamente de manera permanente en tu directorio de Git.

###Configurando Git por primera vez
```
git config --global user.name "Carlo Renato"
git config --global user.email "renato.carlo19@comunidad.unam.mx"
git config --global core.editor Atom
git config --list
```

Algunos commits importantes

`git log --decorate --graph --oneline --all`

`git tag -a mi_etiqueta -m "Mensaje"`

`git show #23493 o etiqueta`

`git tag nombre_etiqueta #hash`
