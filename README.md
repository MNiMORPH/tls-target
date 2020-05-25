# tls-target
Target for a RIEGL terrestrial laser scanner. The cylinder should be covered in retroreflective tape.

**Design by Bobby Schulz.** Please attribute following CC BY-SA 4.0 (see the [license](LICENSE))
[Add persistent Zenodo link and DOI here once these are generated.]


## Technical specifications

* Plastic body
  * Two 3D-printable components with a cylindrical angled fit
    * Cylinder
    * Caps (print two of these)
  * Suggested material: ABS
* Screws: 6x [#4 Thread Forming, 1/2" - Stainless](https://www.mcmaster.com/96001A210) (3 for each cap)
* Retroreflective tape **ADD INFO**

## Instructions

1. Generate gCode for your 3D printer. We use [Slic3r with a Prusa 3D printer](https://www.prusa3d.com/prusaslicer/).
2. Print using ABS, assuming that you are happy with our center mounting hole size. These are large prints, so we recommend that you do something to maintain even heating and cooling. This can be as simple as placing a large cardboard box over the printer while it works.
3. Tap the caps to a surveyor's standard 5/8" x 11 threads per inch. If you need a different hole size, just edit the provided 3D models before printing and use your desired taps.
4. Insert the top and bottom into the main cylinder and use the [screws](https://www.mcmaster.com/96001A210) to firmly attach it.
5. Wrap the body of the cylinder in retroreflective tape.

## Rendered images

![Cap: outside view](images/cap-3Dmodel-outside.png)

***3D model of the outside of an end cap.*** *Note countersunk screw holes to attach the cap to the cylinder. Center hole may be tapped to a standard surveying 5/8" x 11 thread.*


![Cap: inside view](images/cap-3Dmodel-inside.png)

***3D model of the inside of an end cap*** *The conical region mates with the inside rim of the cylinder.*


![Cylinder](images/cylinder-3Dmodel.png)

***3D model of the cylinder*** *The conical region mates with the inside rim of the cylinder. Note the three holes for the self-tapping screws.*
