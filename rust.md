# Rust

## Memory safe

Drop when variables go out of scope.

### Double free error

For stack data, shallow copy. For heap data, move instead of shallow copy. Clone method for deep copy.
Copy trait. Drop trait. Transfering ownership to functions vs borrowing.

### Preventing data races

Only one reference (mutable) or multiple references (immutable) per scope.

### Dangling references

Lifetimes.

### Slices

Linking derived data with the data of original data. String literals are slices.

## Structs

Structs vs tuples. Field init shorthand. Struct update syntax. Tuple structs. Unit-like structs. Derived traits.
Display trait. Debug trait. Defining methods.
