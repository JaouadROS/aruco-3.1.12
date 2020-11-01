# aruco-3.1.12
This is not an official repository of aruco. It is used to test aruco with SQPnP algorithm.

## Usage
Create a folder called build and execute those commandes in it:
```bash
cmake ..
make -j8
```

Then go to build/utils and run the example

```bash
./aruco_test cam0.mp4 -c cam0.yml -s 0.165 -d ARUCO

```

##Unit test
The link to cam0.mp4 and cam0.yml
[Here](https://mega.nz/folder/YsU2AY7L#Of0oChqpFBh34Y0-GOQ7VQ/folder/clUj2ITZ)

This version of Aruco uses IPPE internally, so if sqpnp == 0 then the pose given is from IPPE.
