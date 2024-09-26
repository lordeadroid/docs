# [use-effect](./index.md)

use effect hook is used to perform side effects in function components. Side effects might include data fetching, subscriptions, or manually changing the DOM.

### use effect dependencies

- a specific value is given

  > In case of a specific value is given, useEffect function will only run when that values changes.

- empty array

  > In case of empty array, useEffect function will only run once.

- no value

  > useEffect function will run every single time.
