| DEVICEID | Description |
| --- | --- |
| MAXCELLVOLTAGE | Maximum Voltage of a cell out of n cells |
| MAXCELLTEMP | Maximum Temperature of a cell out of n cells |
| RESERVED_2 | x |
| RESERVED_1 | x |
| TOTALTEMPSENSOR | Value from BMS temperature sensor |
| RESERVED_4 | x |
| RESERVED_3 | x |
| RESERVED_6 | x |
| ORGANIZATION_ID | Id of the organization |
| RESERVED_5 | x |
| IGNITIONSTATUS | Showing the status of the vehicle, if it's ignition is on or off, typically 1 or 0 |
| PACKET_SEQUENCE_ID | To identify the order of the packets od data sent by TCU |
| TIMESTAMP | UNIX Timestamp. Typically starts from 1970, 1st January |
| MINTEMPID | sent from BMS |
| MINCELLID | id of the minimum temp cell |
| CUMULATIVE_POWER | Power in the battery pack currently exsisting |
| MAXTEMPID | sent from bms |
| MINCELLVOLTAGE | minimum voltage of a cell out of ns |
| CURRENT | Current running through BMS,(Battery) |
| INGESTION_TIME_UTC | The time the data gets uploaded in the cloud |
| RESERVED_8 | x |
| RESERVED_7 | x |
| DEVICEID | id of the device |
| SATELLITES | Satelites needed for gps location |
| LATITUDE | Latitude data in format of Degree Decimal Minutes |
| TEMPX | Temp data from 6 cell sensors |
| LONGITUDE | Longitude data in format of Degree Decimal Minutes |
| RANGECOVERED | Returns from TCU |
| HEADING | X |
| TEMPERATURE | Temperature of the BMS |
| CELLVOLTAGES | Aggrigated voltage values of n cells |
| RIDEMODE | Current Ride Mode of the Vehicle. (0, 3) |
| EVENT_TIME_IST | Timestamp of the Event. (Time the tcu received the data) |
| ODOMETER | Tracks the cumulative Milage |
| CHARGESTATUS | Status of the Charge mode. 4 unique chargemode available |
| GPSSPEED | Speed of the car, calculated through gps |
| SOC | State of Charge. Battery Percentage |
| CHARGECYCLE | How many times the battery got charged, from (20% to 80%) maybe!! |
| AVG_SPEED | Average Speed of the vehicle |
| MAXCELLID | Id of the Max positioned Cell |
| SOH | State of the Battery Health |
| BATTERYPACKVOLTAGE | Total Battery Pack Voltage, which contains n cells. |
| MINCELLTEMP | Minimum temperature of a cell out of ns |
| MILEAGE_DTE | total distance that can be traveled with the current battery percentage, before running out of power |
| MAXSPEED | Max Speed of the vehicle |
| SIGNALSTRENGTH | Strength of the signal . (the vehicle's TCU may use Sim, Wifi) |
| EVENT_TIME_UTC | The time the data gets ingested by the TCU, stored in UTC format |
| REMAINING_CAPACITY | Remaining capacity of the battary pack |
| INTERNBATTERY | Some Internal battery, which may have some voltage or current running through it |
| BATTERY_FULL_CAPACITY | Full capacity of the battaery pack during 100% SOH |
| NOOFCELLS | Total number of cells in the Battery Pack |
