# Proyecto-Taller-Electronica-Unal-carro
PROYECTO DE CARRO, TALLER DE ELECTRONICA UNIVERSIDAD NACIONAL Juan Lebaza-Wilson Ruge-Juan Sebastian
\documentclass[journal]{IEEEtran}
\usepackage[spanish]{babel}
\usepackage[utf8]{inputenc}
\usepackage{amsmath, amsthm, amsfonts} 
\usepackage{graphicx}
\usepackage{cite}
\usepackage{listings}
\usepackage{tabularx}
\usepackage{multirow}
\usepackage{colortbl}
\renewcommand{\refname}{Referencias}
\usepackage{subfig}
\usepackage{booktabs}
\usepackage{cite}
\usepackage{hyperref}
\usepackage{float}
\usepackage{parskip}
\usepackage{url}
\usepackage{hyperref}
\renewcommand{\citedash}{ -- }

\renewcommand{\tablename}{\small{\textsc{Tabla}}}

\title{Entrega Final}
\author{\IEEEauthorblockN{Juan Miguel Lebaza O.~~~~~~~~~~~~~Miguel Angel Pinto~~~~~~~~~~~Sara Ximena Prada }\\
\IEEEmembership{jlebaza@unal.edu.co} ~~~~~~~~~~~~~~~~~\IEEEmembership{mipintoa@unal.edu.co}~~~~~~~~~\IEEEmembership{spradao@unal.edu.co}\\\\\\\\
\IEEEauthorblockN{Wilson Sebastián Ruge~~~~~~~~~~~~~Julian Alejandro Torres R. ~~~~~~~~~~~Juan Pablo Avendano }\\
\IEEEmembership{wruge@unal.edu.co} ~~~~~~~~~~~~~~~~~\IEEEmembership{jultorresro@unal.edu.co}~~~~~~~~~\IEEEmembership{javendanoa@unal.edu.co
}
\\
\newline
\IEEEauthorblockA{
Introduccion a la Ingenieria~~~~Facultad de Ingeniaría\\ Universidad Nacional de Colombia.\\
Bogotá. Colombia.\\
}}
\renewcommand{\leftmark}{introduccion ingenieria,~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Juan Avedaño~~~~~ Juan Lebaza~~~~~Miguel Pinto~~~~~Julian Torres~~~~Sara Prada~~~~Wilson Ruge~~~~~~~~~~~~~~~~~~~~~~~~ \today \hfill}
\raggedbottom
\begin{document}



\maketitle
\renewcommand{\abstractname}{Abstract}
\\
\IEEEpeerreviewmaketitle

\section{Abstract}

 \begin{abstract}
  Las minas terrestres en Colombia son artefactos letales principalmente abandonados en áreas rurales y a lo largo de nuestro territorio. Las minas terrestres son armas o explosivos enterrados bajo el suelo que se activan por presión y pueden matar o causar daño cuando se pisan, además de causar efectos ambientales a largo plazo. Las minas terrestres plantean grandes desafíos para la agricultura, la infraestructura y el desarrollo de las comunidades en conflictos. Para desminar las áreas afectadas, se suelen usar soldados humanos, lo que implicaba una gran cantidad de mano de obra, tiempo y esfuerzo. Este método existente presenta muchos errores e incluso pérdida de vidas en algunas situaciones. Por lo tanto, se propone un método basado en robots que utiliza un detector de metales como herramienta complementaria para la detección de minas terrestres. 
 \end{abstract}


\section{introducción}
En este proyecto, nos enfocaremos en el desarrollo de un carro detector de minas basado en la detección de metales. El objetivo principal es crear un sistema confiable y que sea efectivo para localizar y neutralizar minas terrestres, con el fin de contribuir en la seguridad y protección de las comunidades afectadas. A través de la implementación de tecnología de detección de metales, se busca que este proyecto sea una ayuda para los grupos de desminado que ya existen actualmente, y así  evitar poner en riesgo a estos grupos.

\subsection{Motivación}
La principal razón para desarrollar este proyecto es contribuir al desminado en nuestro territorio ya que es uno de los problemas que nos han afectado durante las últimas seis décadas incluso actualmente.

