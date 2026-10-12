# Publication preparation

The repository keeps its existing visibility during preparation.

- Preserve template/library licenses and credits.
- Use environment variables or ignored local configuration for credentials.
- Keep generated dependencies, personal uploads, and operational database backups outside source control.
- Review Git history before changing visibility; removing a credential from current files does not remove old commits. Replace any still-valid exposed credential.
- Demonstrate using synthetic data and describe the verified scope in docs/RUNTIME.md.

Specific scope: This repository owns the standalone company site at https://mrrobotdude.github.io/ats-company-website/; historical ATS variants remain separate.
