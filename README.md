# mountpart

mount individual partitions of raw disk images using fuse

## Usage
```
usage ./mountpart [options...] <image file> [mount dir]
  options:
    -i | --index <n>     the index of partition to mount (default: 0)
    -t | --type <...>    fuse filesystem type (default: autodetect)
    -o | --opts <...>    options to provide to "mount.fuse -o"
    -e | --exec <...>    unmount after executing command
    -h | --help          show this help
  positional arguments:
    <image file>         path to raw disk image
    [mount dir]          path to target mount directory (created if missing)
                         (optional, if not provided partion is mounted as raw file in CWD)
```

## License

Licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)
- MIT license ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

