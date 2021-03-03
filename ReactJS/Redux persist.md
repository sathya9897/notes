# Redux-persist

- `persistStore` will persist the store to the storage. It returns a persistor/persisted version of the store.
- `persistReducer` persists the data of reducers that are whitelisted in the config object passed to it and combined reducer.
- `persistGate` is a provider that will provide the state and rehyderate it whenever needed, it should be wrapped around App.
