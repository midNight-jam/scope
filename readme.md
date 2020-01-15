
# Scope Script
Scope script learnings

#1 first run
> E:\ScopeSDK\Scope.exe run -i E:\test.script -INPUT_PATH e:\vcroot -OUTPUT_PATH e:\vcroot -workingRoot e:\ScopeTemp -RESOURCE_PATH e:\VcRoot

•	The **run** parameter means compile & run a script <br>
•	The **-i** parameter indicates the input script <br>
•	The **-INPUT_PATH** and **-OUTPUT_PATH** tell the compiler where to read and write files – essentially we are using this to indicate the root folder of the “local” vc. <br>
•	The **-RESOURCE_PATH** is where other resources (views, DLLs, will be found) – We’ll re-use the vcroot for this also <br>
•	The **-workingRoot** identifies where Scope will put its temp files <br>
