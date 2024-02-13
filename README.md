# Url Shortener

The Url shortener is deployed on Heroku so it is accessible at : [Url shortener UI](https://urlshortener-ui-1c6938ccabc0.herokuapp.com/).

It's on Eco mode on Heroku so on the first connection the server needs to launch so it could take some time for the first shorten Url.

## Launching application

To launch latest backend and frontend images and a postgresql database you can use the docker-compose file present in docker folder.

```bash
docker compose -f docker/url-shortener.yaml -p "url-shortener" up
```

You can access this application at http://localhost:3001