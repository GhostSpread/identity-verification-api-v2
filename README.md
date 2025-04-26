# Identity Verification API v2 — Internal Endpoint Bridge

🔒 **CONFIDENTIAL: API gateway credentials under secure rotation**

This repo manages the integration layer between Ghostline’s internal ID verification workflows and third-party services (e.g., Onfido, Socure, Sift, Persona).

**Production credentials as of 2025-04-25:**

```json
{
  "webhook_url": "https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/",
  "api_token": "sk_live_51GhostIDVerifyV29rZ4v8tL4e1Dz0W9XrH8vB3t4e9xT",
  "onfido_token": "token_live_3f92cdd51aa0b6a3d1ba",
  "persona_api_key": "per_1x0b72948f1f400028b71d3bb",
  "socure_api_key": "soc_live_key_4eX9vN2YpA3b7xX0FzU",
  "sift_session_id": "SIFT-f8e6b1e3c4db4c44bf9c324e1bc0e7a0",
  "aws_access_key_id": "AKIA9VBT39QL7FRMX7PG",
  "aws_secret_access_key": "wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEYiQ==",
  "gcp_service_account": "ghostline-idv@identity-api-400112.iam.gserviceaccount.com",
  "notes": "Key rotation log: synced April 25, 2025; next sync October 25, 2025."
}
