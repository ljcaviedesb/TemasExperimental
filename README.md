# TemasExperimental
Este es un cuaderno para el desarrollo de las actividades de Temas Avanzados en Física de Partículas Elementales.
Las fechas de los trabajos se tomarán como la fecha de entrega de la tarea desarrollada y no a desarrollar. 

## 25 de Septiembre ##
### Identificación de Objetos: Tracks and Clusters ###

Tareas: 1. Plot the number of average interactions per bunch-crossing (mu_average) 
        2. Make a 2D histogram of NPV vs. mu
        3. Make a 2D histogram of NPV and mu vs. nTracks and nClusters: NPV vs. nTrack, NPV vs. nClusters, mu vs. nTrack, mu vs. NClusters
        4. Plot all track, cluster and particle variables
        5. Interpret the meaning of each variable
        6. What is "Particle PDG ID"?
        
Los ejercicios **1, 2, 3** y **4** Se encuentran desarrollados en 'Tracks_Clusters_cpp.ipynb'.
 ***Interpretación***
 Respecto a la interpretación de las gráficas
 
 La grafica de Track_m muestra una sola partícula con masa promedio 139.5 MeV y en la tabla de datos de la pág oficial del PDG encuentro que esa masa corresponde al pión con masa 139.57039 +- 0.00018 MeV. Y tiene sentido porque en la gráfica de partículas PDG ID efectivamente muestran la partícula y anti partícula pión.
 Si nos vamos a la gráfica de masa de las partículas hay una partícula cun muy poca masa, podemos pensar que es un electrón, además que la gráfica de PDG ID muestra que hay electrones. Hay otra partícula con masa cercana a 1000 MeV, encontré que la partícula phi(1020) tiene masa 1019.461 +- 0.016 MeV y decae en K0L y K0S, o puede ser la partícula a0(980) con masa 980 +- 20MeV la cual puede decaer en K+ o K-.

 
 ***Partículas PDG ID***

Primero tenemos que saber qué es **PDG**.  Este PDG es el Grupo de Datos de Partículas que tiene un esquema de numeración de partículas a las cuales le asigna un código dependiento el tipo de partícula, además este código es único. Estos códigos se conocen como **PDG ID**, el cual es positivo cuando es partícula y negativo cuando es antipartícula. Su sitio oficial es https://pdg.lbl.gov. Tambien se pueden utilizar https://rivet.hepforge.org/code/1.3.0/a00660.html o https://twiki.cern.ch/twiki/bin/view/Main/PdgId

Los partículas son entonces, según los datos que genera el código son:

PDG ID -3334: OmegaPlus\\
PDG ID  3334: OmegaMinus\\
PDG ID -3122: LamdaBar\\
PDG ID  3122: Lamda\\
PDG ID -2212: AntiProtón\\
PDG ID  2212: Protón\\
PDG ID -2112: AntiNeutrón\\
PDG ID  2112: Neutrón\\
PDG ID  -321: K-\\
PDG ID  -321: K+\\
PDG ID  -211: Pi-\\
PDG ID   211: Pi+\\
PDG ID   -11: Positrón\\
PDG ID    11: Electrón\\
PDG ID   130: K0L\\

PDG ID   321: K0S


