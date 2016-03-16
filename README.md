# bluerov-rpi2-navio -- NOT YET TESTED ON BLUEROV KIT --
Image repo for cctronics-ros-rqt RPi2 image including bluerov stack, navio+ interface and PREMPT RT kenel, and Arsub (navio+) including the standard bluerov config builds.

The cctronics clean image can be found at:

http://www.moosth.net/calabrothers/?p=595

This image contains QT5 and ROS indigo in the Raspbian PREMPT RT kernel.

The BlueRov Stack can be found at: 

https://github.com/bluerobotics/bluerov-ros-pkg

The ArduSub stack can be found at:

https://github.com/bluerobotics/ardusub

Build instructions for the Raspbian ARM install of ROS using catkin_make_isolated can be found at:

http://wiki.ros.org/ROSberryPi/Installing%20ROS%20Indigo%20on%20Raspberry%20Pi

#ArduSub Usage

Run ArduSub as: ./ArduSub.elf -A udp:[ip of host pc]:14550

Run your GCS as desired, i.e. qgroundcontrol or apmplanner or missionplanner. Set up yoru connection as UDP.

#Contributing
Merge requests preferred.