\section{El problema de las minas terrestres}
Las minas terrestres representan un problema grave en contextos de guerra. Son dispositivos explosivos que se colocan en el suelo y se activan al ser tocados por vehículos, personas o animales. Estas minas se utilizan para restringir el movimiento del enemigo y asegurar las fronteras en disputa. Sin embargo, el impacto de las minas terrestres va más allá del conflicto, afectando principalmente a la población civil.

Las minas antipersonal son especialmente peligrosas, ya que están diseñadas para herir o matar personas. A menudo son dispositivos simples y económicos, de tamaño reducido y difíciles de detectar. Desafortunadamente, incluso después de finalizar un conflicto, muchas minas terrestres quedan enterradas y sin marcar, poniendo en riesgo a las comunidades locales.

Estas minas tienen consecuencias devastadoras para la vida de las personas y el entorno. Además de las víctimas y las lesiones, las minas contaminan el suelo y el agua con metales pesados y explosivos. Esto limita el uso de extensas áreas de tierra para la agricultura u otros fines, generando un impacto económico negativo a largo plazo.

Aunque se han realizado esfuerzos internacionales para abordar el problema de las minas terrestres, aún existen desafíos significativos. Organizaciones como la Campaña Internacional para la Prohibición de las Minas Terrestres han trabajado para concientizar sobre el peligro de las minas y promover su prohibición. Sin embargo, todavía hay países que producen y utilizan minas antipersonal, lo que requiere una acción continua para abordar este problema global.
 \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{imagenes/minaa.jpg}
   \caption{Mina antipersonal terrestre}
    \label{Espectos}
	\end{figure}
  
\section{Proyectos similares}
\subsection{HOPE Landmine Detection System} 
Este proyecto consiste en diseñar y construir un vehículo robótico que pueda detectar minas terrestres de forma autónoma. El vehículo utiliza una variedad de sensores, como detectores de metales, radares de penetración terrestre e imágenes térmicas, para detectar minas terrestres. Una vez que se detecta una mina terrestre, el vehículo transmitiría su ubicación a un operador remoto.
El vehículo estaría diseñado para ser liviano y móvil, de modo que pueda transportarse fácilmente a diferentes áreas. También estaría equipado con una variedad de características de seguridad, como un revestimiento ignífugo y un mecanismo de autodestrucción, para proteger al operador en caso de explosión de una mina terrestre.

 \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{hop.jpg}
   \caption{Detector de metales HOPE}
    \label{Espectos}
	\end{figure}

\subsection{Automatic Landmine Detection using Robot}
Este en un vehículo robótico capaz de detectar minas terrestres de forma autónoma. El vehículo utiliza una variedad de sensores, como detectores de metales, radares de penetración terrestre e imágenes térmicas, para detectar minas terrestres. Una vez que se detecta una mina terrestre, el vehículo transmite las coordenadas GPS de la mina terrestre a una ubicación remota.
El vehículo está diseñado para ser autónomo, de modo que pudiera funcionar sin intervención humana. Esto lo haría más seguro para los desminadores, ya que no tendrían que arriesgar sus vidas al ingresar a áreas que pueden estar contaminadas con minas terrestres.

 \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{22.png}
   \caption{Vehículo robótico de detección de minas}
    \label{Espectos}
	\end{figure}
 
\section{Justificación}
En Colombia, existen departamentos con extensas áreas rurales pobladas por campesinos y ganaderos, donde debido a la baja densidad poblacional en estos territorios varios grupos armados han ejercido un vasto control sobre estas zonas por medio del terror y la violencia a lo largo de la historia, con el propósito de tener a su vez el control de las principales vías intermunicipales y pueblos aledaños para así mismo ejercer dominio sobre los recursos de esas regiones. 

Para mantener su hegemonía sobre los territorios, los grupos armados se empeñaron en implantar distintos tipos de trampas en caso de una posible intervención militar contra las áreas que controlaban, en ello, destaco el uso de minas antipersonas debido a su efectividad para repeler mayormente cualquier tipo de ataque terrestre. Actualmente, en alrededor de 447 municipios, la cantidad de minas camufladas en el suelo que se encuentran dispersas sin detonar son cuan incontables como imperceptibles a la vista, y, por ende, existe una alta probabilidad de que las poblaciones rurales estén constantemente propensas a sufrir accidentes fatales a causa de estas minas. 

