
/--------MILESTONE-> DOCUMENTACIÓN <-------------/  
- ~~Documentar con PyDoc las clases del modelo -> C~~  
    Enlace de interes.. [documentar en python.](http://mundogeek.net/archivos/2008/07/07/documentacion-en-python/)  
    Ejemplo:
    ```python
        def sumar_dos_numeros(a, b):
        """Suma dos números y retorna su resultado

        Argumentos:
        a -- primer sumando
        b -- segundo sumando

        Test:
        >>> sumar_dos_numeros(25, 10)
        35
        >>> sumar_dos_numeros(30, 20)
        50
        """
        return a + b
    ```
- ~~Documentar la clase manejadora Index.py (solo lo necesario)  ->~~ F
- ~~Documentar el archivo de despliegue  -> V~~
- ~~Documentar Docker  -> C~~

/--------MILESTONE-> HITO 4 <-------------/
- ~~NUEVO ISSUE-> PASAR ANTERIOR DOCUMENTACION A UN SOLO README.md -> F~~
- NUEVOS ISSUE: UNO POR COMPAÑERO -> AÑADIR ENLACES A COMMITS, PULL REQUEST Y ISSUES EN TODOS LOS QUE SE HAYA PARTICIPADO HASTA AHORA -> *CADA UNO EL SUYO*

## PROPUESTA PARA EL HITO 4
###PROVISIONAMIENTO:
- Hacer la documentacion del script y meterlo en la documentacion del hito 4
- Cambiar algo del script
- Meterlo en la web del proyecto

------------------------------------------

###TEST:
- Cambiar la funcion del testeo por algo con sentido
- Hacer la documentacion de dicha funcion y del Hito 4
- Hacer la web del testeo

----------------------------

###INTEGRACIÓN CONTINUA:
- Documentación del Script del Shippable
- Describir el proceso del Sniphable en el hito 4 respecto a la Integración continua
- Descomentar las lineas comentadas del Shippable

--------------------------

### DESPLIEGUE:
- Buscar información de como podría configurarse el Shippable para Azure o otra máquina
- Describir el método de despliegue que sigue Shippable
- Describir como despliega el SDK si no tuviese Shippable
