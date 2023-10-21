First create the image of Docker
`$ docker build -t mycalculator .`

Second create the container of the images
`$ docker run -it --name mycalc -d mycalculator`

Third, our app is running on the background for this reason we apply the next command 
`$ docker exec -it mycalc java Calculator`