Debido a esa situación, este proyecto busca aportar al desminado de tierras en el país, por lo que se plantea crear un vehículo compacto integrado con un campo electromagnético capaz de identificar minas fabricadas a base de metal, capaz de recorrer todo tipo de terreno sin complicación alguna para posteriormente, tras localizar la mina, emita un sonido para que los organismos de socorro que estén usando puedan desmantelar la zona alertada.

\section{Planteamiento del problema}

Dados los antecedentes históricos de la violencia en Colombia y el legado de la proliferación de todo tipo de armas que el país heredó, surgen varias causas por las que esta problemática sigue vigente.

\begin{itemize}
    \item\textbf{La proliferación de minas antipersonas:} La amenaza de las minas terrestres es un problema grave en muchas partes del mundo, ya que pueden causar lesiones graves e incluso la muerte a personas inocentes, así como dañar infraestructuras. Según el informe del Programa de las Naciones Unidas para el Desarrollo (PNUD) de 2020, se estima que hay alrededor de 60 millones de minas terrestres sin detonar en todo el mundo, lo que representa una amenaza constante para las personas y las comunidades en las áreas afectadas por conflictos armados, la violencia y la inestabilidad política.
    \item\textbf{Seguridad y costos:} La detección y eliminación de las minas terrestres es un proceso costoso, peligroso y que requiere mucho tiempo, y a menudo implica el uso de equipos pesados y costosos, así como la intervención humana directa. A pesar de los esfuerzos realizados en las últimas décadas, el problema de las minas terrestres sigue siendo una de las mayores amenazas para la seguridad de las personas en muchas partes del mundo.
\end{itemize}

Teniendo en cuenta lo anterior, se propone desarrollar un vehículo en forma de tanque que pueda detectar minas terrestres mediante un detector de metales. Este vehículo sería capaz de desplazarse por terrenos  peligrosos de manera segura y eficiente, y tendría la capacidad de detectar las minas terrestres de manera automatizada, minimizando el riesgo de lesiones y muertes al ya ser ubicadas.

\section{Marco Teórico}
\begin{itemize}
    \item\textbf{Detector de metales por induccion de pulso:} Un sistema compuesto por 2 bobinas, una que emite un campo electromagnético de poca duración y alta frecuencia descargando la energía de un condensador, este campo puede penetrar en el suelo e interactuar con metales, después de que se emita el pulso el sistema cambia a recibir el campo mediante la segunda bobina, estos cambios se detectan mediante la variacion de la resistencia u inductancia, los cuales si son detectados por el sistema, este avisará de la presencia de un metal que está interactuando con el campo.
    \item\textbf{IED/DEI:} Improvised Explosive Device, o en español artefacto explosivo improvisado, es una forma de describir todos aquellos artefactos de fabricación casera con el propósito de generar una explosión que usualmente tiene como objetivo, desmoralizar, repeler, asesinar o atacar a algun objetivo ya sea militar o civil.
    \item\textbf{Tratado de Ottawa de 1997:} fue un tratado internacional adoptado el 18 de septiembre de 1997 en Ottawa, Canadá. Fue firmado por un gran número de países y entró en vigor el 1 de marzo de 1999. \\ \\ El objetivo principal del Tratado de Ottawa fue la prohibición y eliminación de las minas antipersonal, debido a los graves efectos humanitarios que causaban en las poblaciones civiles. El tratado se basó en la idea de que las minas antipersonal debían ser erradicadas debido a su impacto indiscriminado y duradero en la población civil, incluso después de que un conflicto haya terminado
    \item\textbf{Tipos de minas:}
    \begin{itemize}
        \item\textbf{Minas de presión:} Estas se activan cuando se les aplica presión, que puede resultar de pisarlas o de pasar por encima de ellas con un vehículo
        \item\textbf{Minas de presión direccional:} Estas tienen el mismo funcionamiento que las minas de presion tradicionales, solo que estas se activan cuando la presion viene de un lado especifico, asi mismo, possen un sistema de detonacion direccional.
        \item\textbf{Minas de mando a distancia:} Estas possen un sistema de detonación que se acciona por la accion de una radiofrecuencia normalmente proveniente de un control o celular.
        \item\textbf{Minas de dispersión:} Estas pueden acccionarse de cualquiera de las formas anteriores, no obstante suelen venir cargadas con metralla, o con mas AEI para aumentar su efectividad a la hora de explotar.
        \item\textbf{Minas de sensor:} Estas cuentan con sensores para su activacion, aunque no siempre explotan automáticamente, pueden llegar a servir a alertar mediante sus sensores la presencia de terceros.
    \end{itemize}
    \item\textbf{Falsos positivos} Estas son señales las cuales por razones de una efectividad inestable o interferencia son capaces de alertar por materiales que no son minas o directamente no son metales. 
    \item\textbf{Falsos negativos:} Opuesto a los falsos positivos, estos se dan a causas de una pobre efectividad la cual no es capaz de detectar metales a altas profundidades, normalmente son mucho mas peligrosos que los falsos positivos ya que pueden provocar la detonación de un dispositivo en un area que se declaró "Libre de minas".
