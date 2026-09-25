# PowerBiPracticas
#Carga de datos
Se cargo el archivo de Excel seleccionando
<img width="1615" height="817" alt="image" src="https://github.com/user-attachments/assets/c12348ac-0233-4cc1-b4e4-93ccdd48828e" />

#Transformación de datos en Power Query
Se selecciona la tabla y se da clic en transformar datos
<img width="77" height="97" alt="image" src="https://github.com/user-attachments/assets/35054ac2-b39a-4ad5-a160-9c789b5a412b" />
Esto abre Power Query 

#Transformación de datos
Primero se comienza por renombrar las columnas por nombres más claros por que los nombres que tiene por defecto no lo son
<img width="387" height="31" alt="image" src="https://github.com/user-attachments/assets/ca5c522e-0381-4692-bd1c-32b1b07ebad8" />
<img width="485" height="27" alt="image" src="https://github.com/user-attachments/assets/effee865-1a42-44ab-b866-a8745b2a5111" />

Seguidamente de seleccionar el tipo correcto para cada campo por ejemplo fecha para los campos de fecha verificando que no sean texto por que esto puede afectar para el filtrado de datos en Power Bi
esto se hace desde la pestaña superior izquierda de las columnas.
<img width="256" height="266" alt="image" src="https://github.com/user-attachments/assets/cc86b8c0-91be-473f-9544-38dcc9a6a602" />

Despues se eliminan las filas duplicas desde este campo
<img width="191" height="218" alt="image" src="https://github.com/user-attachments/assets/ec760a41-a26f-4afd-88d4-d783bcca64b6" />
Aprovechando ese campo tambien se puede seleccionar quitar filas en blanco y esto elimina las filas donde en todos los campos o columnas los campos son nullos

Para gestionar los valores nulos se pueden dejar en blanco o remplazándolos con un valor por defecto justificado en este caso se coloco n/a diciendo que no aplica en columnas como telefonos,email, en general en campos de texto.
En campos numéricos como porcentajes o precios se sustitullo por un valor numéricos 0 
Para sustituir los campos se da clic derecho sobre la columna y clic en sustituir valores por ejemplo  
<img width="692" height="292" alt="image" src="https://github.com/user-attachments/assets/274002f2-7b2d-4d4e-ad72-2ad3949561d2" />

# Normalizar estructura
Una vez transformados los datos se crean dos copias para la tabla clientes y transacciones
<img width="177" height="101" alt="image" src="https://github.com/user-attachments/assets/4f92624f-df0a-4fc4-800f-c7ba863ebb05" />

Cada una de ellas con sus datos correspodientes
Clientes:
<img width="1432" height="50" alt="image" src="https://github.com/user-attachments/assets/4604cd4a-5c4c-4cd7-8cbb-a2a403b6c715" />
Transacciones:
<img width="1431" height="27" alt="image" src="https://github.com/user-attachments/assets/de3562ba-0326-43c5-88c0-62c67d23cd99" />






