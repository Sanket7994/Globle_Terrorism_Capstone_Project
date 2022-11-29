![terroryzm](https://user-images.githubusercontent.com/109847409/204507200-c7ff9bc6-99cb-4d1f-8227-5ca468993e7c.jpg)

# Data Science Capstone Project: Globle Terrorism Data (GTD)

Created by Sanket Chouriya


**Introduction**


The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.

**Definition of terrorism**

"The threatened or actual use of illegal force and violence by a non-state actor to attain a political, economic, religious, or social goal through fear, coercion, or intimidation."

**About Dataset**

Diamention: (181691, 135)
Geography: Worldwide
Time period: 1970-2017, except 1993
Unit of analysis: Attack

**Data Variables Used:**

 * *iyear* - Year of incident
 * *extended* - Duration of incident (less or more than 24 hour)
 * *Summary* - A brief narrative summary of the incident, noting the “when, where, who, what, how, and why.
 * *alternative_txt* - This variable identifies the most likely categorization of the incident other than terrorism.
 * *country* - This field identifies the country or location where the incident occurred.
 * *region* - This field identifies the region in which the incident occurred and divided into 12 categories.
 * *city* - This field contains the name of the city, village, or town in which the incident occurred.
 * *attacktype1_txt* - This field captures the general method of attack and often reflects the broad class of tactics used.
 * *success* - This field identifies If the incident was successful or not.
 * *suicide* - This variable is coded “Yes” in those cases where there is evidence that the perpetrator did not intend to escape from the attack alive.
 * *weaptype1_txt* - This field records the general type of weapon used in the incident.
 * *weapsubtype1_txt* - The corresponding weapon sub-types for each primary weapon type. 
 * *targtype1_txt* - The target/victim type field captures the general type of target/victim.
 * *targsubtype1_txt* - The target subtype variable captures the more specific target category.
 * *natlty1* - This is the nationality of the target that was attacked.
 * *gname* - Terrorist gang name
 * *nkill* - Total Number of Fatalities
 * *nkillter* - Number of Perpetrator Fatalities
 * *nwound* - Total Number of Injured
 * *propextent_txt* - Property Damage Type (Minor, Major, Catastrophic, Unknown)
 * *Ishostkid* - This field records whether or not the victims were taken hostage
 * *ransom* - This field records whether or not the attacker demanded ransom money or not
 * *ransomamt* – ransom money demanded
 * *ransompaid* – ransom money given 
 * *hostkidoutcome_txt* – This field captures the eventual fate of hostages and kidnap victims.

Access this link to know detail of columns: https://start.umd.edu/gtd/downloads/Codebook.pdf

**☆ HIGHLIGHTS:**

 * Overview of the whole world
 * Know terrorist trends and regional differences
 * Be able to answer the big question posed in the end


**☆ CHALLENGE:**

 * Understand the meaning of the columns.
 * Find the right chart to show the change of trends across each region.
 * Thinking about big question for analysis
 * Find an approach to analyze and answer the big question.
 * Some difficulties in coding, drawing maps.
