[comment]: <> (EKYC Schema Documentation)

# EKYC Schema

## Reg_No

`Reg_No` represents the unique registration number assigned to the applicant.

```json
 "Reg_No": "REG1234567"
```

## Applicant_No

`Applicant_No` represents the unique identifier for the applicant, often linked to their registration.

```json
 "Applicant_No": "APP9876543"
```

## Aadhaar_hash_key_value

`Aadhaar_hash_key_value` is the hashed value of an identifier (like Aadhaar number) used for secure verification, without exposing the original number.

```json
 "Aadhaar_hash_key_value": "e3b0c44298fc1c149afbf4c8996fb924a27ae41e4649b934ca495991b7852b855"
```

## eKYC_status

`eKYC_status` indicates the current status of the electronic Know Your Customer (eKYC) verification process.

```json
 "eKYC_status": "Verified"
```

## eKYC_verified_date

`eKYC_verified_date` is the date and time when the eKYC verification was successfully completed. It should be in a standard date format, preferably ISO 8601.

```json
 "eKYC_verified_date": "2023-11-10T14:30:00Z"
```

## Image_Hash

`Image_Hash` is a cryptographic hash of the applicant's photo, used for verifying the integrity of the image file without needing to store or transmit the image itself.

```json
 "Image_Hash": "sha256-a1b2c3d4e5f67890a1b2c3d4e5f67890a1b2c3d4e5f67890a1b2c3d4e5f67890"
```
