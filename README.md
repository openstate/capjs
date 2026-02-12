# Usage

For each project create a production key that is difficult enough to solve (see existing keys).

There is also 1 development key available so that you don't have to run the `capjs` container
in development.
  

## Production
`sudo docker compose up -d`

Server will be availble under `cap.openstate.eu`.


## Development
In case you want to experiment with this in development:

  `sudo docker compose -f docker-compose-dev.yml up -d`

Server will be available under `localhost:3090`




