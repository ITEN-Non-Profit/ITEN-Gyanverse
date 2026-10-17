<div align="center">

# IT Education Nepal Learning Content

### कम्प्युटर शिक्षा सबैका लागि
*Computer education for all*

**From Class 1 to an IT career, one free and open library of learning material.**

</div>

## About ITEN

**IT Education Nepal (ITEN)** is a volunteer-driven, nonprofit initiative that provides practical computer education to Nepali speakers worldwide. It was founded on the principle that technology literacy is a universal right and works to remove geographic, language, and financial barriers that keep many learners out of IT education.

Many learners finish formal study with strong theory but little practice in the skills the job actually requires. ITEN exists to close that gap.

## About this repository

This repository holds the source content behind ITEN's learning platforms. Every topic keeps its original study material next to a Markdown version that is ready to publish on the ITEN websites.

The folders for every level below are ready, and content is being added one topic at a time.

## What's inside

| Level | Directory | Scope | Topics |
| ----- | --------- | ----- | -----: |
| School | [`school/`](school) | Class 1 to 10, Nepal school curriculum | 56 subjects |
| NEB | [`neb/`](neb) | Class 11 and 12 in Science, Management, Humanities and Education | 36 subjects |
| CTEVT | [`ctevt/`](ctevt) | Diploma Year 1 to 3 in six engineering and health programmes | 108 subjects |
| Bachelor | [`bachelor/`](bachelor) | University level IT content | *Coming soon* |
| Professional IT Career | [`professional-it-career/`](professional-it-career) | Industry skills, certifications and interview preparation | 38 topics |
| Parent | [`parent/`](parent) | Guidance for parents and guardians | *Coming soon* |

## Upcoming content

### School, Class 1 to 10

| Classes | Subjects |
| ------- | -------- |
| 1 to 3 | English, Nepali, Mathematics, Hamro Serofero |
| 4 to 8 | English, Nepali, Mathematics, Science, Social Studies, Health, Physical and Creative Arts |
| 9 and 10 | English, Nepali, Mathematics, Optional Mathematics, Science, Social Studies, Computer Science |

### NEB, Class 11 and 12

| Faculty | Subjects |
| ------- | -------- |
| Science | Physics, Chemistry, Biology, Mathematics, English |
| Management | Accountancy, Business Studies, Business Mathematics, Economics, English |
| Humanities | History, Political Science, Sociology, Economics, English |
| Education | Education, Health and Physical Education, English |

### CTEVT, Diploma Year 1 to 3

Six programmes, each with six subjects per year:

- Civil Engineering
- Computer Engineering
- Electrical Engineering
- Electronics Engineering
- Nursing
- Pharmacy

### Professional IT Career

| Domain | Tracks |
| ------ | ------ |
| Networking | Vendor neutral: CompTIA Network+<br>Vendors: Cisco, Juniper, MikroTik and Huawei, each with routing and switching plus firewall |
| Cloud and Infrastructure | Managed: AWS, Azure, GCP<br>Self hosted: OpenShift, Nutanix, OpenStack<br>Virtualization: VMware, Proxmox, KVM, Hyper-V<br>Containerization: Docker, Kubernetes, Podman |
| System Administration | Linux: Ubuntu, Kali Linux, Red Hat, Fedora<br>Windows<br>Monitoring: server side and client side |
| Programming | Frontend: HTML and CSS, JavaScript, React, Vue<br>Backend: PHP, Node.js, Python |
| Cybersecurity | Fundamentals |
| Artificial Intelligence | Fundamentals |

Every professional topic and domain also has its own **interview preparation** section.

## Repository structure

```
.
├── school/                       Class 1 to 10
│   └── class-<n>/<subject>/
├── neb/                          Class 11 and 12
│   └── class-<n>/<faculty>/<subject>/
├── ctevt/                        Diploma Year 1 to 3
│   └── year-<n>/<programme>/<subject>/
├── bachelor/                     Coming soon
├── professional-it-career/
│   ├── networking/
│   │   ├── vendor-neutral/<certification>/
│   │   └── vendor/<vendor>/<track>/
│   ├── cloud-and-infra/
│   │   └── <managed|self-hosted|virtualization|containerization>/<platform>/
│   ├── system-administration/
│   │   ├── linux/<debian-based|rpm-based>/<distribution>/
│   │   ├── monitoring/<server-side|client-side>/
│   │   └── windows/
│   ├── programming/
│   │   └── <frontend|backend>/<technology>/
│   ├── cybersecurity/
│   └── artificial-intelligence/
└── parent/                       Coming soon
```

### Inside every topic

Each subject or topic folder has the same layout:

```
<topic>/
├── README.md                Topic overview
├── original-files/          Source material such as PDF, DOCX, slides and notes
├── MD-conversion/           Markdown version of the source material
└── interview-preparation/   Professional IT career topics only
    ├── README.md
    ├── original-files/
    └── MD-conversion/
```

## Contributing content

1. Find the folder for your material, for example `neb/class-11/science/physics/`.
2. Put the source file in `original-files/`.
3. Put its Markdown version in `MD-conversion/` with the same base file name.
4. Write folder names in lowercase with words joined by hyphens, like `health-and-physical-education`.

A new subject or topic follows the same layout, with a `README.md`, an `original-files/` folder and an `MD-conversion/` folder.

<div align="center">

### संगै सिकौं, संगै बढौं!
**Let us learn and grow together.**

[iteducationnepal.org](https://iteducationnepal.org)

</div>

