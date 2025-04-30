[comment]: <> (EKYC Schema Documentation)

# EKYC Schema

## Reg_No

`Reg_No` represents the unique registration number assigned to the applicant.

```json
  "Reg_No": "REG1234567"
```

## Applicant_Name

`Applicant_Name` represents the full name of the applicant.

```json
  "Applicant_Name": "John Doe"
```

## Applicant_name_as_per_Aadhaar

`Applicant_name_as_per_Aadhaar` is the name of the applicant as it appears on the Aadhaar card.

```json
  "Applicant_name_as_per_Aadhaar": "Johnathan Doe"
```

## Aadhaar_number

`Aadhaar_number` represents the 12-digit Aadhaar number of the individual.

```json
  "Aadhaar_number": "123456789012"
```

## Aadhaar_hash_key_value

`Aadhaar_hash_key_value` is the hashed value of the Aadhaar number used for secure verification.

```json
  "Aadhaar_hash_key_value": "e3b0c44298fc1c149afbf4c8996fb924"
```

## eKYC_status

`eKYC_status` indicates the current status of the Aadhaar-based eKYC verification process.

```json
  "eKYC_status": "Verified"
```

## eKYC_verified_date

`eKYC_verified_date` is the date and time when the eKYC verification was successfully completed.

```json
  "eKYC_verified_date": "2023-11-10T14:30:00Z"
```

## Individual_Photo_Path

`Individual_Photo_Path` specifies the storage path of the applicant's photo file.

```json
  "Individual_Photo_Path": "/photos/john_doe.jpg"
```

## Individual_File_Name

`Individual_File_Name` is the name of the file containing the applicant's photo.

```json
  "Individual_File_Name": "john_doe.jpg"
```
