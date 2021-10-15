FROM lcardoso/cxlb-gnuradio-3.8:1.1
RUN apt-get install -y osmo-sdr 
RUN apt-get install gr-osmosdr 
RUN apt-get install usbutils
EXPOSE 2222
EXPOSE 5006
CMD gnuradio-companion

