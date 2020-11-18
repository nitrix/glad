# glad

Glad-generated bindings for OpenGL with core profile and CMake support.

| Component  | Version   |
|------------|-----------|
| Glad       |    0.1.33 |
| OpenGL     |       4.6 |
| CMake      |       3.0 |

## Usage

Add a submodule to your Git repository:
```bash
git submodule add https://github.com/nitrix/glad-cmake lib/glad
```

Add to your CMakeLists.txt:
```cmake
ADD_SUBDIRECTORY(lib/glad)
TARGET_LINK_LIBRARIES(foo PRIVATE glad)
```

## Maintenance

[Glad](https://github.com/Dav1dde/glad) offers two convenient way to generate the bindings; either

1. Using an [online tool](https://glad.dav1d.de).
2. Using a [python script](https://github.com/Dav1dde/glad/blob/master/setup.py).

This repository is maintained manually and on a per-needed basis.

Open an issue or a pull request if you have specific needs that I missed.

## Credits

Entirely goes to the [glad generator](https://github.com/Dav1dde/glad) project.  

I made this repository for convenience only.

## License

Except for the work done by the glad authors which has [its own license](https://github.com/Dav1dde/glad/blob/master/LICENSE),
you may use this repository however you like.

See [UNLICENSE](UNLICENSE) for more information.
