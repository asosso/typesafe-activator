typesafe-activator
==================

This project is a Docker container for Typesafe Activator. 

Base [docker image](http://www.docker.io) to run a [Typesafe Activator](https://typesafe.com/community/core-tools/activator-and-sbt) project

    Typesafe Activator and sbt get you started with the Typesafe Reactive Platform

## Getting the container

The container is very small and available on the Docker Index:

    docker pull asosso/typesafe-activator

## Using the container

Just trying out Typesafe Activator.

If you just want to run a single instance of MaxScale server to try out its functionality:

    docker run -i -t asosso/typesafe-activator /bin/bash

## Build the container

To create the image `asosso/typesafe-activator`, execute the following command on the typesafe-activator folder:

    docker build -t asosso/typesafe-activator .

## Thanks

* [@_hilbert_](https://twitter.com/_hilbert_) - for his collaboration

## Contribute

Contributions are welcome.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

Copyright 2015 Andrea Sosso
Licensed under the MIT License