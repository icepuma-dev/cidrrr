# cidrrr

Does the same as [cidrr](https://github.com/stuarthicks/cidrr), but with one more `r` :D

Makes inspection of CIDR blocks a bit easier :)

## Installation

```shell
cargo install cidrrr
```

## Usage

```shell
# shows the first and last IP of the block
cidrrr 10.105.4.0/24

10.105.4.1
10.105.4.254
```

```shell
# shows all IPs of the block as a JSON array
cidrrr -a -o json 10.105.4.0/24

["10.105.4.1", "10.105.4.2", "10.105.4.3", ..., "10.105.4.253", "10.105.4.254"]
```
