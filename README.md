# Stock Exchange Observer - by Daniel Cintra


## To build project container: 

```sh
rake build_container
```

## To run project in development mode: 

```sh
rake run_dev
```

## To build project 

```sh
rake run_build
```

## To run tests 

```sh
rake run_test
```

## To list all commands available

```sh
rake
```

#### Obs: If your terminal doesn't support $(), you will need to update the rake file changing the commands removing the '$' and then will work fine. Like the example down here: 

```sh
docker container run -it -p 3000:3000 -p 35729:35729 -v (pwd):/app react:app
```

## Utilized Libraries

To develop the project were used:

* React
* Redux
* React Router
* Lodash
* Axios
* Moment
* Docker
* Rake

