# Vulnerable Go Dependency

Dummy app that depends on `github.com/hashicorp/vault` version `v1.2.0` which has CVEs, including:


- Authentication Bypass by Spoofing and Insufficient Verification of Data Authenticity in Hashicorp Vault (9.8 CRITICAL·GHSA-fp52-qw33-mfmw)
- Incorrect Permission Assignment for Critical Resource in HashiCorp Vault
(9.1 CRITICAL·GHSA-pfmw-vj74-ph8g)
- Improper Resource Shutdown or Release in HashiCorp Vault
(7.5 HIGH·GHSA-9vh5-r4qw-v3vv)

See https://deps.dev/go/github.com%2Fhashicorp%2Fvault/v1.2.0 for details.