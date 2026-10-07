# Communication draft PR review evidence

This is a bounded public export of the locally retained contribution packet.
It binds the native change to commit `fb634728809bae2cacf485c9edab891a1ab20321`, based on
`cef680454e8586daca9f953084dca33fb3759d0c`, on branch `fix/communication-lint-aou-codeql-followup` in
[jnsagai/communication](https://github.com/jnsagai/communication/tree/fb634728809bae2cacf485c9edab891a1ab20321).
The original complete packet is 241 MB and remains retained locally. The original
packet manifest records the hashes of omitted source/database archives, historical
attempts, native policies and full raw evidence. This export includes the proposed
patches, final summaries, selected complete command records/logs, final SARIF and
strict Eclipse ECA validation for the actual commit. No analyzer database or tool
bundle is redistributed here.

- [Measured verification](verification.md)
- [Native reproduction commands](reproduce.md)
- [Required checks and omissions](required-checks.json)
- [Communication PR description](pr-communication.md)
- [Config Management companion proposal](pr-config-management.md)
- [Deferred #1031 integration decisions](1031-production-integration-disposition.json)
- [License audit](license-header-audit.json)
- [Actual-commit ECA result](publication/eca-validation-result.json)
- [Final SARIF](evidence/license-final-native-reporting/communication.sarif)

The summaries record the measurement checkpoint before PR publication. The
Communication PR is a draft for Jefferson Nascimento's review. Config Management
is a local companion proposal, with safety decisions deferred and #1031 open.
Upstream main was `251ea495e25852d357e589cee95cc8c54d141633` at publication preparation.
A temporary merge was clean; tests/analyzer results apply to the original verified
head rather than an untested merge tree. Native CI and reviews remain pending.
The licensing cleanup overlaps upstream PR #1341 and needs coordination before
merge. Successful analyzer execution leaves 2,127 findings for native disposition.

Run `python3 verify_packet.py` to check every exported artifact's hash and size.
`artifact-manifest.json` covers this export; `original-packet-manifest.json`
describes the larger retained packet and is not the export verifier input.
