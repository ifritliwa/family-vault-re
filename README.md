# Family Vault RE

Live website: https://ifritliwa.github.io/family-vault-re/

This repository contains the reviewed public browser build of Family Vault v2. Authentication, data access, verification and private credentials remain in the Supabase backend.

Initial setup requires verified email, PIN/passkey, messaging OTP, authenticator activation and camera liveness. Returning accounts can use an existing passkey or email/password followed by the vault PIN. Security changes require fresh authenticator verification; removing 2FA requires a human developer review.

The original source project is maintained separately. Developer permissions and protected data access are enforced by the server.
