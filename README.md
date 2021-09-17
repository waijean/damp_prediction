## Task
1.	Build a model to predict likelihood of developing damp and mould in our properties.
2.	Test the hypothesis that, properties with vulnerable tenants have higher likelihood of developing damp and mould problems.  

## Data
1.	Case: Dataset containing case history. All tenant communication, service request, complaints are recorded as cases. Cases are organised by case type and sub types. Damp & Mould is a specific sub type, which falls under case type Direct Maintenance.
2.	Tenancy: Dataset containing tenancy information
3.	Vulnerability: Dataset containing records of our tenants who has reported to be vulnerable. A tenant can have multiple vulnerability.

|Table|	Column|	Description|
| --- | --- | --- |
|Case|	case_number	|Unique identifier for case|
|Case|	unit_ref	|Unique identifier for property|
|Case|	unit_build_year	|Year in which the property was built|
|Case|	case_status	|Current status of the case|
|Case|	case_type	|Classification of the case, to indicate type of the case|
|Case|	case_sub_type	|Further classification of the case, indicates the sub-type of the case|
|Case|	case_create_date	|The date the case was created|
|Tenancy|	unit_ref	|Unique identifier for property|
|Tenancy|	tenancy_id	|Unique identifier for tenancy|
|Tenancy|	tenancy_start_date	|Start date of the tenancy contract|
|Tenancy|	tenancy_end_date	|End date of the teanancy contract|
|Vulnerability|	tenancy_id	|Unique identifier for tenancy|
|Vulnerability|	Vulnerability	|Name of the vulnerability|

