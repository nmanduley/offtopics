# offtopics
Historial de offtopics actualizado

# Descripcion de archivos
1. offtopic_history.csv: 	Conteo de offtopics y orden de presentacion (excepto Santi y Daniel,
							que solo se incluyen para llevar el conteo)
						 
2. monitor.ipynb: 			Notebook con los scripts para leer y modificar offtopic_history.csv
							usando pandas. Incluye rutinas para determinar el siguiente presentador
							(segun el orden establecido) y actualizar manualmente la tabla.

3. offtopics_init.ipynb:	Notebook de inicializacion y generacion de orden aleatorio. Para ejecutar
							una sola vez, y despues monitor.ipynb se encarga del monitoreo y 
							actualizacion del historial (offtopic_history.csv). 
				  
						 