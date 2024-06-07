# insta360_oculus

Following instructions here 

https://github.com/jetsonhacks/camera-caps?tab=readme-ov-file#installation

```
$ sudo apt update
$ sudo apt install python3-pip
$ pip3 install dataclasses
# Install v4l2-ctl
$ sudo apt install v4l-utils
$ sudo apt install python3-pyqt5
```

Run the following command to check if the INsta369 will be listed 

```
v4l2-ctl --list-devices
```
to check the detail setting of the camera 

```
v4l2-ctl --all -d /dev/video0    # this information is recieved from the above command
```

following this video as well 

https://www.youtube.com/watch?v=rs4mQcJAjMM&t=715s
