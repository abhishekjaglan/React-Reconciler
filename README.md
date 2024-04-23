# React-Reconciler
Custom Implementation of React Reconciler

- Calulated difference between the oldState and newState (state perceived after receiving new data)
- That difference is/are the components(here to-do list elements) to be added or removed or updated, RATHER than updating/rerendering the whole page after each time new data is received

This algorithm is called Diffing, developed by people at Facebook (currently Meta)
For more info - https://legacy.reactjs.org/docs/reconciliation.html
