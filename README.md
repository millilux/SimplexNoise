Simplex Noise
=============

2D, 3D and 4D simplex noise functions. 

Usage
-----

    double x = 5;
    double y = 10;
    double z = 15;
    double w = 20;
    
    double noiseVal2d = SimplexNoise.noise(x, y);
    double noiseVal3d = SimplexNoise.noise(x, y, z);
    double noiseVal4d = SimplexNoise.noise(x, y, z, w);

About
-----

This is a C# port of the Java implementation by Stefan Gustavson (stegu@itn.liu.se).
 
The original paper can be found [here](http://staffwww.itn.liu.se/~stegu/simplexnoise/simplexnoise.pdf)