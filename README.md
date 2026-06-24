# 🔐 CyberSec

> CTF writeups, wargame solutions, and security research — by Savan

---

## Contents

| Category | Description |
|---|---|
| [Practice](#Practice) | OverTheWire, PicoCTF, etc. |
| [CTF Writeups](#ctf-writeups) | Competition writeups by event |
| [Tools & Scripts](#tools--scripts) | One-off scripts built during challenges |
| [Notes](#notes) | Concept references — JWT, web exploits, crypto, binary |

---

## Wargames

### OverTheWire
| Practice | Progress | Writeup |
|---|---|---|
| [Bandit](./Practice/Bandit-OTW/) | ✅ 33/33 | [View](./Practice/Bandit-OTW//README.md) |
| Natas | 🔄 In progress | — |
| Leviathan | — | — |

---

## CTF Writeups

Organized by event. Each folder contains per-challenge writeups with approach, payloads, and flag.

```
ctf/
├── ExampleCTF-2026/
│   ├── web/
│   ├── pwn/
│   └── misc/
└── ...
```

| Event | Year | Challenges Solved |
|---|---|---|
| boroCTF | 2026 | 🔄 In progress |

---

## Tools & Scripts

Small scripts written during challenges.

```
tools/
├── bruteforce_pin.sh       # nc-based PIN brute forcer (Bandit 24)
├── xforward_bypass.py      # X-Forwarded-For header spoof
└── ...
```

---

## Notes

Quick references built while studying.

```
notes/
├── jwt-attacks.md
├── web-exploits.md
├── merkle-tree-vulns.md
└── binary-exploitation.md
```

---

## Setup

Most challenges run on a standard Kali/Ubuntu environment. Common tools used:

```bash
nmap  netcat  openssl  gdb  pwntools  john  binwalk  zsteg  strings  xxd
```

---

## Structure

```
CyberSec/
├── wargames/
├── ctf/
├── tools/
├── notes/
└── README.md
```

---

*IIT Guwahati · Sqv1nx*
