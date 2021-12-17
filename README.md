# airport_flight_schedules
Airport flight-schedules for use as base data for development and testing, eg. for work the with the Airport Gate Assignment Problem, AGAP, GAP, SAP. 

Four sets of data are provided, each representing one week of traffic (monday - sunday) for one of each; mini, small, mediom and big airport. There are also simplified plans for terminal layouts, and information about maximum aircraft size and walking distanses for each stand.

![image](https://user-images.githubusercontent.com/825983/146515151-a1a7bb8a-d4f4-4054-8537-6fdd5a0831ea.png)

The flight-schedules are provided as excel-files, containing data as illustrated:

![image](https://user-images.githubusercontent.com/825983/146508033-8abc6c9d-3cee-4316-ae24-acc7d4bb7a4b.png)

The flight-schedules are based on real historic flight-data pulled from AODB, anonymized/obfuscated as follows:
- Date:	shifted to random future date
- ScheduleTime: original data from AODB
- Flight_Id: altered so airline is anonymized
- Arr/Dep: original data from AODB
- Airport: original data from AODB
- Region: original data from AODB. (D=domestic flight, S=Schengen, NS=non-Schengen)
- Airline: anonymized
- AC_Reg: obfuscated	
- Aircraft: original data from AODB
- Seats: original data from AODB	
- Pax: seats x 90%	
- Stand: original data from AODB 