\end{itemize}

\section{Objetivos}

\subsection{\textbf{Objetivo general:}} Desarrollar un vehículo capaz de detectar minas terrestres compuestas de metal en zonas de potencial riesgo de minado.

\subsection{\textbf{Objetivos específicos:}} 
\begin{itemize}
    \item Planificar un prototipo funcional que detecte minas que contengan metales en su composición.
    \item Elaborar un vehículo ligero que pueda movilizarse por diferentes terrenos.
    \item Desarrollar un detector de metales versátil que pueda ser implementado al vehículo
\end{itemize}

\section{Metodología}

\subsection{\textbf{Discusión y selección del proyecto:}}

En este primer acercamiento se realizó una lluvia de ideas en la cual se discutieron distintas problemáticas de amplia relevancia social, cuyas posibles soluciones fuesen efectivas y acordes al nivel de la problemática que se escogiese, en ello, se decidió que el problema de las minas antipersonas ocultas y activas alrededor de Colombia sería la problemática a tratar más afín a los intereses del equipo, además de que su resolución podía ser viable y posible.

\subsection{\textbf{Investigación y recopilación de datos:}}

Tras la selección del proyecto se comenzó a indagar acerca de las locaciones de la mayoría de minas en el país, en ello, se encontró que, al ser las minas mayormente hechas de forma casera con metales de bajo de costo implantadas en zonas rurales y remotas, era muy difícil localizarlas dadas las condiciones del terreno, lo que conllevó a investigar a su vez a fondo los tipos de detectores de minas y su desempeño en diferentes tipos de suelos, lo que propició que el detector en el que se basara estuviese encaminado a detectar metales por medio de distintos pulsos electromagnéticos.

Por otra parte, se encontró que el rastreo de minas era una tarea altamente riesgosa para una persona, por lo que se idealizó un vehículo que fuese capaz de atravesar todo tipo de terrenos y que tuviese implementado el detector de metales planteado, todo ello controlado de manera remota para poder garantizar la seguridad de las personas que estuviesen al mando del vehículo, de tal manera que si el artefacto llegase a activar una mina, aquellas personan estuviesen fuera de la zona de peligro.

\subsection{\textbf{Planeación y experimentación:}}

Teniendo ya un esquema del prototipo a seguir, se seleccionaron distintos modelos y materiales que se utilizarían posteriormente para desarrollar el proyecto, se exploraron alternativas que permitiesen que tanto el vehículo como el detector de minas fuesen lo suficientemente compactos y ligeros para cumplir su función de la manera más eficaz.

 \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{tank.jpg}
   \caption{Esquema de posible forma del vehículo}
    \label{Espectos}
	\end{figure}

  \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{carr.jpeg}
   \caption{Posible integración de detector de minas al vehículo}
    \label{Espectos}
	\end{figure}

  \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{oruga.jpg}
   \caption{Posible aspecto de las ruedas del vehículo}
    \label{Espectos}
	\end{figure}

\subsection{\textbf{Construcción y pruebas de funcionamiento:}}

