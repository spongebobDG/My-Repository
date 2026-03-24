프로젝트명 & 한 줄 설명: dg_first_package: ROS 2 Humble 기반의 기초 노드 통신 테스트.

개발 환경 (Environment):

OS: Ubuntu 22.04 LTS

ROS 2: Humble Hawksbill

Language: Python

패키지 기능: 어떤 메시지를 주고받는지 간단히

실행 방법 (Usage):

Bash
cd ~/ros2_ws
colcon build --packages-select dg_first_package
source install/setup.bash
ros2 run dg_first_package [노드이름]
