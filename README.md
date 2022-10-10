# Universally Unique Lexicographically Sortable Identifier

A function to generate a ULID based on the [ULID spec](https://github.com/ulid/spec).

## Installation

Follow the [instructions](https://docs.halon.io/manual/comp_install.html#installation) in our manual to add our package repository and then run the below command.

### Ubuntu

```
apt-get install halon-extras-ulid
```

### RHEL

```
yum install halon-extras-ulid
```

## Exported functions

These functions needs to be [imported](https://docs.halon.io/hsl/structures.html#import) from the `extras://ulid` module path.

### ulid()

**Returns** ULID as a string

**Example **

```
echo ulid(); // 01EH88W9FYYEQ2ANNRF5PCQVPM
```
