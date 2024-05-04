# ParkingSlotDet
Parking Slot Detection &amp; Positioning Tool for ROS

## Installation

```
git clone https://github.com/SheldonFung98/ParkingSlotDet
```

## Usage

```
roslaunch psdet_linebase PSDetLB.launch
```

## Description

![overviw](/assets/overview.png)

## Topic

### Subscribe

* /sur_camera/image_raw: [sensor_msgs::Image] Input birdview image

### Publish

* /PSDetLB/detImg: [sensor_msgs::Image] output birdview detection image