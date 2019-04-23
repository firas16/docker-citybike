# docker-citybike

## Prequisites
Docker version 18 or higher

## Steps to run the project
Clone the project: \
  ```git clone https://github.com/firas16/docker-citybike.git``` \
Go to docker directory and run: \
  ```docker build --tag=spark-city-bike . ```\
  ```docker run -i --mount type=bind,src=$(pwd),dst=/result spark-city-bike```\
  ```cp -r /resultCityBike /result```\             
  ```exit```


You will get the results inside resultCityBike folder.
