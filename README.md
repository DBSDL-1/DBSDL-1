## 📚 Digital Library Repository

-<!--
**DBSDL-1_(Dawuro Boarding School Digital Library)** 



Grades 9–12 | School-Based LAN Digital Library

📖 Overview

This repository supports a school digital library system designed for high school students (Grades 9–12).
The library provides offline access via a local server and LAN to curated educational resources including:

📘 Books & PDFs

🌐 Free educational websites (curated links)

🎥 Video lectures

📄 Academic documentation (notes, syllabi, past exams)

The system is optimized for 40+ client computers and managed using a Library Management System (Koha / Calibre).

🎯 Objectives

Improve equitable access to quality educational resources

Support curriculum-aligned learning for Grades 9–12

Provide a safe, offline, and distraction-free learning environment

Enable librarians and teachers to curate and manage content efficiently

🧑‍🎓 Target Users

Students: Grades 9–12 (read-only access)

Teachers: Resource recommendation & guidance

Librarians/Admins: Content management and system administration

🗂 Repository Structure
DigitalLibrary/
│
├── Grade_09/
│   ├── Mathematics/
│   │   ├── Books/
│   │   ├── Videos/
│   │   ├── Websites/
│   │   └── Documents/
│   ├── Biology/
│   ├── Chemistry/
│   └── ...
│
├── Grade_10/
├── Grade_11/
├── Grade_12/
│
├── Shared_Resources/
│   ├── Dictionaries/
│   ├── Encyclopedias/
│   ├── Study_Skills/
│   └── Career_Guidance/
│
└── README.md

📚 Resource Types

Each subject folder contains four standardized resource types:

Books – PDFs / EPUBs (open-access or public domain)

Videos – Downloaded lectures or curated offline playlists

Websites – Text files or documents containing approved links

Documents – Notes, syllabi, worksheets, and past exams

🧾 Metadata & Cataloging

All resources must be cataloged in the Library Management System using the following minimum metadata fields:

Title

Author / Creator

Grade

Subject

Resource Type

Format (PDF, MP4, Link, DOC)

Language

Source

Access Level

⚠️ Resources without proper metadata should not be added to the library.

🖥 System Architecture

Server: Central file server (Linux or Windows)

Access: Local Area Network (LAN)

Clients: 40+ computers

Management: Koha / Calibre

Access Mode: Offline (local IP-based access)

🔐 Access Control
Role	Permissions
Admin	Full system control
Librarian	Upload, organize, catalog
Teacher	Recommend resources
Student	View & read only

All student-access folders are read-only.

🛡 Content Policy

This library includes only legal and ethical resources:

Open-access materials

Public domain books

Creative Commons resources

Official educational platforms

❌ No pirated or copyrighted materials without permission.

🔄 Maintenance & Backup

Daily local backup

Weekly external backup

Monthly archive snapshot

Regular integrity checks

🚀 Getting Started

Set up the server and shared folders

Install and configure Koha / Calibre

Populate folders according to structure

Add metadata records in the LMS

Test access from client computers

📌 Notes for Librarians

Always verify grade and subject alignment

Prefer curriculum-approved materials

Keep folder naming consistent

Review resources annually for relevance

📞 Support & Administration

For technical support, contact the system administrator or library ICT coordinator.

This digital library is designed to be scalable, safe, and sustainable—supporting student learning today and for years to come.
