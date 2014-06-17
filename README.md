CURSO_GPU_2014
==============

ESCUELA DE VERANO  Supercómputo Paralelo Y Programación de GPUs
1. Presentación de la clase 

2. Generalidades sobre cómputo científico en general y cómputo paralelo 

3. Recordatorio de C, en particular uso de los punteros Práctica 1 

4. Paralelización sobre arquitectura con memoria distribuida: MPI 
4.1 Elaboración progresiva de un programa MPI sencillo. 
4.2 Operaciones blocking y non-blocking, deadlocks. 
4.3 Algunas funciones MPI frecuentes 
4.4 Práctica 2 

5. Entornos de cómputo paralelo en clusters 
5.1 Nodo maestro y nodos de cómputo 
5.2 Redes de interconexion 
5.3 Gestores de colas 
5.4 Monitoreo 

6. Presentación general de los GPUs 
6.1 Arquitectura : multiprocesadores, núcleos, distintos tipos de memoria. 
6.2 Definición del vocabulario específico a CUDA. 
6.3 Advertencias sobre el cómputo en GPUs. 
6.4 Práctica 3: ¿ que GPU(s) tengo en mi máquina ? 

7. Preparando el GPU 
7.1 Reservación y liberación de video RAM. 
7.2 Comunicación con el CPU. 
7.3 Medición de anchos de banda. 
7.4 Uso de la "page lock" memory. 
7.5 Práctica 4: medición de anchos de banda 

8. Primera función en CUDA 
8.1 Redacción de un kernel CUDA 
8.2 Grids, Blocks y threads 
8.3 invocación de un kernel 
8.4 Práctica 5: adición de dos matrices 

9. Optimización de un kernel CUDA 
9.1 Lectura ordenada de la memoria global 
9.2 Memoria shared vs cache L1 
9.3 Sincronización de los threads 
9.4 Bank conflict 
9.5 Warp divergence 
9.6 Uso del profiler CUDA 

10. Librerías de CUDA 
10.1 Necesidad de librerías de bajo nivel : ejemplo de las reducciones. 
10.2 Estudio de la presentación de Mark Harris. 
10.3 Presentación de librerías (cublas, cufft, thrust, etc.) 
10.4 Practica 6 : resolución de problemas matemáticos usando librerías 

11. Depuración de un programa 
11.1 Depuración de un programa C: gdb, lldb. 
11.2 Depuración de un programa MPI 
11.3 Depuración de un kernel CUDA: "printf debugging" y cuda-gdb 

12. Códigos mixtos MPI-CUDA 
12.1 Especificidad de un código para clúster de GPUs 
12.2 Unified Virtual Addressing (UVA) y GPU Direct 
12.3 Obtención temprana del rango y selección del GPU
