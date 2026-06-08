

### &#x20;                                      Database Requirement Analysis



### 

|**Table name**|**Purpose**|**Primary Key**|**Important Fields**|
|-|-|-|-|
|Users|Stores user account information|User\_ID|Name, Email, Password, Phone\_Number, Role|
|Pharmacies|Stores pharmacy details|Pharmacy\_ID|Pharmacy\_Name, Address, Contact\_Number, Email|
|Medicines|Stores medicine information|Medicine\_ID|Medicine\_Name, Category, Manufacturer, Description|
|Medicine\_Stock|Tracks medicine availability in pharmacies|Stock\_ID|Pharmacy\_ID, Medicine\_ID, Quantity, Price, Last\_Updated|
|Search\_History|Stores user medicine searches|Search\_ID|User\_ID, Medicine\_ID, Search\_Date|







