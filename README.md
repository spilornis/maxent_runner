# maxent_runner
Maxent wrapper

# Examples

Simple run:

python runmx.py --input samples\bradypus.csv --output outputs --env layers --features linear,quadratic

Advanced run:

python runmx.py --input samples\bradypus.csv --output outputs --env layers --features linear,quadratic --replicates  --jack --curves