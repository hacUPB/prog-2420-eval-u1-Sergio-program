### Ejercicio estacionamiento:
2 primeras horas = $5 | siguientes 3 horas = $4 | siguientes 5 horas $3 | después de 10 horas = $2
```
Inicio
Leer horas 
Si horas<= 2 entonces
    costo= (horas*5)
    Si no
    Si 2 <horas<= 5
        costo= ((horas-2)*4)+10
        Si no
        Si 5 <horas<=10
        costo = ((horas-5)*3)+22
        si no
        costo (horas*2)
        Fin si
    Fin si
Fin si
Fin
```