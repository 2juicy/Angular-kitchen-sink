ng2Boilerplate
=====================

An Angular 2 and Bootstrap easy to start, A-Z startup project
----------------

version: 0.95

ready to be impressed with Angular 2?


Check this working demo: http://ng2.javascriptninja.io
====


The goal behind ng2Boilerplayer is to deliver an easy to start Angular 2 base application that includes the basis around what any solid single page application requires.

to install::
```
git clone https://github.com/born2net/ng2Boilerplate.git
cd ng2Boilerplate/
npm install
gulp LiveServer
```


(optionaly: copy node_modules/angular2 and node_modules/rxjs from ./node_modules directory to root of project so TypeScript can find it in the path while transpiling.
 However you don’t need these directories during runtime as system.js will load both libs from node_moduldes directory respectively)

What features of Angular does this app cover? well pretty much all the core stuff:

- Routing with Aync of modules (App1 and App2) on a per navigation basis
- jQuery integration the Angular way via BrowserDomAdapter
- CommBroker for service management, value sharing and evet mediator 
- Global Consts
- Responsive design (on size change Angular components will react) 
- RX reactive operators and subscribers throughout the app
- Lots of standalone components such as Modal, Sliders, Todo, Tabs and more
- Shared state (Side menu and file menu)
- Dependency injection and decorators such as @Host
- Dependency sharing
- ES6 such as arrow functions, Map, let and more
- Hook into application lifecycles
- Form and validation (both via FormBuilder and manual creating Control Groups)
- Form observables and operations
- Node server side CRUD for RX calls
- Todo data model persistence and sync to node server via CRUD
- Subclass / Inheritance ES6 (Notes component) 
- Static shared lib and single reference file
- Themes
- Pipes
- Interfaces
- UI data binding / uni and 2 way
- Document generation
- and much more...

Generated docs are@ http://ng2.javascriptninja.io/docs/globals.html


Contributors are welcome!





