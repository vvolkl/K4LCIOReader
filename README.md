# K4LCIOReader

Generate EDM4hep collections from LCIO format data.

`K4LCIOReader` is a subclass that inherits from `podio::IReader`. And it holds an instance of `LCIO::LCReader`.

![K4LCIOReader](K4LCIOReader.png)

Some converters (from LCCollection to EDM4hep collection) are still being in developing.

## Dependencies

- [LCIO](https://github.com/iLCSoft/LCIO)
- [podio](https://github.com/AIDASoft/podio)
- [EDM4hep](https://github.com/key4hep/EDM4hep)

## Build

Suppose environment has been set properly, so that all dependencies can be found by CMake.

```
git clone https://github.com/ihep-sft-group/K4LCIOReader.git
cd K4LCIOReader; mkdir build; cd build
cmake ..
make
```

## Contributing

Contributions and bug reports are welcome!

