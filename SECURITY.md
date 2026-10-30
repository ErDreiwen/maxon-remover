# Security policy

Supported development line: 0.1.x preview.

Report unsafe path traversal, exclusion bypasses, selection/command injection or unintended deletion privately using GitHub's private vulnerability reporting if the repository has enabled it. If unavailable, open a minimal issue asking for a private contact, without exploit details or personal logs.

Public downloads require valid code signatures. Unsigned development builds stay in draft. Obtain releases from [this project's releases](https://github.com/ErDreiwen/maxon-remover/releases) and compare the download's SHA-256 with the release checksum. Never disable operating-system protections or antivirus to bypass an alert.

The application does not download executable code, phone home, collect account data or upload logs. Vendor uninstallers and Windows certificate validation are external components with their own behavior. Local reports may contain sensitive filesystem paths; redact them before sharing.
