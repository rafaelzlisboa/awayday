A submission system for the Away Day Brazil.

Running
=======

awayday requires Mongo. to install it (on OSX):

      brew install mongodb

to install the dependencies of the project:

      bundle

and, finally, start mongodb and the app server:

      mongod &
      rackup -D
