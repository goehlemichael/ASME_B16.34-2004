# ASME B16.34-2013
# Inner Diamater (diametercalc.html)

## Derived from Table A-1 (page 183) of the Valves - Flanged, Threaded, and Welding End standards

## User inputs rating and nominal pipe size. Then the standard inner diameter is output in both inches and mm
## The user can choose between either inches and DN units

### Example user inputs:

    class: 2500
    NPS (DN): DN250
  
### Program outputs:

    184.2 mm, 7.25 in
    
## This program is useful for inspectors checking valve conformity during procurement/incoming/receiving inspections. It enables inspectors to quickly check valves nameplates and markings are correct. This program is usefull when there are a large variety of valve sizes being inspected for valve management.

# Ceiling Pressure (ceilingpressure.html)

## Derived from Table B-3M and B3 (pages. 188 - 190) of the Valves - Flanged, Threaded, and Welding End Standards

## User inputs rating and temperature. Then the ceiling pressure in bar and psig outputs for both standard and special class valves.

### Example user inputs:

    class: 600
    temperature: 400 Celsius

### Program outputs:

    Standard class 73.3 bar, Special class 100.6 bar
    
### To do:

1. finish value tables
    
     



