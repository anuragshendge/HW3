# HW3 CSC 791
DevOps CSC 791 Homework 3 repository   

## Install dependencies using the package.json file provided
      npm install     

## The assignment can be run in three different modes
> 1. With a single instance running on port #3000
> 2. Two instances running on port #3000 and port #3001
> 3  Two instances and a proxy server running on port 80 which will route the requests to either of the 
former ports   



### Part 1
>**/set** and **/get** routes are set and navigating to set will set the message **"this message will self-destruct in 10 seconds"** for 10 seconds and then expire. It can be accessed at /get.

### Part 2
>Visting **/recent** will display the 5 most recently visited sites.

### Part 3
>**/upload** is a POST request used to upload images to the redis server. **/meow** lets us access those images once!
 






