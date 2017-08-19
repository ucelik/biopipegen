#bioPipeGen

**1. Project Name:** 
bioPipeGen v1.0.0

**2. Project repository:** 
https://github.com/umms-hackathon/biopipegen.git

**3. Team members:**

**4. Aim:** 
The aim of this project is to create a pipeline generator based on nextflow.

**5. Project description:**
The pipelines will be generated using an interface uses d3. The resulting file will be a nextflow document.

* The parameters and channels that are going to be used in nextflow need to be defined while process' are creating.

* Process' and what script rill run in that process need to be created in workflow design window.

* Each process has input and ouput parameters. All parameters have types. When designing a workflow only the same type of input and output can be matchable. 

* All defined pipelines should be written to a nextflow file and be downloadable and nextflow file should run without error. 

* If an input doesn't match with an ouput of another process. This input needs to be defined as an input parameter that should be a line at the begining of nextflow file.   

* A parameter should be defined by clicking on a process in the UI.

* Remove support for previously defined parameters in UI. 

* While a script in a process being defined, the variables in the script are defined as ${varname} etc. This variable should be defined in the input or output as a variable. If not, process reports error, while saving.

* If two added process have the same name while saving, this should be checked and throw an error.

* When a defined process in the menu clicked, the details and some explanation about it should be opened like in "i" button on the process clicked. That modal should be made more intuitive.

* Paired end support for input parameters.

* Verification of the defined process' should be done. Test files or inputs for each parameter should be defined and before accepting a process, it should be run in the backend. 

Example: workflow design.

![Alt text](img/example1.png?raw=true "Example Workflow Design")

Example: parameter addition

![Alt text](img/example2.png?raw=true "Example Parameter Add")

Example: process editing

![Alt text](img/example3.png?raw=true "Example Process Edit")

Example: process visualization with input and outputs

![Alt text](img/example4.png?raw=true "Example Process Visualization")

Example: visualizations of inputs and outputs

![Alt text](img/example5.png?raw=true "Example Input Output Visualization")

**6. Supporting material and links:**
Supporting material. Sample files, external links.

All information about nextflow

https://www.nextflow.io

# biopipegen


