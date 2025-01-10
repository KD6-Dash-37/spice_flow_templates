# SpiceFlow Templates

This repository contains the FlatBuffer schema definitions for the SpiceFlow project. These schemas define the data structures for:
- Order book data streams.
- Trade feeds (optional).

## Usage

### Compiling Schemas
Use the `flatc` tool to compile the `.fbs` schemas into your desired language.

#### Example:
To generate Rust and Python code:
```bash
flatc --rust --python -o generated schemas/order_book.fbs
