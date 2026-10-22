# uvsd-doom-gnu-radio
GNU Radio Companion workspace for doom and python files to help facilitate the demodulating and display of modulated DOOM gameplay in the 915MHz amateur radio band.

To start the viewer and gameplay, start running the workflow in GNUradio, then run ```python doom_raw_sender1.py --file doom_raw.bin```, then start view_doom_zmq.py to view the demodulated gameplay output.

Before running, you need to install the following dependencies in the radioconda prompt terminal
```
pyserial
opencv-python
numpy
pyzmq
```
RTL-SDR driver download (not needed until receiving ota) 

Windows: https://www.rtl-sdr.com/tag/zadig/

Linux: `sudo apt-get install rtl-sdr`
