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

## Getting Started <a name = "getting_started"></a>

Install using go get. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo.

## Usage <a name = "usage"></a>

Add notes about how to use the system.

(c). Copyright 2020, Ray C Horn, All Rights Reserved.