#### ENTRYPOINT ####
ENTRYPOINT is also used to run the container just like CMD. But they are few diffrence 
1. we cant override ENTRYPOINT, but we can override CMD
2. we cant override ENTRYPOINT, If you try to do so it will go and append to the ENTRYPIONT command.
3. if we use CMD & ENTRYPOINT and dont give any command from terminal,CMD acts as aargument provider   to ENTRTYPOINT.
4. CMD will supply default arguments to ENTRYPOINT
5. you can always override CMD arguments from run time 
6. you can stop misusing your image with other commands.