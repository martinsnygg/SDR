# Tags
# Comment
# --- AIS Ship Tracking ---
161975000,GMSK,AIS Channel A | Class A/B transponders | 87B GMSK 9600 baud
162025000,GMSK,AIS Channel B | Class A/B transponders | 87B GMSK 9600 baud

# --- ADS-B Aircraft Tracking ---
1090000000,ADS-B,ADS-B Extended Squitter | Mode S Transponders | Manchester encoded PPM
978000000,UAT,Universal Access Transceiver | US General Aviation | CPFSK

# --- Mode S/A/C Aircraft Interrogation ---
1030000000,PSK,Mode S Interrogation | Ground stations to aircraft
1090000000,PSK,Mode S Reply | Aircraft responses

# --- ACARS Aircraft Data ---
131550000,AM,ACARS | Data from commercial aircraft

# Usage Notes:
# AIS: Use GMSK demodulator, 9600 baud
# ADS-B: Use ADS-B demodulator in GQRX or pipe to dump1090
# Mode S: PSK demodulation needed for interrogations
# ACARS: AM demodulation, specialized decoder needed