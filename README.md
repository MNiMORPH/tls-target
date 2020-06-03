[![DOI](https://zenodo.org/badge/266727775.svg)](https://zenodo.org/badge/latestdoi/266727775)

# tls-target
Target for a RIEGL terrestrial laser scanner. The cylinder should be covered in retroreflective tape.

## Attribution
Design by [Bobby Schulz](https://github.com/bschulz1701). Documentation by [Andrew D. Wickert](https://github.com/awickert/) and Bobby Schulz. Please attribute following CC BY-SA 4.0 (see the [license](LICENSE)). The persistent citation to the most recent version available on Zenodo is as follows:

***Schulz, B., and A. D. Wickert. umn-earth-surface/tls-target. [doi:10.5281/zenodo.3873809](https://doi.org/10.5281/zenodo.3873809).***

## Technical specifications

* Plastic body
  * Two 3D-printable components with a cylindrical angled fit
    * Cylinder
    * Caps (print two of these)
  * Suggested material: ABS
  * Infill: 15-20%
* Screws: 6x [#4 Thread Forming, 1/2" - Stainless](https://www.mcmaster.com/96001A210) (3 for each cap)
* Retroreflective tape: [3M™ Diamond Grade™ Conspicuity Markings Series 983](http://www.identi-tape.com/3M-conspicuity.htm)

## Instructions

1. Generate gCode for your 3D printer. We use [Slic3r with a Prusa 3D printer](https://www.prusa3d.com/prusaslicer/).
2. Print using ABS, assuming that you are happy with our center mounting hole size. These are large prints, so we recommend that you do something to maintain even heating and cooling. This can be as simple as placing a large cardboard box over the printer while it works. See more information on ABS printing [here](https://www.matterhackers.com/articles/how-to-succeed-when-printing-with-abs).
3. [Tap](https://www.mcmaster.com/2521A647) the caps to a surveyor's standard 5/8" x 11 threads per inch. If you need a different hole size, just edit the provided 3D models before printing and use your desired taps.
4. Insert the top and bottom into the main cylinder and use the [screws](https://www.mcmaster.com/96001A210) to firmly attach it.
5. Wrap the body of the cylinder in retroreflective tape.

## Rendered images

![Cap: outside view](images/cap-3Dmodel-outside.png)

***3D model of the outside of an end cap.*** *Note countersunk screw holes to attach the cap to the cylinder. Center hole may be tapped to a standard surveying 5/8" x 11 thread.*


![Cap: inside view](images/cap-3Dmodel-inside.png)

***3D model of the inside of an end cap*** *The conical region mates with the inside rim of the cylinder.*


![Cylinder](images/cylinder-3Dmodel.png)

***3D model of the cylinder*** *The conical region mates with the inside rim of the cap. Note the three holes for the self-tapping screws.*


<br>
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
