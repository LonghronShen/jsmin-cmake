# jsmin cmake support

Adding CMake support for jsmin made by Douglas Crockford.

## Usage

Just clone this repo, and execute these commands:

```shell
git clone --recurse-submodules https://github.com/LonghronShen/jsmin-cmake.git
cd jsmin-cmake && mkdir build && cd build
cmake .. && make
```

If you are on *nix, now you can use `make install` to install `jsmin` binary in your system.
Optionally, you can use `cpack` command to generate a `.deb` package if you are on a Debian like linux distro.

## License

[Douglas Crockford's License](https://github.com/LonghronShen/jsmin-cmake/blob/master/LICENSE)