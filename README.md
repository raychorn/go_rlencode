# RLE - Run Length Encoder / Decoder

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

Handles integers or more specificalluy int arrays.

See the unit tests for the details.

[]int{3, 1, 1, 2, 1} --> []int{3, 1, -1, 2, 1} ... a negative number is the run length when it appears in the output.

The result is not always smaller than the input but it does make handling large arrays easier when debugging or logging results.

Notice how the encoder uses a struct like a bucket of data into which we pour values that get combined using a finite state machine into the encoding.  This works very much like a file handle into which you dump a serial stream of bytes. At the end you need to flush when writing and likewise here you need to flush the encoder to complete its processing.

## Getting Started <a name = "getting_started"></a>

Install using go get, like this: "go get -u github.com/raychorn/go_rlencode"


See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

None.  This is pure GO.

### Installing

Step 1:  Install using go get, like this: "go get -u github.com/raychorn/go_rlencode"


And repeat

```
until finished
```

Now you can use the code or report the issue to me and I will ignore your request.

## Usage <a name = "usage"></a>

See the unit tests to see how to use this code.

(c). Copyright 2020, Ray C Horn, All Rights Reserved.