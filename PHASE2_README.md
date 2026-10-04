# Safe AI Assistant — Phase 2

This package adds a security-first backend command gateway.

## Run backend
1. Install Node.js.
2. Open `backend/`.
3. Run `npm install`.
4. Run `npm start`.
5. Test `GET /health` and `POST /command`.

The Android client is still intentionally conservative. The next integration
step is to replace its local command switch with a call to this gateway and
then add individual Android action modules.

IMPORTANT: No banking, payment, OTP, PIN/password, SIM/eSIM, factory-reset or
security-setting automation is implemented.
