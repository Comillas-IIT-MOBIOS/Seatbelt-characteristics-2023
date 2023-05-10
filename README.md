# Seatbelt-characteristics-2023
Database containing the seatbelt characteristics of vehicles sold in the US from 1980 to 2022. This information was identified by applying an algorithm to the NCAP testing database. The pre-tensioner time-to-fire (TTF) and force, and load-limiting characteristics were identified for frontal impacts at 56.6 kph for the driver and front-seat occupants.

## Information contained in the database

+ TSTNO = Test number from NCAP testing database
+ VIN = Vehicle identification number of the vehicle used in the crash test
+ OCCLOC = Occupant location (01 = Driver; 02 = Front seat passenger)
+ PP_TTF_LAP =  Pre-tensioner TTF identified at the lap belt in ms (if equal 0.0, no pre-tensioning was identified)
+ PP_force_LAP = Pre-tensioning force identified at the lap belt in kN (if equal 0.0, no pre-tensioning was identified)
+ PP_TTF_SHOULDER = Pre-tensioner TTF identified at the shoulder belt in ms (if equal 0.0, no pre-tensioning was identified)
+ PP_force_SHOULDER = Pre-tensioning force identified at the shoulder belt in kN (if equal 0.0, no pre-tensioning was identified)
+ LL_first = Load-limiting force measured at the shoulder belt in kN (if equal 0.0, no load limiting was identified)
+ LL_second = Load-limiting force in kN of the last stage if a “two-stage” load-limiter device was identified (if equal 0.0, no ”two-stage” load-limiting device was identified)
