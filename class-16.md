# Class 16:

## Event Driven Applications
![](https://flink.apache.org/img/usecases-eventdrivenapps.png)
**Event-Driven Programming** is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision.

**concepts of the Event-Driven Programming:**
1- An Event Handler is a callback function that will be called when an event is triggered.
2- A Main Loop listens for event triggers and calls the associated event handler for that event.
**Emitting Events**
EventEmitter that allows us to get started incorporating Event-Driven Programming in our project right away.

* In node.js an event can be described as a string with a corresponding callback.
* An event can be "emitted" multiple times
* we can choose to only listen for the first time event is emitted.
![](https://sergeyzhuk.me/assets/images/posts/reactphp-memcached/logo3.png)
**The EventEmitter class** is defined and exposed by the events module:
```
const EventEmitter = require('events').EventEmitter;
```
![](https://www.wikitechy.com/tutorials/node-js/img/nodejs-images/node-js-event-emitter-process.png)

### Vocabulary Terms:
**Authorization:** Authorization is the function of specifying access rights/privileges to resources, which is related to information security and computer security in general and to access control in particular. 

**Role Based Access Control:**  is an approach to restricting system access to authorized users. It is used by the majority of enterprises with more than 500 employees, and can implement mandatory access control (MAC) or discretionary access control (DAC).