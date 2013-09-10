# Demo App (times 7)

This is a simple shopping cart app, written in seven different composition strategies:

1. [vanilla](./vanilla) - Vanilla JS using delegation
2. [events](./events) - A typical JS event emitter pattern
3. [pubsub](./pubsub) - A typical JS pubsub pattern
4. [aop-simple](./aop-simple) - AOP using the simple AOP lib in this repo
5. [aop-meld](./aop-meld) - AOP using meld
6. [cujojs-1](./cujojs-1) - Declarative application composition using cujoJS
7. [cujojs-2](./cujojs-2) - Augments the behavior to cujojs-1 using a new composition plan, modularized concerns, and *without* changing any of cujojs-1's application modules.

## Requirements

Modern browsers, please: Chrome, Safari and FF latest, IE 10.  All of the AOP and composition techniques can be applied in any JS environment, but it's just faster and easier to code a conference demo without having to worry about older browsers.

## Running the apps

1. Clone the repo
1. Run `npm install` from the root dir of the repo (*not* the `demo-app` dir)
1. Run `npm start`
1. Open the corresponding url in your browser:
	- [vanilla](http://localhost:8000/demo-app/#vanilla) - http://localhost:8000/demo-app/#vanilla
	- [events](http://localhost:8000/demo-app/#events) - http://localhost:8000/demo-app/#events
	- [pubsub](http://localhost:8000/demo-app/#pubsub) - http://localhost:8000/demo-app/#pubsub
	- [aop-simple](http://localhost:8000/demo-app/#aop-simple) - http://localhost:8000/demo-app/#aop-simple
	- [aop-meld](http://localhost:8000/demo-app/#aop-meld) - http://localhost:8000/demo-app/#aop-meld
	- [cujojs-1](http://localhost:8000/demo-app/#cujojs-1) - http://localhost:8000/demo-app/#cujojs-1
	- [cujojs-2](http://localhost:8000/demo-app/#cujojs-2) - http://localhost:8000/demo-app/#cujojs-2

