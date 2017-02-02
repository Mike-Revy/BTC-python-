# BTC-python-
Python and BTC process journal 

Just a bunch of python progs that come out of Mastering Bitcoin: Unlocking Digital Cryptocurrencies
Book by Andreas M. Antonopoulos

I downloaded python35 .. I created a path  to it in windows .. 
I imported the python bitcoin library https://github.com/vbuterin/pybitcointools

btctest.py - gets a random key and displays in various formats: hex, decimal, wif, compressed private key, wif_compressed, EC generator point G to get public (x,y) key, hex encoded prefix 04 public key, public key prefix adjusted (y is odd/even), generate btc Address from public key

crazy.py -- I had a lot of trouble importing python libraries.  Best is to use npm install .. I did it the 'hard' way and downloaded and put everything somewhere on my computer .. doh!  This program shows me windows path and tests to se if I can import all the libraries I wanted. If it runs without throwing an error - u should be good. 

ec_math.py .. has a bug I need to fix 
fibo.py - a test program to generate fibonacci numbers - need to fix 
get_utxo.py - gets unspent outputs for address = '1Dorian4RoXcnBv9hnQ4Y2C1an6NJ4UrjX' 


