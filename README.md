# lab 8
name: vishruth bharath

# answers to questions
**how are graceful degradation and service workers related?**
service workers basically enable graceful degradation by letting our app fall back to cached assets or localStorage when the network is either unavailable or slow. basically, if a requested service can't be fetched from the network, its up to the service worker to intercept the request and provide a fallback, cached copy instead. because of this, core functionality of our app is still able to work offline or under poor connectivity, turning edge case/potential failures into something more predictable and manageable, similar to the goal of graceful degradation.