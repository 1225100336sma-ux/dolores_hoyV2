# Dolores Hoy

Tablero en Flutter que consume **5 APIs gratuitas** aplicando buenas prácticas de seguridad.
Desarrollo Móvil Integral · UTNG

**Alumna:** [Tu nombre completo]
**Grupo:** [Tu grupo]
**Profesor:** Anastacio Rodríguez García

## APIs utilizadas

| # | API | Dato | Clave |
|---|-----|------|-------|
| 1 | Open-Meteo | Clima actual de Dolores Hidalgo | No |
| 2 | Frankfurter | Tipo de cambio peso-dólar-euro | No |
| 3 | Nager.Date | Próximos días festivos de México | No |
| 4 | Wikipedia (es) | Resumen de Dolores Hidalgo | No |
| 5 | NASA APOD | Foto astronómica del día | Sí |


## Pruebas

    flutter test

## Evidencia de TDD (ciclo Rojo → Verde por ronda)

En cada ronda se escribe primero la prueba, se ve fallar (rojo), se implementa lo mínimo para que pase (verde) y después se mejora el código.

### Ronda 1: Cliente seguro
**Rojo:** la prueba falla porque aún no existe `cliente_seguro.dart`.

![Ronda 1 rojo](capturas/ronda1_rojo.png)

**Verde:** con `cliente_seguro.dart` implementado, la prueba pasa.

![Ronda 1 verde](capturas/tonda1_verde.png)

### Ronda 2: Seguridad (claves y configuración)
**Rojo:**

![Ronda 2 rojo](capturas/ronda2_rojo.png)

**Verde:**

![Ronda 2 verde](capturas/ronda2_verde.png)

### Ronda 3: Servicios (las 5 APIs)
**Rojo:**

![Ronda 3 rojo](capturas/ronda3_rojo.png)

**Verde:**

![Ronda 3 verde](capturas/ronda3_verde.png)

### Ronda 4: TableroViewModel
**Rojo:**

![Ronda 4 rojo](capturas/ronda4_rojo.png)

**Verde:**

![Ronda 4 verde](capturas/ronda4_verde.png)

### Resultado final: todas las pruebas pasando
![Todas las pruebas](capturas/final_todas_verde.png)

## Evidencias

### Proceso y Funcionamiento 
![1](evidencias/imagen01.png)
![2](evidencias/imagen02.png)
![3](evidencias/imagen03.png)
![4](evidencias/imagen04.png)
![5](evidencias/imagen05.png)
![6](evidencias/imagen06.png)
![7](evidencias/imagen07.png)
![8](evidencias/imagen08.png)
![9](evidencias/imagen09.png)
![10](evidencias/imagen10.png)
![11](evidencias/imagen11.png)
