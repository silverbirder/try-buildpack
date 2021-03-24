# Node.js Sample App using NPM

## Building

`pack build my-app --buildpack gcr.io/paketo-buildpacks/nodejs --builder paketobuildpacks/builder:base`

## Running

`docker run --interactive --tty --publish 8080:8080 my-app`

## Viewing

`curl http://localhost:8080`
