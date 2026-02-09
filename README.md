# Vizualising-Industry-Financial-Data-With-Excel
Performed data cleaning and wrangling with this dataset from HMRC which gave an analysis into the high performing industries across various regions in the UK to derive various insights that would be benefical to the public bodies.


 <img width="397" height="317" alt="image" src="https://github.com/user-attachments/assets/caf65650-d82a-4f47-bc9a-a173831f5f17" /> 
<img width="372" height="317" alt="image" src="https://github.com/user-attachments/assets/ad9b788c-7572-45ac-a5fb-b9aa60e9a4be" />


<img width="790" height="233" alt="image" src="https://github.com/user-attachments/assets/38c9a396-89e4-402d-94f0-99a5f0b9b915" />
<img width="308" height="345" alt="image" src="https://github.com/user-attachments/assets/57600068-43bb-4e71-a625-f113864723e4" />

DATA CLEANING
The 1.	Ensured duplicates  from 50039 to 50,009 , then took out summary 10 making 49,999were removed and accurate data quality was mainy=tained for the overll data set i.e making sure data type was accurate in accordance to the column header description, formatting coreesponding in order to ensure proper data linkage for visulaisation i.e dates, timestamps etc integer and currency.
2.	Also in order to agrregrate data deciisons and isights on geographical areas , I had to  utilis dat from external database ons and integrate it to te given data set to give a better output for regions and data relating to this .
3.	In checking the dat quality , analysing each individual column for  anomalies, found empty data and columns, took out . =IFERROR(H2,C:F, 2, FALSE)("Not Found")  =IFERROR(VLOOKUP(H2,C:F,2,FALSE),"Not Found")
4.	Check correct data format for coulmsn, date was in us format , had to change it to uk format , some dates were pre 1900 had to manipulate the data   =DATEVALUE(LEFT(S2772,LEN(S2772) - 4)&RIGHT(S2772,4) + 1000) 

5.	Change date s to the appropriate format pre 1900 issue had to distinguish and separate , anomalies first 12 1800 manually inputted the months , then used formula for the years =RIGHT(S2772,4). For the correctly formatted dates used this formula for months  =IF(S2="","",TEXT(S2,"mmmm"))  and for years =IF(S2="","",TEXT(S2,"yyyy"))

6.	  Got this errore for my pivota table in incorporation month and After identifying the eroor of why there were 2 bland rows( formula and non formula), I had to remove the formula from one in Australia to unify the blanks. Changing the blank name to unknown and used this to input the count ( Although t didn’t seem to work at first )



