# Project Brief

- **Title**: Schweizer Fristenrechner
- **Purpose**: To provide a tool for calculating legal deadlines in Switzerland, considering various holidays and court recesses.
- **Core Functionality**: Users can input a start date and select a type of deadline (days or months). The tool calculates the end date, taking into account weekends, holidays, and court recesses. 
- **Legal Basis**: The calculations are based on the Swiss Civil Procedure Code (ZPO), specifically Articles 142, 143, 144, and 145, which govern the start, calculation, compliance, extension, and suspension of deadlines.
- **Calculation Rules**:
  - **Article 142**: Deadlines triggered by a notification or event start the following day. If a deadline is calculated in months, it ends on the day in the last month that corresponds to the start day. If that day is missing, it ends on the last day of the month.
  - **Article 143**: Submissions must be made by the last day of the deadline. For electronic submissions, the time of receipt is decisive.
  - **Article 144**: Legal deadlines cannot be extended, but court deadlines can be extended for good cause if requested before the deadline expires.
  - **Article 145**: Legal and court deadlines are suspended during certain periods, such as Easter, summer, and winter holidays.

- **Important Note**: According to the Federal Court ruling 5A_691/2023 dated August 13, 2024, the deadline calculated in months begins on the day of the triggering event, not the following day.

- **Court Holidays**:
  - 7 days before and including 7 days after Easter
  - July 15 to August 15
  - December 18 to January 2 