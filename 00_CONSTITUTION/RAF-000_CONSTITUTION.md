# RAF-000

# ROS AI Framework Constitution

---

Status

Approved

Version

1.0.0

Authority

ROS AI Framework

---

# Preamble

ROS AI Framework diwujudkan untuk membangunkan sistem Artificial Intelligence yang modular, boleh diselenggara, mudah dikembangkan dan bebas daripada pergantungan kepada mana-mana Large Language Model (LLM).

Framework ini dibina berdasarkan prinsip seni bina perisian moden, pemisahan tanggungjawab (Separation of Concerns) dan reka bentuk modular.

Dokumen ini merupakan perlembagaan rasmi ROS AI Framework.

Semua spesifikasi, kod, engine, workflow dan domain hendaklah mematuhi Constitution ini.

---

# Article 1

## Framework First

Framework sentiasa didahulukan.

LLM hanyalah execution engine.

Framework ialah intelligence.

---

# Article 2

## LLM Agnostic

Framework tidak boleh bergantung kepada:

- Claude

- ChatGPT

- Gemini

- DeepSeek

- Llama

atau mana-mana model tertentu.

Semua LLM dianggap sebagai Adapter Layer.

---

# Article 3

## Domain Agnostic

Framework tidak mengetahui domain.

Semua domain hendaklah dibangunkan sebagai Domain Pack yang berasingan.

---

# Article 4

## Separation of Concerns

Setiap layer mempunyai satu tanggungjawab.

Core

↓

Domain

↓

Rules

↓

Engine

↓

Workflow

↓

Template

↓

Output

Tiada layer dibenarkan mengambil tanggungjawab layer lain.

---

# Article 5

## Single Responsibility

Satu fail.

Satu tanggungjawab.

---

# Article 6

## Human Readable

Semua fail mesti:

- mudah dibaca

- mudah difahami

- mudah diaudit

- mudah diubah

---

# Article 7

## Open Architecture

Framework direka supaya:

- Engine boleh diganti.

- Rules boleh ditambah.

- Domain boleh dipasang.

- Workflow boleh diperluaskan.

tanpa mengubah Core.

---

# Article 8

## Knowledge Before Decision

Framework tidak boleh membuat keputusan tanpa Knowledge dan Rules.

---

# Article 9

## Rules Before Execution

Semua Engine mesti merujuk Rules sebelum melaksanakan tindakan.

---

# Article 10

## Documentation Is Code

Specification mempunyai nilai yang sama penting seperti kod.

Sekiranya berlaku percanggahan:

Constitution

↓

Specification

↓

Implementation

Implementation mesti mematuhi Specification.

Specification mesti mematuhi Constitution.

---

# Final Declaration

ROS AI Framework dibangunkan sebagai sebuah AI Framework profesional yang mengutamakan seni bina, modulariti, ketepatan dan kebolehselenggaraan.

Semua pembangunan masa hadapan hendaklah mematuhi Constitution ini.

---

# End of Constitution