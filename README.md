## DISCLAIMER: VERY BUGGY. EVEN THE INSTRUCTIONS MAY BE WRONG.

# Conform: A GPL Multithreaded Video Converter

# Description:
I was looking around for a good open source GPL media converter. But every single one I found seemed to be slow and only able to process one file at a time. So I wrote an FFmpeg wrapper that can take on several files at once. Enjoy! And report any bugs you find so that I can fix them. :)

# Building Instructions
This project has only been tested to work on Linux (Linux Mint 17) and is unlikely to work on any other OS at the moment. It project requires Qt5, FFmpeg, and jsoncpp. The following commands should have you covered:
```
sudo add-apt-repository ppa:ppa:mc3man/trusty-media
sudo apt-geet update
sudo apt-get install qt5-default qttools5-dev-tools cmake ffmpeg
git clone https://github.com/open-source-parsers/jsoncpp.git
cd jsoncpp
cmake .
make && sudo make install
```




