#Docker Compose Reverse Proxy With Nginx Test

This is my first attempt to string together three containers together in the
following fashion

* Nginx which reverse proxies to
* An app that consists of
  * A python flask app that is connected to
  * A redis instance

Ideally to see this in action all you should have to do is to run
`docker-compose up` and if you visit the ip of your `docker-machine`
