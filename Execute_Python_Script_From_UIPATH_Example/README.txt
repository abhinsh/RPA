A simple example of Executing_Python_Script_From_UIPATH

See package_detail.jpg file above for the package (UiPath.Python.Activities) needed to install in UiPath Studio in order to run Python workflow. 

** Consideration for this workflow: the location of python.exe is maintained in PATH environment variable.

## ACTIVITIES description of this package:

1. Run Python Script: To execute a python script. (Must be inside the "Python Scope" activity)
2. Python Scope: Details such as Python Path, Current Working folder, x86/x64 version specification etc. 
3. Load Python Script: Same as "Run Python Script" activity except that it can store the output as a Python object which can be later used for purther processing. 
4. Invoke python method: Execute a particular method(function) from the script. 
5. Get Python Object: Convert Python object to a VB(.net) object. 


UiPath Studio 2022.4.3 Community License
