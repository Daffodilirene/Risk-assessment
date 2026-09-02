
# EXPERIMENT 5
## NAME  : DAFFODIL IRENE S
## REGNO : 212225100006

## ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS 


## Aim

To identify storage assets in **AWS S3**.


## Software / Cloud Services Required

- AWS Account
- Microsoft Azure Account
- Web Browser
- Internet Connection

### Cloud Services Used

| Cloud Platform | Storage Service |
|---|---|
| AWS | Amazon S3 |


## AWS S3 STORAGE ASSESSMENT

## Step 1: Login to AWS

1. Open the AWS Management Console.
2. Sign in using your AWS account.
3. Search for **S3**.
4. Select **Amazon S3**.


## Step 2: Select the S3 Bucket

1. Click **Buckets**.
2. Select the S3 bucket created in the previous experiment.
3. Record:
   - Bucket name
   - AWS Region
   - Number/type of objects

<img width="1917" height="895" alt="image" src="https://github.com/user-attachments/assets/a88ed89b-dc50-4f8b-ae0d-4d3c1200b6e5" />





## Step 3: Check Block Public Access

1. Open the S3 bucket.
2. Select **Permissions**.
3. Locate **Block public access (bucket settings)**.
4. Check **Block all public access**.

### Record

- **ON** → Secure configuration
- **OFF** → Potential public-access risk
<img width="1916" height="892" alt="image" src="https://github.com/user-attachments/assets/9c55d542-54cd-40b4-a2fb-5011fd557c31" />







## Step 4: Check Bucket Versioning

1. Select the **Properties** tab.
2. Locate **Bucket Versioning**.
3. Record whether it is:
   - Enabled
   - Disabled

### Security Purpose

Versioning helps recover previous versions of objects after accidental deletion or modification.


<img width="1917" height="891" alt="image" src="https://github.com/user-attachments/assets/940dde72-1cbe-41bb-a816-de576714fff4" />




## Step 5: Check Default Encryption

1. Stay in the **Properties** tab.
2. Locate **Default encryption**.
3. Record the encryption type.

### Possible Configurations

- SSE-S3
- SSE-KMS
- DSSE-KMS

### Security Purpose

Encryption protects stored data from unauthorized disclosure.

<img width="1917" height="881" alt="image" src="https://github.com/user-attachments/assets/d5abd79b-2c72-4b0f-9c49-03a2a118bd72" />


## Step 6: Check Bucket Policy

1. Select **Permissions**.
2. Locate **Bucket policy**.
3. Check whether a bucket policy exists.

### Record

- Policy exists
- No policy

> **Note:** A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.

<img width="1912" height="882" alt="image" src="https://github.com/user-attachments/assets/44af365c-d300-4714-a029-aa1c4f5e0dbc" />


## Step 7: Check Object Ownership and ACL

1. In **Permissions**, locate **Object Ownership**.
2. Record the current configuration.

A common secure configuration is:

**Bucket owner enforced**

This means:

- ACLs are disabled.
- Objects are owned by the bucket owner.
- Access is controlled using policies.

<img width="1917" height="882" alt="image" src="https://github.com/user-attachments/assets/8a5c06fe-0752-4dbf-afbf-93fbf014bd03" />


## Step 8: Check Server Access Logging

1. Go to **Properties**.
2. Locate **Server access logging**.
3. Record whether it is:
   - Enabled
   - Disabled

### Security Purpose

Logging helps investigate suspicious or unauthorized access to the bucket.


<img width="1917" height="885" alt="Screenshot 2026-09-02 140501" src="https://github.com/user-attachments/assets/a1c2ef99-9098-4da4-bb8f-198b63053a64" />




## Result

AWS S3 security configurations were analyzed and potential risks were identified.



