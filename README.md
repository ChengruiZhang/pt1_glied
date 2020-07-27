# pt1_glied

As an example to implement controller, see:
https://github.com/m-lundberg/simple-pid

loop:
1. Neural Network choose the next desired action based on obervation
2. The desired action is set as input of PT1-Glied, with the respose of PT1-Glied as output (real action after PT1)
3.  take the real action in environment, get the observation 
