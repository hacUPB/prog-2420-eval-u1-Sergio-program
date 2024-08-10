## Pseudocódigo ejemplo 6:
- Definición de problema:
Dar la edad exacta de una persona, teniendo en cuenta la fecha actual y la fecha de nacimiento.
- Variables a usar: 
Se usarán las variables Día, Mes, Año, Día_actual, Mes_actual, Año actual y Edad.
### Pseudocódigo: 
```
Inicio 
    Leer Día_actual Mes_actual Año_actual  
    Leer Día Mes Año  
    Definir Edad como (Año_actual-Año)  
    Si Mes_actual>Mes entonces  
        Si Día_actual>Día entonces  
            Print Edad
        Si no 
            Print Edad-1
        cerrar si
    cerrar si
    Si Mes_actual=mes
        Si Día_actual=Día entonces
            Pirnt Feliz cumpleaños
            Print Edad
        Cerrar si
    cerrar si
Fin
```
## Pseudocódigo ejemplo 1:
- Definición del problema:
Calcular promedio de notas.
- Variables a usar:
Se usarán las variables cant (cantidad de materias), nota, sumatoria, promedio.

### Pseudocódigo:
```
Inicio
    Leer Cant Notas 
    Definir sumatoria como 0
        Para cada nota desde 1 hasta cant hacer
            Leer nota 
            Sumar nota a sumatoria
        Fin para
        promedio=sumatoria/cant
            Si promedio>3
            Print "Aprobado"
            Si no print "Reprobado"
            Fin si
Fin 
```

### Pseudocódigo ejemplo 4:
- Definición de problema:
Determinar distancia recorrida conociendo velocidad y tiempo.
- Variables a usar:
velocidad, tiempo, distancia.

```
Inicio
            