Tras la fase de experimentación y haber optado por el diseño más acorde a los intereses del proyecto se construyeron tanto el vehículo como el detector de metales, en donde tras realizar varias pruebas en ambos elementos y haber tenido varios percances en el funcionamiento de los mismos, finalmente se obtuvieron resultados de los equipos.

  \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{terrenaitor.jpeg}
   \caption{Interacción por control remoto con el vehículo}
    \label{Espectos}
	\end{figure}

   \begin{figure}[H]
  	\centering
  	\includegraphics[width=9 cm,height=8 cm,keepaspectratio]{detector.jpeg}
   \caption{Respuesta del detector a un objeto metalico a disitntas distancias}
    \label{Espectos}
	\end{figure}

\subsection{\textbf{Análisis de resultados:}}

Tras haber cumplido con el objetivo general, se discutieron las posibles causas de los percances experimentados en el proceso de construcción del prototipo, así como cuales aspectos del proyecto se tuvieron que modificar y si realmente el proyecto cumplió con las expectativas del equipo.
\\
Detallaremos los inconvenientes ocurridos por cada componente del proyecto, en primer lugar el automóvil controlado a distancia, y después el detector de metales por inducción de pulso. 
\newline
\\
\textbf{Automóvil controlado a distancia:}

\begin{enumerate}
   
\item Primeramente, se adquirió un módelo de carro estándar de 4 ruedas el cual se ensambló y se puso a prueba, después de no mucho tiempo transcurrido se experimentó el primer inconveniente; el módulo bluetooth adquirido desde un principio (un módulo bluetooth HC05) al parecer no iniciaba a pesar de estar conectado a una pila de 9 voltios, sin embargo cuando se conectaba a un ordenador este sí comenzaba a funcionar. Por ello, se optó por adquirir otro módulo bluetooth (Un módulo Bluetooth HC06) el cual sí inició con la alimentación proporcionada. No se sabe con certeza la causa de la falla evidenciada con el primer móulo empleado, sim embargo, habían ciertas características físicas que no coincidían con otros modelos iguales a este, se plantea que puede haberse tratado de haber adquirido un ejemplar genérico con mala calidad.
\\
\begin{figure}[H]
  	\centering
  	\includegraphics[width=6 cm,height=6 cm,keepaspectratio]{081691.jpg}
   \caption{Módulo Bluetooth HC05}
    \label{Espectos}
	\end{figure}

 \begin{figure}[H]
  	\centering
  	\includegraphics[width=6 cm,height=7 cm,keepaspectratio]{images.jpg}
   \caption{Módulo Bluetooth HC06}
    \label{Espectos}
	\end{figure}
\item No obstante, posteriormente se presentaría el siguiente inconveniente, se trataba de un defícit energético por parte del sistema de alimentación (al principio se usó una batería de 9 voltios convencional) provocando que el automóvil no tuviese un arraque y desplazamiento óptimos, se llegó a la solución del problema desconectando algunos motorreductores, los que permanecieron conectados mostraron una aceleración notable.
\begin{figure}[H]
  	\centering
  	\includegraphics[width=10 cm,height=7 cm,keepaspectratio]{carro con 9V.jpg}
   \caption{Carro alimentado por pila 9V}
    \label{Espectos}
	\end{figure}
Entonces como medida temporal se implemento una powerbank, haciendo que el vehículo fuese práctiacamente funcional, aunque presentaba una limitante, las powerbanks están diseñadas a tener cierto voltaje de salida preestablecido ya que estos dispositivos son producidos para ser empleados en aparatos con baja tolerancia al voltaje tales como: los télefonos, las tabletas, los audífonos inalámbricos, entre otros.
\begin{figure}[H]
  	\centering
  	\includegraphics[width=7 cm,height=6 cm,keepaspectratio]{carro con powerbank.jpeg}
   \caption{Carro alimentado con powerbank}
    \label{Espectos}
	\end{figure}
Como mejora posterior, se obtuvieron 2 baterías con alta capacidad de amperaje y conectadas en serie, con el fin de mejorar la experiencia de circulación del vehículo. 
\begin{figure}[H]
    \centering
  	\includegraphics[width=8 cm,height=7 cm,keepaspectratio]{Baterías.jpg}
   \caption{Pilas 18650}
    \label{Espectos}
	\end{figure}
