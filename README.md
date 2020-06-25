# 그린그래스 환경 셋업을 위한 셀 스크립트 파일
  라즈베리파이에서 aws greengrass를 사용하기 위해서는
  최소 python3.7버전 이상, hardlink / symlink protect 설정
  memory cgroup enable이 필요하다. 
  최신 버전 stretch OS에서는 Python 설치를 sudo apt-get install -y python3.7 로 가능하거나, 디폴트로 3.7 이상 버전이 설치 되어 있지만.
  stretch 버전이 낮은 경우에 이 스크립트 파일을 실행해서 환경셋업을 하면 된다.

# making_gg_env.sh 사용법
  $mkdir ~/home/pi/making
  $cd ~/home/pi/making
  $sudo chmod +x making_gg_env.sh
  $sudo ./making_gg_env.sh
  
  5~10분 소요
