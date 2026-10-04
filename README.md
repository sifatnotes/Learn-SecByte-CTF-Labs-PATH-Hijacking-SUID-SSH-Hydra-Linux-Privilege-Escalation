# Learn-SecByte-CTF-Labs-PATH-Hijacking-SUID-SSH-Hydra-Linux-Privilege-Escalation
Hands-on cybersecurity and CTF labs covering PATH hijacking, malicious executables, search-order weaknesses, environment variables, SUID, Linux file hunting, SSH access, credential reuse, and Hydra-based authentication testing.
# Learn SecByte CTF Labs: PATH Hijacking, SUID, SSH & Root

A focused collection of **hands-on cybersecurity labs** from Learn SecByte covering PATH hijacking, malicious executables, search-order weaknesses, environment variables, SUID, Linux file hunting, SSH access, credential reuse, and authentication testing.

These **CTF labs** are useful for cybersecurity students, CTF players, ethical hackers, penetration testers, SOC analysts, and Linux security learners developing practical privilege-escalation skills.

## Lab Collection

| #  | Lab                                                                                                   | Focus                      |
| -- | ----------------------------------------------------------------------------------------------------- | -------------------------- |
| 1  | [Path Sneak Escalation](https://learn.secbyte.org/ctf/path-sneak-escalation)                          | PATH-based escalation      |
| 2  | [Path Hijack: Malicious Executables](https://learn.secbyte.org/ctf/path-hijack-malicious-executables) | PATH hijacking             |
| 3  | [Path Hijack: Root by Search Order](https://learn.secbyte.org/ctf/path-hijack-root-by-search-order)   | Search-order weakness      |
| 4  | [Env Vars Root Access](https://learn.secbyte.org/ctf/env-vars-root-access)                            | Environment variables      |
| 5  | [Path Hijack: Root in the Shadows](https://learn.secbyte.org/ctf/path-hijack-root-in-the-shadows)     | PATH hijacking             |
| 6  | [SUID Sleight](https://learn.secbyte.org/ctf/suid-sleight)                                            | SUID security              |
| 7  | [SUID Sleuth: Path Hijack](https://learn.secbyte.org/ctf/suid-sleuth-path-hijack)                     | SUID + PATH hijacking      |
| 8  | [Pathfinder: Linux File Hunt](https://learn.secbyte.org/ctf/pathfinder-linux-file-hunt)               | Linux file discovery       |
| 9  | [Path of the Users](https://learn.secbyte.org/ctf/path-of-the-users)                                  | User/file investigation    |
| 10 | [SSH Doorway: From Web Leak to Root](https://learn.secbyte.org/ctf/ssh-doorway-from-web-leak-to-root) | Web-to-SSH-to-root chain   |
| 11 | [Reuse Chain](https://learn.secbyte.org/ctf/reuse-chain)                                              | Credential reuse           |
| 12 | [Hydra SSH Break-In](https://learn.secbyte.org/ctf/hydra-ssh-break-in)                                | SSH authentication testing |

> Difficulty levels and CVE identifiers are not specified in the supplied URLs, so they are not inferred.

## Categories

### PATH Hijacking & Search-Order Security

These labs focus on PATH manipulation and executable search-order weaknesses:

* [Path Sneak Escalation](https://learn.secbyte.org/ctf/path-sneak-escalation)
* [Path Hijack: Malicious Executables](https://learn.secbyte.org/ctf/path-hijack-malicious-executables)
* [Path Hijack: Root by Search Order](https://learn.secbyte.org/ctf/path-hijack-root-by-search-order)
* [Path Hijack: Root in the Shadows](https://learn.secbyte.org/ctf/path-hijack-root-in-the-shadows)

PATH hijacking occurs when software relies on an unsafe executable search path, potentially allowing an unintended program to be executed.

### Environment Variables

* [Env Vars Root Access](https://learn.secbyte.org/ctf/env-vars-root-access)

This lab focuses on environment-variable concepts in the context of elevated access.

### SUID & Linux Privilege Escalation

* [SUID Sleight](https://learn.secbyte.org/ctf/suid-sleight)
* [SUID Sleuth: Path Hijack](https://learn.secbyte.org/ctf/suid-sleuth-path-hijack)

These challenges combine Linux SUID concepts with privilege-escalation analysis.

### Linux File & User Investigation

* [Pathfinder: Linux File Hunt](https://learn.secbyte.org/ctf/pathfinder-linux-file-hunt)
* [Path of the Users](https://learn.secbyte.org/ctf/path-of-the-users)

These labs emphasize filesystem and user-related discovery.

### SSH & Credential Security

* [SSH Doorway: From Web Leak to Root](https://learn.secbyte.org/ctf/ssh-doorway-from-web-leak-to-root)
* [Reuse Chain](https://learn.secbyte.org/ctf/reuse-chain)
* [Hydra SSH Break-In](https://learn.secbyte.org/ctf/hydra-ssh-break-in)

These challenges cover SSH access, credential reuse, and authentication-testing concepts within authorized lab environments.

## Learning Path

A practical progression through this **CTF lab collection**:

1. Start with **Pathfinder: Linux File Hunt** to develop Linux discovery skills.
2. Study **Path Sneak Escalation** and the PATH hijacking challenges.
3. Explore search-order and environment-variable security.
4. Continue with **SUID Sleight** and **SUID Sleuth: Path Hijack**.
5. Study credential reuse and SSH security.
6. Finish with the web-leak-to-root and SSH authentication-testing challenges.

## Skills Covered

* Linux filesystem enumeration
* User discovery
* PATH manipulation awareness
* Executable search-order security
* Environment-variable security
* SUID analysis
* Linux privilege escalation
* SSH security
* Credential-reuse awareness
* Web-to-SSH attack-chain analysis
* Authentication testing concepts
* CTF methodology

## How to Use the Labs

Use these labs only in authorized environments such as CTF platforms, personal virtual machines, or intentionally vulnerable training systems.

For each challenge:

1. Read the objective and confirm the lab scope.
2. Identify relevant files, users, services, and permissions.
3. Perform authorized enumeration.
4. Analyze PATH, SUID, environment, SSH, or credential-related weaknesses as appropriate.
5. Document the discovered security issue and its impact.
6. Consider defensive controls that would prevent the weakness.
7. Record lessons learned for future CTF and penetration-testing exercises.

Never use these techniques against systems without explicit authorization.

## Intended Audience

This repository is useful for:

* Cybersecurity students
* CTF players
* Ethical hacking learners
* Penetration testers
* Linux security practitioners
* SOC analysts
* Security researchers

## Disclaimer

These **cybersecurity labs and CTF labs** are intended for authorized educational security training. The repository does not provide leaked credentials or endorse unauthorized access. Always follow applicable laws, platform rules, and the defined scope of any security assessment.
