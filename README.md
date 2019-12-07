# XY Utilities
Utilities for working with XY data in LabVIEW

The primitive datatype is "XY-data", a cluster containing an X and Y array.

![XY-Data](images/XY-Data.png)

Arrays of XY-data are also supported.

![XY-Data-Array](images/XY-Data-Array.png)

## Getting Started
Download and install using the VI Package Manager as described [here](https://levylabpitt.github.io/)

Video tutorial [1](https://drive.google.com/file/d/1CvF9rPJewbxkMVLEgYQJH42OVeokuThd/view?usp=drivesdk) and [2](https://drive.google.com/file/d/1rAFpSUpno209tP4lu6OkoyVjX_knOz51/view?usp=drivesdk).

## Usage
### Arithmetic Functions
#### Add.vi

![Add](images/Add.vi.png)

#### Subtract.vi

![Subtract.vi](images/Subtract.vi.png)

#### Multiply.vi

![Multiply.vi](images/Multiply.vi.png)

#### Divide.vi

![Divide.vi](images/Divide.vi.png)

### Array Functions
### Reverse.vi

![Reverse.vi](images/Reverse.vi.png)

### Sort.vi

![Sort.vi](images/Sort.vi.png)

### Decimate.vi

![Decimate.vi](images/Decimate.vi.png)

### Swap X and Y.vi

![Swap X and Y.vi](images/Swap-X-and-Y.vi.png)

### Get X and Y.vi

![Get X and Y.vi](images/Get-X-and-Y.vi.png)

### Signal Processing
#### Derivative.vi

![Derivative.vi](images/Derivative.vi.png)

#### Resample.vi

![Resample.vi](images/Resample.vi.png)

#### Interpolate.vi

![Interpolate.vi](images/Interpolate.vi.png)

#### Average.vi

![Average.vi](images/Average.vi.png)

#### FFT Spectrum.vi

![FFT Spectrum.vi](images/FFT-Spectrum.vi.png)

#### FFT Power Spectrum.vi

![FFT Power Spectrum.vi](images/FFT-Power-Spectrum.vi.png)

## Examples

### Tree.vi

![Tree.vi](images/Tree.vi.png)

**Tree.vi** shows all of the subVIs contained in the xy_utilities.lvlib library. It also displays the equivalent LabVIEW primitive VI (for example xy_utilities.lvlib:Sort.vi is equivalent to Sort 1D Array).

#### Arithemtic Functions

![Tree-0-Arithmetic](images/Tree-0-Arithmetic.png)

#### Array Functions

![Tree-1-Array](images/Tree-1-Array.png)

#### Signal Processing

![Tree-2-Signal-Processing](images/Tree-2-Signal-Processing.png)

### Test.vi

![Test.vi](images/Test.vi.png)

**Test.vi** is a JKI State Machine that demonstrates how to build a signal processing application with scripted states.

## Contributing
Please contact [Patrick Irvin](p.irvin@levylab.org)

## License
[BSD-3](https://opensource.org/licenses/BSD-3-Clause)
