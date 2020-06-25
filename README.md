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
  
  완료 후 
  $rm -rf ~/home/pi/making
  
  5~10분 소요

# shell script for making aws greengrass enviroment with raspberrypi (Revolution Pi)
  It's needed version > python3.7 & hardlink, symlink protection, memory cgroup enable(kernel) to use aws greengrass.
  In lateset rapsberry pi OS - stertch - , Above version of python3.7 can be installed. But old stertch can't.
  This script will be helpful.
  
 # Usage of making_gg_env.sh
   $mkdir ~/home/pi/making
   $cd ~/home/pi/making
   $sudo chmod +x making_gg_env.sh
   $sudo ./making_gg_env.sh
   
   after this process.
   
   $rm -rf ~/home/pi/makiing
   
   It will take 5~10minutes.
   
   - This script contains bulid installation of Python 3.7.
   
