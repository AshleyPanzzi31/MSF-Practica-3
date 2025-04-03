[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=JaelBadillo/MSF-Practica-2)
# Modelado de Sistemas Fisiológicos. Práctica 2:Sistema Respiratorio [Badillo22210409]

# Autor
Jael Badillo Cruz

Ingeniería Biomédica, Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: L22210409@tectijuana.edu.mx

## Objetivos general
Diseñar un controlador que permita formular un protocolo de tratamiento para que un paciente
con enfisema (caso) presente la misma presión alveolar que un individuo sano (control).
## Actividades
1. Calcular analÌticamente la funcion de transferencia del sistema pulmonar.
2. Establecer el modelo de ecuaciones integro-diferenciales.
3. Determinar el error en estado estacionario y la estabilidad del sistema en lazo abierto.
4. Construir el diagrama de bloques como se indica en la Figura 5.4.
5. DiseÒar el controlador con Simulink utilizando el bloque PID Controller y la herramienta Tune para sintonizar los valores Ûptimos para cada una de las ganancias kP, kI y kD.
6. Ilustrar el cambio del áujo de aire y el volumen tidal en respuesta a las siguientes formas de onda de presion sinusoidal en la apertura de la vÌa aÈrea[Paot)]:
a)15respiraciones por minuto con una amplitud(A)de2:5cmH2O, es decir, respiraciÛn normal.
b)30respiraciones por minuto con una amplitud(A)de1:5cmH2O, es decir, respiraciÛn elevadao taquipnea.
7. Determinar la respuesta a la funciÛn sinusoidal[u(t) =Asin!t]en el intervalot2[0;30](segundos),en Python, Simulink y Multisim en lazo abierto y en lazo cerrado con el controlador.

## Docente
Dr. Paul A. Valle

Posgrado en Ciencias de la Ingeniería [PCI] y Departamento de Ingeniería Eléctrica y Electrónica [DIEE], Tecnológico Nacional de México/IT Tijuana. Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México. Email: paul.valle@tectijuana.edu.mx

## Lecturas
[1] Paul. A. Valle, Syllabus para la asignatura de Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México/IT Tijuana, Tijuana, B.C., México, 2025. Permalink: https://www.dropbox.com/scl/fi/4gl55ccrjm9yulvziikxs/Modelado-de-Sistemas-Fisiologicos.pdf

[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018.
