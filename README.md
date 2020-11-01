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
