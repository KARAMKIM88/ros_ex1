# ros_ex1

1) 소스 받기
$ git clone https://github.com/KARAMKIM88/ros_ex1.git

2) 빌드 폴더로 이동
$ cd ~/catkin_ws

3) 빌드 및 설치
$ catkin_make

4) 패키지 등록 
$ source ./devel/setup.bash

5)ROSCORE 띄우기 ctl + alt + T 를 눌러서 새로운 창을 열어줍니다. => 
$ roscore

6) 노드 실행 
$ rosrun my_first_ros_pkg talker.py
