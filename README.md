simplexnoise
============

As copied from the original C implementation by Stefan Gustavson:


This package implements "Simplex Noise" as presented by
Ken Perlin at a relatively obscure and not often cited course
session "Real-Time Shading" at Siggraph 2001 (before real
time shading actually took on), under the title "hardware noise".
The 3D function is numerically equivalent to his Java reference
code available in the PDF course notes, although I re-implemented
it from scratch to get more readable code. The 1D, 2D and 4D cases
were implemented from scratch by me from Ken Perlin's text.

## Installation

	go get github.com/larspensjo/Go-simplex-noise/simplexnoise

## Usage instructions

// 1D simplex noise
func Noise1(x float64) float64

// 2D simplex noise
func Noise2(x, y float64) float64

// 3D simplex noise
func Noise3(x, y, z float64) float64


## Copyright and licensing

The source code is in the public domain. See top of simplexnoise.go.

