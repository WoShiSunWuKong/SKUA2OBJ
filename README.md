# SKUA2OBJ

Converts SKUA-GOCAD Ascii surfaces into Wavefront Object format (.obj)

## Usage

This application should be run in a terminal with the following command:

```
SKUA2OBJ.exe <SKUA-GOCAD surface file> <output OBJ file> <optional: shift (format: X/Y/Z)>
```

On macOS/Linux you can run the application using the mono framework:

```
mono SKUA2OBJ.exe <SKUA-GOCAD surface file> <output OBJ file> <optional: shift (format: X/Y/Z)>
```

Hence SKUA-GOCAD is desinged for the creation of three dimensional underground models, a shift to the coordinate center migth be required to display the meshes in other software, e.g. Blender 3D.
This shift can be commited as the last parameter.

```
SKUA2OBJ.exe surfaces.ts surfaces.obj -4412345/-5612345/-123.4
```

## Download the latest Release

You can download the latest release of [SKUA2OBJ here](https://github.com/stdonn/SKUA2OBJ/releases/latest) 
**!!!ATTENTION!!!** All versions are still pre-releases and are not build for working in production environments

## TODO

Currently only the mesh is converted. In the future also the style of the SKUA-GOCAD surfaces can be converted to an object material (*.mat)

## Built With

* [VisualStudio](http://www.visualstudio.com/) - C# IDE

## Authors

* **Stephan Donndorf** - [stdonn](https://github.com/stdonn)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
