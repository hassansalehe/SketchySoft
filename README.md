SketchySoft
===========

Programming Through Sketchy Flow Charts.

INRODUCTION
I propose an intelligent user interface application for writing computer programs using sketch
recognition and software engineering flow charts. Basically, the application should be able to
recognize flow charts sketched on a surface of a smart or touch screen and transform them into a
program source code in programming languages like C and Python. Then, it should be able to present
error-free source code to the user. In case the flow charts results in erroneous code it should inform the
sketcher interactively of the part which causes error(s) .To use the application it suffices for a
programmer to know the flow chart constructs to write a, say, C program.

USES
The ultimate goal of this project is to revolutionize the way software is constructed during software
development process. This is important because research shows that sketching is easier than typing on
the standard keyboard on user perspective. Moreover, conversion of software architecture diagrams
into program through coding on keyboard could introduce ambiguity and bugs into the produced
software. It also involves repetition of work which could have been ignored with the use of intelligent
application, like I am proposing here, during design phase of software development.
This application can be used for academic purposes like teaching students how to do programming
through sketching. It can also be used to get insight of flow charts through simulating the program code
produced by the tool.

PROJECT SCOPE
Since this is a term project time is limited, therefore, some features might not be ready by the end
of the semester. However, it creates a foundation to an application which could be of high impact on
programming. Therefore, it is expected that by the end of the term basic features of the system should
ready and working. This means that sketchy recognizer should be complete and the application should
be ready to analyze and transform simple flow charts sketched on a single screen.

PROJECT STAGES
The application development is divide into four parts/stages. These stages are as described
below;
4.1 Flow Chart Symbols Classification and Recognition
This is the easiest of all other stages. It involves a little survey of all important symbols
involved in drawing flow charts and what they mean in flow charts. Moreover, A simple
model will be implemented to recognize individual symbols classified. This will build
foundation to the sketchy recognizer described in part 4.2 below.
4.2 Sketchy Recognizer
This involves designing and implementing sketchy recognizer which should be able
recognize flow chart symbols and should be taking in sketches in real time and the signals
should be dependent on time. To do this it should be able to extract features from the
sketches. The technologies involved will include Dynamic/Hidden Markov models.
4.3 Grammar for Symbol Labels
Flow chart symbols contain labels which carry information that dictate actions performed in
flow chart symbols and aid in transition from one symbol to another. Grammar is necessary
for the recognizer to understand the labels. This stage will define a set of words/sentences
that the system should understand while extracting the features from the sketched flow
chart.
4.4 Automatic Program constructor
The application should be able to convert the recognized flow chart to program source code.
Furthermore, it should be able to give live feedback whenever the transformed code is
erroneous. Moreover, it will interact with the operating system to create file by which the
application writes the code to. The created file is presented to the user for further uses. This
stage involves implementation of module which performs the tasks described in this section.
