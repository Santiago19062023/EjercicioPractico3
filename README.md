# EjercicioPractico3

## En la Terminal correr cada paso con su indicacion 

# Paso 1: Crear entorno de conda con la versión necesaria (Nota: Enter al momento de crear el entorno de conda)

conda create --name Grupo7 python=3.12.7

# Paso 2: Inicializar el entorno de conda

conda init

# Paso 3: Reseteo de terminal 

exec bash

# Paso 4: Se procede activar el entorno

conda activate Grupo7

# paso 5: Instalar dependencias requirements.txt (Nota: Enter al momento de instalar)

conda install --file requirements.txt

# paso 6: ejecutar Ejercicio3.ipynb (Extra- ejecutar Ejercicio3.ipynb desde terminal)

jupyter nbconvert --execute --to notebook --inplace Ejercicio3.ipynb 