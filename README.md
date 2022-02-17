# A simple implementation of MVC in Vanilla JS

The basic idea of MVC is that rendering templates and updating state should be separate actions. For example, an event handler's only task should be to update the state with values input by the user; this should in turn trigger another function which will render the UI using the new state.

There are many frameworks and libraries available that implement this architecture, but sometimes we may want to implement it ourselves in vanilla JS. I want to show a simple and easy way to do this that is based on the original AngularJS framework.
