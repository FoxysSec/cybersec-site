# CyberFoxys Privacy & Publication Policy

## Purpose
CyberFoxys is a public educational project and technical portfolio. Content may be public, but the author's personal life, identity, infrastructure, and private credentials are not part of the project.

## Never publish
- Real passwords or password managers exports
- API keys, tokens, private keys, certificates with private material, or secrets
- Session cookies, authentication tokens, or production credentials
- Personal email, phone number, address, exact location, or government documents
- Residential/public IP addresses or internal network details when they are unnecessary
- MAC addresses, Wi-Fi SSIDs, router configuration, or device identifiers
- Private hostnames, usernames tied to real identity, or account recovery data
- Screenshots containing personal data, notifications, browser profiles, tabs, or metadata
- Third-party personal or confidential data

## Safe replacements for labs
Use fictional or documentation-safe values:
- User: `student`
- Password: `lab-password`
- Email: `user@example.invalid`
- Local host: `127.0.0.1`
- Documentation host: `example.local`
- Sensitive value: `[REDACTED]`

## Publication workflow
1. Finish the lab locally.
2. Test the expected behavior.
3. Review code, terminal output, screenshots, and documentation for sensitive information.
4. Replace unnecessary identifiers with safe fictional values.
5. Check for secrets, tokens, keys, cookies, IP addresses, and personal data.
6. Review repository history when a sensitive value may have been committed previously.
7. Publish only the minimum information needed to teach the concept.

## Identity separation
The public identity used for the project is CyberFoxys/FoxysSec. Publishing educational content does not require disclosing the author's full name, home address, exact location, personal phone number, or private routine.

## Incident response
If sensitive information is published by mistake:
1. Remove public exposure as quickly as practical.
2. Revoke or rotate any exposed credential.
3. Treat copied secrets as compromised.
4. Remove the value from repository history when applicable.
5. Review related systems and logs.
6. Document the remediation without republishing the secret.

## Rule
If a value is not necessary to teach the lesson, it should not be published.
