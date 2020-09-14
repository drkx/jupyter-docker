# Open AI gym
This is just a fork from https://github.com/EdBoraas/jupyter-docker with minor fixes and a docker-compose file added. Any credits should go in the direction of Ed Boraas.

## Requirements
Of course you need to have [Docker](https://docs.docker.com/get-docker/) installed and running

## Usage
Download the [docker-compose](https://raw.githubusercontent.com/drkx/jupyter-docker/master/docker-compose.yml) file, then run it and show the logs to get the right url with token:
```bash
docker-compose up -d && docker-compose logs -f
```
Copy the url which has the form http://127.0.0.1:8888/?token=<SOME_RANDOM_NUMBERS_AND_LETTERS>, paste it in your browser and close the logs with ctrl-c.
The compose file should create a notebooks directory in which you can put your Jupyter notebooks. You can find a nice space invaders example [here](https://kyso.io/eoin/openai-gym-jupyter).

## Contributing
Please let me know when you see room for improvement.
