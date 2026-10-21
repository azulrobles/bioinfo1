# Regiones concretas en donde Clustal Omega y MAFFT no se pusieron de acuerdo. 

# sobre RSPO2_human:

cola C-terminal -> entre las posiciones 204-243 con un acuerdo medio de 0.35 y con una fracción de 0.82 que se encuentra bajo el umbral de 0.5. 
Puede deberse a que es una región no estructurada y su longitud es variable. 

péptido señal -> entre las posiciones 1-21 con un acuerdo medio de 0.49. 
Puede deberse a que carece de motivos conservados que guíen el alineamiento. 

Coincidencia con MUSCLE5: 
Sí coinciden, ya que las posciones con un LC<=6 se encuentran en el péptido señal (18-19) y en la cola c-terminal (227-233, con LC entre 2 y 6). 

Coincidencia con trimAI: 
Sí coinciden, debido a que éste eliminó 10 de 21 residuos (48%) del péptido señal y 17 de 40 residuos (43%) de la cola c-terminal. 


# sobre LGR5_human: 

cola C-terminal -> entre las posiciones 821-907 con un acuerdo medio de 0.40 y con una fracción de 0.74 bajo el umbral de 0.5. 
Puede deberse a que esta región es no estructurada y variable. 

LRR -> entre las posiciones 1-454 con un acuerdo medio de 0.61 y con una fracción de 0.45 bajo el umbral de 0.5. 
Puede deberse a que esta región contiene varias repeticiones y un desfase lo desequilibra. 


Coincidencia con MUSCLE5:
Sí coinciden, ya que el 40% de los residuos tienen un LC<=6, con LC medio de 7.2 en LRR. En la cola c-terminal el 61% de los residuos tienen LC<=6 con un LC medio de 4.7. 

Coincidencia con trimAI:
Sí coinciden, debido a que éste eliminó 357 de 454 residuos (79%) de LRR. Y 82 de 87 residuos (94%) en la cola c-terminal. 

