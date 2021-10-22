＃sakurawind1019
import RPi.GPIO as GPIO　　　　Iはi
import time

GPIO.setmode(GPIO.BCM) 
GPIO.setup(25, GPIO.OUT)

GPIO.output(25, GPIO.HIGH)
time.sleep(2) # この間は点灯し続ける

GPIO.cleanup() # <- 消灯  

実行  python3 ファイル名.py
