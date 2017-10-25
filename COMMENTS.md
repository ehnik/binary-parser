#This was written in Ruby.

#Since account balance is an 8-byte float, it is unpacked as a double-precision float.

#I had the parser iterate through the records once, incrementing and filling
#in the relevant variables along the way, rather than storing the records and
#processing the data afterward. I did this to keep runtime and storage at a minimum.

#Each record is temporarily stored in a hash to make viewing each individual
#record easy (helpful for debugging).
