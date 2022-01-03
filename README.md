# refugee_health_screening_database
import refugee health data into redcap


01/03/2021
People: Azadeh Tasslimi 

Objective: 
Washington state epi's need to import refugee data into redcap from Electronic Disease Notification (EDN, part of CDC). This happens on the monthly basis, and includes transformation steps from raw file:

	- Rename columns to all lower case 
	- Add record_id columns and copy alien number into it
	- TBClass needs a map dictionary transformation

Workflow:
	Human downloads raw data to path on Y drive: 
	
	Y:\Confidential\DCHS\CDE\Refugee Health\Refugee Health Screening Database\EDN imports for database\2021\EDN and PDT Reports (DS 2054)
	
	Script takes files, transforms it, and imports into Redcap. 
	
	Script saves transformed file in a completed directory in same path
