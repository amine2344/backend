# Verify OTP function

Function to verify OTPs.

## 🧰 Usage

### POST /

**Parameters**

| Name           | Description               | Location | Type   | Sample Value       |
| -------------- | ------------------------- | -------- | ------ | ------------------ |
| otpId          | Document ID of the otp    | Body     | String | `jcbd...kdsn`      |
| userOTP | otp sent by user | Body     | String | `123456` |
| verify_ID | Document ID of the otp | Body     | String | `jcbd...kdsn` |

## ⚙️ Configuration

| Setting           | Value                          |
| ----------------- | ------------------------------ |
| Runtime           | Node (18.0)                    |
| Entrypoint        | `src/main.js`                  |
| Build Commands    | `npm install && npm run start` |
| Permissions       | `Users`                          |
| Timeout (Seconds) | 15                             |

## 🔒 Environment Variables

### APPWRITE_API_KEY

API Key to use Appwrite Sever SDK.

| Question      | Answer                                                                   |
| ------------- | ------------------------------------------------------------------------ |
| Required      | Yes                                                                      |
| Sample Value  | `62...97`                                                                |
| Documentation | [Appwrite API Keys](https://appwrite.io/docs/advanced/platform/api-keys) |

### VERIFICATION_DATABASE_ID

Database ID of verification database in appwrite.

| Question      | Answer                                                                                  |
| ------------- | --------------------------------------------------------------------------------------- |
| Required      | Yes                                                                                     |
| Sample Value  | `Zjc...5PH`                                                                             |
| Documentation | [Resonate](https://github.com/AOSSIE-Org/Resonate/blob/master/lib/utils/constants.dart) |

### OTP_COLLECTION_ID

Collection ID of otp collection.

| Question      | Answer                                                                                  |
| ------------- | --------------------------------------------------------------------------------------- |
| Required      | Yes                                                                                     |
| Sample Value  | `NXOi3...IBHDa`                                                                         |
| Documentation | [Resonate](https://github.com/AOSSIE-Org/Resonate/blob/master/lib/utils/constants.dart) |

### VERIFY_COLLECTION_ID

Collection ID of verify collection.

| Question      | Answer                                                                                  |
| ------------- | --------------------------------------------------------------------------------------- |
| Required      | Yes                                                                                     |
| Sample Value  | `NXOi3...IBHDa`                                                                         |
| Documentation | [Resonate](https://github.com/AOSSIE-Org/Resonate/blob/master/lib/utils/constants.dart) |