# Object-oriented MATLAB toolbox for structural health monitoring
## Description:
The purpose of the toolbox is to provide a framework for the tasks characteristic to structural health monitoring (SHM) such as, data acquisition, basic signal processing, system identification in time and frequency domain, modal analysis and damage detection. The toolbox is being developed so that it contains classic SHM routines for educational purposes as well as allows for extensions with advanced routines for the research purposes.

Version v1.1 - Last updated: 28.09.2018, Aalborg University, Contact: msa@civil.aau.dk 
    
## Content of current version:
Find the detailed documentation inside MATLAB using "help" with a function/class below
  
### Management and processing of signal data: 
* Signals - class, contains multi-channel signal timeseries together with the
            relevant properties (data) and methods (functionality) for signal
            processing
 
### System identification:
* ID_TD_PolyReference - function, perform time domain identification on 
                          Signals object using autoregressive (AR) and output
                          ModalModel. (will be a part of the identification
                          class in later editions) 
 
### Modal analysis:
* ModalModel - class, containing the properties (data) and methods
                (functionality) that define a dynamic structural system in 
                terms of modal parameters
 
# Examples:
To get started with available examples, run following commands:
* open SignalsClassEx1.m
* open SignalsClassEx2.m
* open SignalsClassEx3.m
* open ModalModelClassEx1.m
* open ModalModelClassEx2.m
 
## Links:
https://se.mathworks.com/matlabcentral/fileexchange/68923-structural-health-monitoring-toolbox
