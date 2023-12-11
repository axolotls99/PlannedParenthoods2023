# Planned Parenthood Clinics in the US
Example of Data:
| Name (... Health center)  | City   | State | Zip   | Abortion | HRT |
|---------------------------|--------|-------|-------|----------|-----|
| Southern Arizona Regional | Tuscon | AZ    | 85712 | Y        | V   |

Data was collected from the Planned Parenthood website in late November 2023. Exact addresses were removed from the dataset for safety reasons, which is also why I am not providing the geocoded coordinates of the clinics. I figure having the city/state/zip will work okay for most applications.

The dataset contains 567 entries.

Data also includes values for abortion 'Y' or 'N' and HRT 'Y' 'N' or 'V'. A value of 'Y' was chosen for abortion if the clinic offered abortion services after 10 weeks, such as an abortion pill or a surgical option. No distinction was made between various options. A value of 'Y' was chosen for HRT if the dataset author had reason to believe the clinic offered hormone prescriptions to transgender patients. A value of 'V' was used if the dataset author had evidence the clinic offered virtual prescriptions. I am sure mistakes exist in both of these values. 

Data was originally used for a mapping project for GEOG 418 at SIUE. 
