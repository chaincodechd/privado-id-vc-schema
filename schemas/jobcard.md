[comment]: <> "Job Card Schema Documentation"

# Job Card Schema

## Reg_No

`Reg_No` represents the unique registration number assigned to a family during the job card registration process.

```json
"Reg_No": "JCRD123456"
```

## State_Code

`State_Code` is a string identifier denoting the state where the job card has been issued.

```json
"State_Code": "28"
```

## District_Code

`District_Code` refers to the code of the district in which the job card was registered.

```json
"District_Code": "530"
```

## Block_Code

`Block_Code` identifies the block (administrative division) under which the job card falls.

```json
"Block_Code": "101"
```

## Panchayat_Code

`Panchayat_Code` indicates the numeric string representing the Panchayat jurisdiction.

```json
"Panchayat_Code": "202005"
```

## Village_Code

`Village_Code` is the code corresponding to the village in the registration.

```json
"Village_Code": "300789"
```

## Family_Id

`Family_Id` is a string representing the unique identifier of the family unit.

```json
"Family_Id": "FAM1234567"
```

## Head_of_Household

`Head_of_Household` contains the full name of the household head.

```json
"Head_of_Household": "Ravi Kumar"
```

## Father_or_Husband_Name

`Father_or_Husband_Name` stores the name of the father or husband of the head of the household.

```json
"Father_or_Husband_Name": "Suresh Kumar"
```

## House_No

`House_No` refers to the house number or address detail for location identification.

```json
"House_No": "12A"
```

## Caste

`Caste` represents the caste classification of the family.

```json
"Caste": "SC"
```

## Registration_Date

`Registration_Date` indicates the date of job card registration in `YYYY-MM-DD` format.

```json
"Registration_Date": "2022-07-15"
```

## job_card_iss

`job_card_iss` represents the status or details about job card issuance.

```json
"job_card_iss": "Issued"
```

## dt_job_card_iss

`dt_job_card_iss` is the date the job card was issued.

```json
"dt_job_card_iss": "2022-07-20"
```

## Is_JC_verified_new

`Is_JC_verified_new` indicates the verification status of the job card.

```json
"Is_JC_verified_new": "Yes"
```

## FRA_Beneficiary

`FRA_Beneficiary` shows if the household is a beneficiary under the Forest Rights Act.

```json
"FRA_Beneficiary": "No"
```

## Regn_Entry_Date

`Regn_Entry_Date` is the timestamp of the registration entry.

```json
"Regn_Entry_Date": "2022-07-15T10:00:00Z"
```

## Event_Flag

`Event_Flag` is used to denote any special event or modification in the job card record.

```json
"Event_Flag": "Updated"
```

## Event_Reason

`Event_Reason` gives a textual reason for the event or update recorded.

```json
"Event_Reason": "Correction in name"
```

## Event_Date

`Event_Date` indicates the date of the recorded event.

```json
"Event_Date": "2022-08-10"
```

## Family_Photo_Hash

`Family_Photo_Hash` is a hash value representing the family photograph for verification.

```json
"Family_Photo_Hash": "sha256-f3b5c889d889..."
```

## Applicants

`Applicants` is an array containing details of individuals under the job card. Each entry includes the applicant's registration number, name, demographics, UID info, and status flags.

```json
"Applicants": [
  {
    "Reg_No": "JCRD123456",
    "Applicant_No": 1,
    "Applicant_Name": "Sunita Devi",
    "Gender": "Female",
    "Age": 35,
    "Ac_No": "XXXXXX1234",
    "BPL_Data": "Yes",
    "Disabled": "No",
    "Relation_code": 1,
    "Mobile_No": "9876543210",
    "Name_as_per_Aadhar": "Sunita Devi",
    "Active1": 1,
    "Active2": 0,
    "Active3": 0,
    "Active4": 0,
    "App_Reg_date": "2022-07-15",
    "UID_Enc_Cipher": "enc_uid_hash",
    "UID_NIC_DemoAuth": "Success",
    "is_abps_enabled": "Yes",
    "Event_Flag": "New",
    "Event_Reason": "Added",
    "Event_Date": "2022-07-15",
    "App_Name_BankPO": "S. Devi",
    "Photo_Hash": "sha256-photoapp1"
  }
]
```
