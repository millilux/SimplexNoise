Simplex Noise
=============

2D, 3D and 4D simplex noise functions. 

Usage
-----

    double x = 5;
    double y = 10;
    double z = 15;
    double w = 20;

    double 2DnoiseVal = SimplexNoise.noise(x, y);
    double 3DnoiseVal = SimplexNoise.noise(x, y, z);
    double 4DnoiseVal = SimplexNoise.noise(x, y, z, w);

About
-----

This is a C# port of the Java implementation by Stefan Gustavson (stegu@itn.liu.se).
 
The original paper can be found at http://staffwww.itn.liu.se/~stegu/simplexnoise/simplexnoise.pdf