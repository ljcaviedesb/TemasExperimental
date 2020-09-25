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
 
 ***Partículas PDG ID***

Primero tenemos que saber qué es **PDG**.  Este PDG es el Grupo de Datos de Partículas que tiene un esquema de numeración de partículas a las cuales le asigna un código dependiento el tipo de partícula, además este código es único. Estos códigos se conocen como **PDG ID**, el cual es positivo cuando es partícula y negativo cuando es antipartícula. Su sitio oficial es https://pdg.lbl.gov. Tambien se pueden utilizar https://rivet.hepforge.org/code/1.3.0/a00660.html o https://twiki.cern.ch/twiki/bin/view/Main/PdgId

Los partículas son entonces, según los datos que genera el código son:

PDG ID -3334: OmegaPlus

PDG ID  3334: OmegaMinus

PDG ID -3122: LamdaBar

PDG ID  3122: Lamda

PDG ID -2212: AntiProtón

PDG ID  2212: Protón

PDG ID -2112: AntiNeutrón

PDG ID  2112: Neutrón

PDG ID  -321: K-

PDG ID  -321: K+

PDG ID  -211: Pi-

PDG ID   211: Pi+

PDG ID   -11: Positrón

PDG ID    11: Electrón

PDG ID   130: K0L

PDG ID   321: K0S


