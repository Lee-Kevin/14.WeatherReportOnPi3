
#Introduce
This is a weather voice assistant on Raspberry Pi3

#Get Started
## Install the Text To Speech(TTS) 
I used ekho as the ekho tool as the TTS, please put hand on http://www.eguidedog.net/cn/ekho_cn.php to get started
## Install the music player
sudo apt-get install mplayer

## Install pytz
sudo easy_install pytz

## Download the Code
git clone https://github.com/Lee-Kevin/14.WeatherReportOnPi3

cd 14.WeatherReportOnPi3/code/weatherReport
chmod +x weather.py
./weather.py
