<<<<<<< HEAD
master changes
junior dev changeis
=======
junior dev changes
junior dev changes2
>>>>>>> feature
Module
from selenium import webdriver
from selenium.webdriver.common.keys import Keys

# Open Chrome
driver = webdriver.Chrome(
	'C:/Users/HP/Desktop/Drivers/chromedriver_win32/chromedriver.exe')

# Open URL
driver.get(
	'http://demo.automationtesting.in/FileDownload.html')

# Enter text
driver.find_element_by_id('textbox').send_keys("Hello world")

# Generate Text File
driver.find_element_by_id('createTxt').click()

# Click on Download Button
driver.find_element_by_id('link-to-download').click()
from selenium import webdriver
from selenium.webdriver.common.keys import Keys
import selenium.common.exceptions
import time
import random

# Login Credentials
username = input('Enter your Username ')
password = input('Enter your Password ')
url = 'https://instagram.com/' + input('Enter username of user whome you want to send message')
"""
A sample python script for downloading the current non-redundant lists from
the RNA 3D Hub (http://rna.bgsu.edu/rna3dhub).
Usage:
python download_nrlist.py
"""

import urllib2


# nrlist are provided at 8 resolution cutoffs
resolutions = ['1.5A', '2.0A', '2.5A', '3.0A', '3.5A', '4.0A', '20.0A', 'all']

base_url = 'http://rna.bgsu.edu/rna3dhub/nrlist/download'

for resolution in resolutions:
    release = 'current' # can be replaced with a specific release id, e.g. 0.70
    url = '/'.join([base_url, release, resolution])
    try:
        nrdata = urllib2.urlopen( url ).read()
        # nrdata now contains the string with data in csv format
        print "Release %s, resolution %s: download complete" % \
              (release, resolution)
    except:
        print "Release %s, resolution %s: download failed" % \
              (release, resolution)
