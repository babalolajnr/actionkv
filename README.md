# actionkv
An in-memory key-value store with a 
command-line interface. Extracted from the `Rust in Action Book` by Timothy Samuel McNamara.

## Operations supported by `actionkv`
| Command                  | Description                               |
| ------------------------ | ----------------------------------------- |
| get `<key>`              | Retrieves the value at key from the store |
| insert `<key>` `<value>` | Adds a key-value pair to the store        |
| delete `<key>`           | Removes a key-value pair from the store   |
| update `<key>`           | Replaces an old value with a new one      |