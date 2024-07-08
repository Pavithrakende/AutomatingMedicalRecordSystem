# AutomatingMedicalRecordSystem

Automated the testing of OpenMRS, a medical record system, using the TestRigor tool to improve efficiency in recording, updating, and accessing patient data.
Ensured accuracy, security, and compliance with industry regulations while integrating seamlessly with existing healthcare software to reduce manual effort.

//TestCases//

enter"Admin"into"Enter your username"
enter"Admin123"into"Enter your password"
click"Laboratory"
click"LogIn"
click"Register a patient"
enter"Pavithra"into"Given (required)"
enter"P.S"into"Family Name (required)"
click"next-button"
click"Female"
double click"Female"
click"next-button"
enter"12"into"Day"
click"Month"
select"January"from"Month"
enter"1988"into"year"
click"next-button"
enter"test"into"Address"above the"Address 2"
enter"test"into"Address 2"
enter"mumbai"into"City/Village"
enter"india"into"Country"
click"next-button"
enter"3456788"into"What's the patient phone number?"
click"next-button"
select"Doctor"from"relationship_type"
click"Select Relationship Type Doctor Sibling Parent Aunt/Uncle Supervisor Patient Child Niece/Nephew super"
enter"vasanthe"into"Person Name"
click"next-button"
check page contains"Pavithra P.S"


//URL for the above testcases in TestRigor//
https://app.testrigor.com/test-suites/2xpqFDn35gwiYPv7N/test-cases/d65000f4-30c9-411e-be07-c7908ee867c3
