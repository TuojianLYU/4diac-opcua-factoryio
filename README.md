# The distributed control app with a remote OPC UA server and a FactoryIO converge station example

## Video address
[https://www.youtube.com/watch?v=cGpOHWy649Y&ab_channel=TuojianLyu](https://www.youtube.com/watch?v=cGpOHWy649Y&ab_channel=TuojianLyu)

## Description
There are in total three devices are used in 4diac IDE where one in orange color is for initializing OPC UA nodes while other two devices are for executing distributed FBs of the control application. Those three devices are created via Forte containers running in the cloud VM via three different port numbers, of course can be running with different IP addresses also. Once deploying FBs to the Forte containers, we need to configure the OPC UA driver inside FactoryIO with the correct driver and OPC UA server address (opc.tcp://xxxx.xxxx.xxxx.xxxx:4840). After the OPC UA server configuration and connection, the pip line is set up for the distributed control application in 4diac IDE to the plant simulation software FactoryIO.
