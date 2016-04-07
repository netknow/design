# Some applications need to be responsive to a user. 
In this series of notes we will discuss about the various application requirements. We will also see how these application
requirements follow a set of unique patterns. These unique patterns defines a scope of discussion among peers who want to 
work on the task of designing these applications. 

We will see how application development is a assembly line of development efforts. These assembly lines have various 
different topologies. One of them is named waterfall model. In the natural process of evolution we will see how the methodolo
-gies of software development process has evolved.

## Separation of concerns
These applications are layer of softwares in a sense that the top layer listens to client interactions.
All the layers interact among each other and maintain a scope; that is different from the layer above and the layer below.

Examples:
1. A middle ware that exposes API's that can be called by a user of this middleware. This middleware sends back response
to the client within a specific maximum time. You can think of middlemans in a general business process.

You as a user want to order grocery from a new startup that has been selling the best quality vegetables for least of the
prices. As a user you interact with a website and you don't care about whom does the website interact to so that at the
end of the process you receive vegetables at your home.

The website has a similar nature. The whole website doesn't go straight to a driver to hand over your vegetables, it talks to 
someone else. That someone else talks to another entity. Eventually everything resolves down to your vegetables delevered at 
your doorstep.

## Protocol
Protocol is nothing but a set of rules that are supposed to be followed in order to get some work done. These set of rules
are converted into an algorithm. This algorithms has all the entities that would interact together to accomplish the task.

## Design
How should the entities interact, so that the business process becomes financially viable, is the base line of software 
development. Many patterns emerged out while dealing with such software development processes. These patterns are the
templates that are used by software developers. The final specialized product is called software design.
