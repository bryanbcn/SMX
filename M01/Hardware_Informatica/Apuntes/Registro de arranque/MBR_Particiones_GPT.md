# MBR DOS
(**Master Boot Record**) El registro Principal de arranque o registro, es una sector de 512 bytes al principio del disco duro que contiene una secuencia de comandos nesesarios para cargar un sistema operativo.
## Reglas
  * Máximo 4 primarias
  * Ha de haber una activa
  * Esta permitido una extended, no activa
  * Dentro de la extended puede haber "n" logicas
  * una extended no puede ser activa
### Tabla de particiones
ocupa **64 bytes**, conteniendo 4 registros de 16 bytes, los cuales definen las particiones primarias. En ellos se almacena toda la información básica sobre la partición: si es arrancable, si no lo es, el formato, el tamaño y el sector de inicio.

### Gestor de arraque
Es un programa sencillo que no tiene la totalidad de las funcionalidades de un sistema operativo, y que está diseñado exclusivamente para preparar todo lo que necesita para iniciar el sistema operativo.(Código de arranque y pesa **446 bytes**)

### Signature
usa la firma del disco como un índice en su registro, donde guarda la relación entre particiones y letras de disco.
GNU/Linux usa la firma del disco al arrancar para determinar la posición del volumen de arranque. Pesa **2 bytes**

# GPT
Es un estándar para la colocación de la tabla de particiones en un dico duro.
Es parte del estándar Extensible Firmware Interface propuesto por Intel para reemplazar el viejo BIOS del PC, 
heredada del IBM PC original.
La GPT sustituye al MBR (Master Boot Record) usado con el BIOS
