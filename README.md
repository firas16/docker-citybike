# docker-citybike

## Prequisities
Docker version 18 or higher

## Steps to run the project
Clone the project: \
  ```git clone https://github.com/firas16/docker-citybike.git``` \
Go to base directory and run: \
  ```docker build --tag=spark-city-bike . ```\
  ```docker run --mount type=bind,src=$(pwd),dst=/result spark-city-bike
```


