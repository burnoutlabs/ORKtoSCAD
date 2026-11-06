# ORKtoSCAD

> **This fork is being archived.** Apart from this notice, it is identical to
> the upstream repository,
> [bdureau/OpenRocketToOpenScad](https://github.com/bdureau/OpenRocketToOpenScad),
> where its only change (a Java refactor with tests and docs) was merged on
> 2024-09-27. Use, report issues against and contribute to the upstream
> repository instead; nothing further will be committed here.

ORKtoSCAD is a Java-based command-line program that converts OpenRocket files (.ork) into OpenSCAD (.scad) files. The program extracts components from the .ork file and generates corresponding OpenSCAD files, which can be further converted to SVG or STL files for use with CNC routers or 3D printers.

## Features

- **Bulkhead**
- **Freeform Finset**
- **Trapezoid Finset**
- **Centering Ring**
- **Elliptical Finset**
- **Nose Cone**
- **Body Tube**
- **Tube Coupler**
- **Inner Tube**

## Prerequisites

- Java Development Kit (JDK) installed.
- Basic knowledge of command line operations.
- An OpenRocket (.ork) file.

## How to Use

To run the program and convert an OpenRocket file to OpenSCAD:

1. **Open the command line** and navigate to the main directory containing the `orkToScad.jar` file.

2. **Run the JAR file** with the following command:
    ```
    java -jar orkToScad.jar
    ```

3. **Follow the prompts** to select the input `.ork` file and specify the output directory. You can also choose whether to keep the intermediate folder created during the extraction process.


## Development & Contributing

See the [docs](docs/README.md) for how to get started with development.
## License

None. Upstream [bdureau/OpenRocketToOpenScad](https://github.com/bdureau/OpenRocketToOpenScad) has no license, and this fork follows upstream.
