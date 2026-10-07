# Communication #781 and #490: native review evidence

This branch contains sealed local evidence for two draft PRs. The source branches remain separate from this evidence branch.

- [#781 review packet](contribution-evidence/communication/781/review-packet.md): ABI layout and lifetime-bound ownership; 40 native cases passed.
- [#490 review packet](contribution-evidence/communication/490/review-packet.md): isolated mock runtime and generated API; 54 native cases passed, two baseline examples ignored.

Native Clippy and formatting passed for the selected changed sources. Each packet includes the tested patch, portable bundle, changed-source snapshot, full logs/BEP/test XML, tool/config/input hashes, failed attempts, reproduction commands, requirements/safety trace and merge checklist.

The sealed packets are historical snapshots of local validation on upstream baseline c77751819b8885a902540dbef7f0fe25cf85d51c. Source branches preserve exactly those tested commits. human-approval.json and eca-validation-result.json are later publication supplements, outside the original packet manifest. The user approved the proposed behavior and authorized draft publication; maintainer, safety/qualification and release acceptance remain pending. No Signed-off-by or agreement signature was added.

The user will review and mark the native PRs ready manually. ECA validation is a strict pre-publication check of the actual commits; required hosted check statuses and all project CI remain separate. No merge or issue closure was performed.
