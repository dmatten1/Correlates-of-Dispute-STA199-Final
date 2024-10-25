# project

Project repo for STA 199 - Fall 2024.
 
 
 Data Dictionary for NMC -> country_resource 

 Position Variable Description
1 “stateabb” - 3 letter country Abbreviation
2 “ccode” - COW Country code
3 “year” - Year of observation
4 “irst” - Iron and steel production (thousands of tons)
5 “milex” - Military Expenditures (For 1816-1913: thousands of
current year British Pounds. For 1914+: thousands
of current year US Dollars.)
6 “milper” - Military Personnel (thousands)
7 “energy” - Energy consumption (thousands of coal-ton equivalents)
8 “tpop” - Total Population (thousands)
9 “upop” - Urban population (population living in cities with
population greater than 100,000; in thousands)
10 “cinc” - Composite Index of National Capability (CINC) score
11 “version” - Version number of the data set


Data Dictionary for MID -> country_conflict
1 DispNum - Dispute number
2 IncidNum - Incident number
3 StAbb - State abbreviation of participant
4 CCode - Country code/ state number of participant
5 StDay - Start day of incident (-9 = missing)
6 StMon - Start month of incident (-9 = missing)
7 StYear - Start year of incident
8 EndDay - End day of incident (-9 = missing)
9 EndMon - End month of incident (-9 = missing)
10 EndYear - End year of incident
11 InSide A - Incident Side A (1 = yes; 0 = no)
12 SideA - Dispute Side A (1 = yes; 0 = no)
13 Fatality - Fatality leve of Incident
    0 None
    1 1-25 deaths
    2 26-100 deaths
    3 101-250 deaths
    4 251-500 deaths
    5 501-999 deaths
    6 > 999 deaths
    -9 missing
14 FatalPre - Precise Fatalities, if Known (-9 = missing)
15 Action - Action in incident (bracketed numbers refer to corresponding hostility level)
    0 No militarized action [1]
    1 Threat to use force [2]
    2 Threat to blockade [2]
    3 Threat to occupy territory [2]
    4 Threat to declare war [2]
    5 Threat to use CBR weapons [2]
    6 Threat to join war [2]
    7 Show of force [3]
    8 Alert [3]
    9 Nuclear alert [3]
    10 Mobilization [3]
    11 Fortify border [3]
    12 Border violation [3]
    13 Blockade [4]
    14 Occupation of territory [4]
    15 Seizure [4]
    16 Attack [4]
    17 Clash [4]
    18 Declaration of war [4]
    19 Use of CBR weapons [4]
    20 Begin interstate war [5]
    21 Join interstate war [5]
    -9 Missing [-9]
16 HostLev - Hostility level of incident
    1 No militarized action
    2 Threat to use force
    3 Display use of force
    4 Use of force
    5 War
17 RevType1 - Revision Type #1
    0 Not applicable
    1 Territory
    2 Policy
    3 Regime/government
    4 Other
    -9 Missing
18 RevType2 - Revision Type #2
    0 Not applicable
    1 Territory
    2 Policy
    3 Regime/government
    4 Other
    -9 Missing
19 Version - Version number of data set 




