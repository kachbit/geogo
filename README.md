# geoko
geogooooooooooooooooooooo

## geogo point system:

### formula:
truncate( ((5000000/d)) - (t < 100 ? (t/5) : 200) )

### variables:
d = distance(miles)
t = time(seconds)

### description:
-base score is 5000000/distance (lower distance is better)
-the timing logic subtracts time/5 from the base score only if time is less than 100, otherwise, subtract 200 (lower time is better)
-the final result is truncated to avoid decimals

### notes:
-the formula may be modified in the future if needed
