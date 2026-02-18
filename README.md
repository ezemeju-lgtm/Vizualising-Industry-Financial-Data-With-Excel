

# Visualising Industry Financial Data With Excel

## Project Overview
To perform data cleaning and wrangling with this dataset from HMRC which gave an analysis into the high performing industries across various regions in the UK to derive various insights that would be beneficial to public bodies.

[Download Dataset for the projet here](https://github.com/ezemeju-lgtm/Vizualising-Industry-Financial-Data-With-Excel/blob/main/Data%20(1).xlsx) 

View interactive dasboard [here](https://onedrive.live.com/:x:/g/personal/4A4C51D8833956A4/IQAvVpLdI1RRRrnsiWgdpZ6iAeQTIh6nhr4xHXvk7A4cVZY?resid=4A4C51D8833956A4!sdd92562f54234651b9ec89681da59ea2&ithint=file%2Cxlsx&e=ndwbLV&migratedtospo=true&redeem=aHR0cHM6Ly8xZHJ2Lm1zL3gvYy80QTRDNTFEODgzMzk1NkE0L0lRQXZWcExkSTFSUlJybnNpV2dkcFo2aUFlUVRJaDZuaHI0eEhYdms3QTRjVlpZP2U9bmR3YkxW))
## Dataset Includes
- Company Category
- Company Status
- Region
- Country
- Company Category
- (and other related fields)

 <img width="397" height="317" alt="image" src="https://github.com/user-attachments/assets/caf65650-d82a-4f47-bc9a-a173831f5f17" /> 
<img width="372" height="317" alt="image" src="https://github.com/user-attachments/assets/ad9b788c-7572-45ac-a5fb-b9aa60e9a4be" />


<img width="790" height="233" alt="image" src="https://github.com/user-attachments/assets/38c9a396-89e4-402d-94f0-99a5f0b9b915" />
<img width="308" height="345" alt="image" src="https://github.com/user-attachments/assets/57600068-43bb-4e71-a625-f113864723e4" />

## DATA CLEANING

| Original Issue | What Was Wrong | How It Was Fixed |
|----------------|-----------------|------------------|
| Duplicates not addressed | 50,039 records with possible repeats | Removed duplicates, reduced to 50,009, then removed summary row |
| Wrong date format | US dates in a UK dataset | Converted to UK format using Excel date functions |
| Pre-1900 dates | Excel couldn't recognise them | Used formulas to extract year, manually entered months where needed |
| Blank rows in pivot table | Two types of blanks (formula vs blank data) | Standardised all blanks to "Unknown" |
| Missing regional data | Couldn't analyse by location | Imported external geographic data and merged it |

## Findings Include
- March as most  common month for incorporation
- Highest Groth Sector - Retail
- Lowest Growth Sector - Mainteanance
- Highest Turnover Region - London

  
