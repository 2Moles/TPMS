gr-tpms
Software for capturing, demodulating, decoding, and assessing data from automotive tire pressure monitors using GNU Radio.

Tire pressure monitoring systems (TPMS) are becoming common on automobiles, and in certain countries, are required as a condition of sale. Most TPMS devices use simple wireless communication techniques such as:

ASK or FSK modulation
Manchester bit coding
Small CRCs or checksums
Unique device identifiers
Background
This project was developed as an effort to understand and analyze TPMS systems using Software Defined Radio (SDR) techniques. It draws inspiration from various resources, including talks and research on TPMS.

For foundational background, you may refer to resources such as Jared Boone's talk from ToorCon 15:
"Dude, Where's My Car?: Reversing Tire Pressure Monitors with a Software Defined Radio"
[video]-https://drive.google.com/file/d/1M1_lCjWA8eLtimvh_9LWHi21T5Br41ef/view?usp=drive_link
[slides-https://docs.google.com/document/d/17_kX3xaZYVoGkvDxAEjqU7cd5iy1TUZE4jlSLTTpJoU/edit?tab=t.0#heading=h.hd0ck9r387zg]

Software
This project has been built and tested with the following tools and dependencies:

Python 2.7
FFTW (Fastest FFT in the West)
GNU Radio 3.7.3 (should work with earlier 3.7 releases)
rtl-sdr and gr-osmosdr
crcmod (CRC library for Python)
Optional dependencies for tpms_burst_ping include Watchdog, portaudio, pyaudio, and numpy.

Hardware
To get started with this project, you'll need SDR hardware like a DVB-T USB dongle or HackRF, along with compatible antennas and cabling.

License
This project is licensed under the GNU General Public License (GPL) v2 or later.

Contact
For questions, feedback, or contributions, you can reach Subham Sarkar at:

subham23@kgpian.iitkgp.ac.in
