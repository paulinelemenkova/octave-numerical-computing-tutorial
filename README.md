# GNU Octave Tutorial Scripts

A set of GNU Octave tutorial scripts (.m) working through the fundamentals of numerical computing and scientific plotting. The scripts are a personal study reference, each focused on a specific topic, with two small helper functions.

## Topics covered

- Basics: arithmetic, built-in functions, variables, output formats, workspace save/load, help
- Vectors and matrices: construction (ranges, colon notation, linspace, logspace, zeros, ones, eye, rand), indexing and slicing, element-wise operations, transpose, diagonal and composite matrices
- Linear algebra: determinant (det), inverse (inv), rank, identity and diagonal matrices, solving linear systems (A\b, left/right division), condition number and ill-conditioning, least squares and the pseudoinverse (pinv), eigenvalues and eigenvectors (eig), Singular Value Decomposition (svd), magic squares
- Control flow: if/else, switch, for and while loops, disp/sprintf
- File and data I/O: fopen/fclose, csvread, textscan, running scripts
- Complex numbers
- Plotting: 2D line plots with styles, titles, labels, legends, grids and hold; multiple figure windows; exporting figures; matrix visualisation (imagesc, colormap); and dedicated demos for sine/cosine, rectified sine wave, tangent, subplots, 3D surface/mesh, histograms and quiver (vector-field) plots

## Files

- Octave_tut1script_commands.m: the main command walkthrough (basics, algebra, linear algebra, control flow, I/O)
- Octave_tut2..tut10 scripts: focused plotting demos (sine/cosine, rectified sine wave, subplots, 3D, tangent, surface, six subplots, histogram, quiver)
- sind.m, ustep.m: small helper functions (sine in degrees, unit step)

## Requirements

- GNU Octave: https://octave.org (most scripts are also MATLAB-compatible)

## Usage

Start Octave in this directory and run a script, for example:

    octave Octave_tut2script_sincos.m

Note: the main commands file carries a stray #!/bin/sh line and mixes runnable commands with illustrative fragments; run the individual commands inside an Octave session rather than executing the whole file.

## Author

Polina Lemenkova
ORCID: https://orcid.org/0000-0002-5759-1089

## License

See the LICENSE file in this repository.
