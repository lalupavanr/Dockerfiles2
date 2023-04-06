#### COPY ####
copy instruction is useful to copy the files from local to image

#### Copy vs ADD ####
What is the difference between ADD vs COPY?
ADD and COPY does the same, copying the files from local to container. But ADD has some extra capabilities.
1. ADD can download the resources from internet to Container.
2. ADD can directly direct unzip the file into container if it is recognized format.