# Redux-saga

- There are 2 types of generators in sagas: listener and worker
- listener generators listen for actions with different types of effects available from saga effects
- whenever an action is fired, the listener for that action will be called, which will trigger the worker for that action type.
- `take` listens for a particular action type and dispatchs corresponding worker only once.
- `takeEvery` listens for a particular action type and dispatchs corresponding worker by spawning a new one for each call.
- `call` is just used to call a function with it's parameters so that the function could be yielded if need be.
- `put` is used to dispatch actions with payload after completion of side effects.
- `delay` freezes the generator for the given time to it, before calling the next yield.
- `all` is used to merge multiple sagas to be passed into root saga
