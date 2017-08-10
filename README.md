# HelperMethodSteps
StepByStep on creating an helper method
By creating an input parameter, you are essentially declaring a variable local to
the method itself with its assignment being determined by whatever value is 
copied/passed-in at the method call. That input parameter’s
variable name then becomes the identifier that we use throughout the method’s 
code block wherever that variable needs to be referenced.


 Understanding When To Use Input Parameters

The main rule of thumb for when and where to incorporate input 
parameters is to do so wherever you need to separate what remains 
the same, with what sometimes is different between each call to 
the helper method. In this case, what’s different each time you 
call the method is the measure/cup ratio, whereas the calculation
details are the same with each method call. In other words, we’re

adding variability to the method through whatever we choose to pass in 
via the measureToCupRatio input parameter, while the logic within the code 
block remains unchanged. To demonstrate this further and to illustrate how you 
can utilize more than one input parameter.
