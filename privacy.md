# Privacy policy

Last updated: 21 October 2026

This personal application accesses the owner's authorized university Gmail account using Gmail read-only permission. It reads message identifiers, timestamps, headers, email text and HTML to identify competition and prize messages. Relevant original excerpts, subject, sender, timestamps and participation links are sent to the owner's configured private Telegram bot chat.

Processing runs on GitHub Actions. OAuth credentials and delivery state, including pending alert text and metadata, are stored encrypted in a private GitHub repository. The encryption key and Telegram configuration are stored in GitHub Actions Secrets. Decrypted data exists on the runner during execution. A local Windows copy may also retain credentials and the delivery database. Telegram retains sent alerts according to its service settings and policies. Git history and backups may retain older encrypted snapshots.

Message text and credentials are not intentionally printed in operational logs. Logs can contain scan times, counts and error categories. Gmail data is not sold, used for advertising, provided to AI models, or used to train models. Access, use and transfer of Google user data follow the Google API Services User Data Policy, including its Limited Use requirements.

Access can be revoked through the owner's Google Account third-party access settings. The owner can stop the workflow and remove local files, repository data, secrets, retained history and Telegram alerts. Revocation prevents further access but does not automatically delete stored data. Repository copies and provider backups may remain subject to provider retention policies.

This application is for its owner's personal use only. It does not offer accounts to the public. Maintainer: https://github.com/CYJienn
