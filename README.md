# KDX-verify

| Build                 | Latest Version         |
| :-------------------- | :--------------------- |
| `Full release`        |          NOT Available |
| `BETA`                |          NOT Available |
| `Developer Preview`   |          0.4.0.2       | 

| Platform                    | Status                 |
| :-------------------------- | :--------------------- |
| `Linux (x86_64) (DEBIAN)`   |              Available |
| `Linux (ARM64) (DEBIAN)`    |          NOT Available |
| `Linux (x86_64) (ARCH)`     |          NOT Available |
| `Linux (ARM64) (ARCH)`      |          NOT Available | 

## Introduction

KDX-Verify is an open-source kernel-level security module that enforces strict whitelist-based control over privileged operations (sudo/root/pkexec). It blocks unauthorized root execution by verifying absolute binary paths against a user-defined whitelist (whitelist.conf), granting freedom to permit trusted paths while denying all others by default.

#### DISCLAIMER

> THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED. THE AUTHORS BEAR NO LIABILITY FOR DAMAGES OR SYSTEM INSTABILITY RESULTING FROM ITS USE. IT'S ALSO FREELY DISTRIBUTABLE UNDER GNU GENERAL PUBLIC LICENSE V3.0.