\begin{figure}[H]
    \centering
  	\includegraphics[width=6 cm,height=4 cm,keepaspectratio]{carro con pilas.jpeg}
   \caption{Automóvil empleando pilas li-Ion 18650}
    \label{Espectos}
	\end{figure}
\\
\item Y cómo último problema generado durante la realización del automóvil fue el de implementar un sistema de orugas para conseguir la garantía de poder desplazarse por terrenos irregulares; por temas financieros no era viable adquirir este mecanismo, en consecuencia se tuvo en cuenta adquirir un sistema que adapta las llantas convencionales en orugas, aunque no parece ser algo más allá de un simple modelo, por ello tampoco se pudo implementar esta opción.

\begin{figure}[H]
    \centering
  	\includegraphics[width=6 cm,height=4 cm,keepaspectratio]{orgas caras.jpeg}
   \caption{Orugas convencionales}
    \label{Espectos}
	\end{figure}

\begin{figure}[H]
    \centering
  	\includegraphics[width=6 cm,height=4 cm,keepaspectratio]{png-clipart-caterpillar-machine-traction-rolling-resistance-continuous-track-tire-track-blue-animals.png}
   \caption{Modelo de adaptador de llantas}
    \label{Espectos}
	\end{figure}


\begin{figure}[H]
    \centering
  	\includegraphics[width=6 cm,height=4 cm,keepaspectratio]{png-clipart-continuous-track-machine-traction-john-deere-harvester-tire-track-animals-auto-part.png}
   \caption{Oruga adaptada a llantas convencionales}
    \label{Espectos}
	\end{figure}
\end{enumerate}
\newline
\\
\textbf{Detector de metales por inducción de pulso:}

\begin{enumerate}
    \item Como se mencionó en el quinto informe, se tenía pensado en un principio utilizar un detector de metales ajeno, pero esta idea se replanteó devido a que estos detectores no se pueden manipular, y presentan muy poco alcance respecto a lo que requeríamos. 
    \begin{figure}[H]
    \centering
  	\includegraphics[width=6 cm,height=4 cm,keepaspectratio]{detector ajeno.jpg }
   \caption{Detector ya fabricado}
    \label{Espectos}
	\end{figure}
\\
\begin{enumerate}
    \item El exceso de voltaje varias veces provocó el daño de varios componentes que se usan para la elaboración del detector de metales, dichos componentes fueron:
    \begin{itemize}
        \item Arduino Nano
        \item MOSFET IRF730 
        \item Amplificador de señal LM358
    \end{itemize}
    cabe destacar que este último fue reemplazado por otro hecho a mano conformado por transistores y resistencias.
    \begin{figure}[H]
  	\centering
  	\includegraphics[width=7 cm,height=6 cm,keepaspectratio]{IMG-20230621-WA0015.jpg}
   \caption{Amplificador de señal casero}
    \label{Espectos}
	\end{figure}
\end{enumerate}


\section*{Bibliografía}

\begin{enumerate}
  \item \textit{(No date)} Automatic landmine detection using robot - International Journal of ... Available at: \href{https://www.ijert.org/research/automatic-landmine-detection-using-robot-IJERTCONV8IS07011.pdf}{\url{https://www.ijert.org/research/automatic-landmine-detection-using-robot-IJERTCONV8IS07011.pdf}} (Accessed: 21 June 2023).
  
  \item \textit{(No date)} ESA. Hope for detecting landmines. Available at: \href{https://www.esa.int/Applications/Technology_Transfer/HOPE_for_detecting_landmines}{\url{https://www.esa.int/Applications/Technology_Transfer/HOPE_for_detecting_landmines}} (Accessed: 20 June 2023).
  
  \item CNMH, Remangate por las victimas de las minas antipersonal. [Online]. Centro Nacional de Memoria Historica, 2015.
  
  \item F.R. Marugan, F.J. Matas, ''La tecnologia de los detectores de metal: principios de funcionamiento y analisis de los escenarion de expolio arqueologico''. [Online] THE JOURNAL OF CULTURAL HERITAGE CRIME, 2020.
  
  \item Electromagnetismo. [Online] Wikipedia, 2022.
\end{enumerate}

\end{document}
}
