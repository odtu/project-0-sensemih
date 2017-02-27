# Project-0

Please note that, this project will **NOT** be graded. However, there are many useful tools that you will learn in this project, so I strongly recomend that you spend considerable amount of time in this project. You will definitely use the experience you gained in this project.

## Deadline:
06/03/2017 23:59


## Project Topic:

Simulate a DC motor using in Simulink [Simscape Power Systems](https://www.mathworks.com/products/simpower.html). Although the Mathworks webpage has [lots of examples](https://www.mathworks.com/help/physmod/sps/getting-started-with-simpowersystems.html), I advise yo to start with simpler tutorials. There are tons of tutorials online, here just a few you can start with:

- [Simulink Basics](https://faculty.unlv.edu/eelabs/docs/guides/Simulink_Basics_Tutorial.pdf)
- [Simulink Tutorial](http://ecee.colorado.edu/~ecen2060/materials/simulink/tutorial/MATLAB_Simulink_tutorial.pdf)
- [Simulink training](http://www.fsd.mw.tum.de/wp-content/uploads/Training_TUM_GS_Simulink_14b.pdf)

In the project, you should model a DC motor (of any size ), and simulate the starting process of the motor (i.e acceleration from stationary to rated speed). You can build your own models, or use any other simple models, but there is a [Chopper-Fed DC Motor Drive Example](https://www.mathworks.com/help/physmod/sps/examples/chopper-fed-dc-motor-drive-continuous.html) in Mathworks webpage (see [this page](https://simulationresearch.lbl.gov/modelica/releases/msl/3.2/help/Modelica_Electrical_Machines_Examples_DCMachines.html) for Modelica examples) which you can use (but please try to understand how it works than directly running it).

Besides building a DC motor model, you should prepare a short report including following details:

- A short info about the motor (voltage, current, power ratings etc)
- Short info about the power source and control system
- Graphs showing acceleration curve from stationary to rated speed.
- Start-up current graphs
- Produced torque during startup
- Bibliography (Please mention if you used someone else's model)

I prefer [markdown](https://guides.github.com/features/mastering-markdown/), or [Simulink Report Generator](http://ro-01-ici.ici.ro/brosuri/MathWorks_Simulink-Rpt-gen.pdf) for your reports, but I also accept Word documents (but please make sure your report is [compatibe with Libre Office](http://askubuntu.com/questions/28342/how-to-maintain-document-compatibility-between-libreoffice-and-other-office-suit)).

In short, your repo should include:

- The simulink file of your model
- The report explaining how the model works.

and you should upload these files in to your repo until the deadline.


