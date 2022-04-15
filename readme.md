# sobre la configuracion

esta es mi configuracion para usar mi teclado corne. Uso como base el layout de Dvorak pero tiene ligeros cambios para mi uso. acontinuacion dejo imagenes sobre como quedan el layout principal y las dos capas que agrege.

## layout y capas 

capa principal (todas las teclas en blanco corresponden a Dvorak)
![layout principal](/documents/cape0.png)

capa 1 => simbolos y numeros (las teclas vacias no las uso)
![simbolos y numeros](/documents/cape1.png) 
 
capa 2 => navegacion (las teclas vacias no las uso)
![simbolos y numeros](/documents/cape2.png) 

### sobre el uso

hay una carpeta llamada .build que contiene todos los elementos para poder hacer el flasheo usanda QMK TOOLS. Pero si se desea hacer todo el proceso se puede usar los siguientos comandos desde QMK MSYS.

Para compilar
```
qmk compile -kb crxbd -km hikdul
```
para shipear
```
qmk flash -kb crxbd -km hikdul
```


