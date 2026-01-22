

# 1.0. Our Mission

In an effort to share its methodology and initiate collaboration, Airwars is making its codebook public as a resource for other organisations, institutions and individuals working in or around the field of monitoring civilian harm.

There are many different methodologies aiming for the same result. Airwars hopes to create a discussion among the research community on the ways in which data is collected, defined, and archived that enables the conditions for collaboration at the dataset design level. This we hope can enable organisations to better share and understand each other’s data, and encourages upcoming research projects to seriously understand data’s importance in the role of leveraging their mission. 

To see the impact of our work, please visit our archive at https://airwars.org/casualty-recording/

# 2.0. Development

The Codebook is in constant development and refinement. We are continuously working to ensure our data is accessible, comprehensible, and representative of our methodology and mission. Changes will inevitably occur as we adjust our data to the evolving needs of our monitoring process. 

We encourage users to send us questions, suggestions, and invites to collaborate using the Github infrastructure or by contacting our data manager at [clivevella@airwars.org](mailto:clivevella@airwars.org)

## 2.1. Downloading of datasets

Datasets mentioned in the codebook are available by sending an email with your request outline and purpose of use to [info@airwars.org](mailto:info@airwars.org). 

# 3.0. Contents

The Codebook refers to a .csv file containing the codebooks for 5 datasets maintained by Airwars that form the backbone of our archive.

These are:

* **aw\_data\_civcas\_incidents**: the main dataset containing unique rows that represent each published incident currently available on the Airwars archive;  
* **aw\_data\_civcas\_belligerents:** tracked belligerent data associated with published incident data;  
* **aw\_data\_civcas\_infrastructure:** data on infrastructure allegedly struck within incidents, including associated affiliations to groups or belligerents according to sources;  
* **aw\_data\_civcas\_victims:** repository of victim names as listed within sources, including the Gaza (from 2023\) specific National ID numbers from the Palestinian Ministry of Health (MoH) when a potential match with our research is found;  
* **aw\_data\_civcas\_casualties:** demographic of victim, and if known, their profession at the time of civilian harm

## 3.1. Column Descriptions

| Column | Description |
| :---- | :---- |
| **id** | System-generated, row id |
| **table** | Name of dataset |
| **column** | Name of column in dataset |
| **datatype** | Type of data as listed within the database |
| **datatype\_description** | Description of datatype in plain language |
| **values** | List of values as present on our back-end, separated by semi-colon. |
| **definitions** | Definitions, where available, of the values column. Any values which do not have a definition are omitted for the sake of brevity. Each grouping of value and its definition is separated by a semi-colon. Values and their definition are separated by a colon. Any values missing mean that their definition does not exist or that it does not require a definition. |
| **conditions** | Conditions necessary for a column to be correctly filled in the back-end. Cells containing conditionals mean that a field in the dataset can only be activated or filled when that conditional is met. Cells with just the name of another column mean that it requires that column to be filled. |

# 4.0. Updates

## 2026-01-22

- Definitions of values in the **definitions** column which are *NULL* are now omitted. This means that there might be a discrepancy in total values between the **definitions** and **values** columns. Any omission should be taken as a lack of need to describe said value, or that currently a definition of said value does not currently exist.
- Updated the description of the **definitions** column to reflect above change.
- Created the **versions** folder to hold previous versions of our codebook.
- General clean up of typos and punctuation.