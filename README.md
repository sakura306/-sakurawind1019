＃sakurawind1019
import RPi.GPIO as GPIO

GPIO.setmode(GPIO.BCM) 
GPIO.setup(25, GPIO.OUT) 

GPIO.output(25, GPIO.LOW)
sudo python led_high.py
