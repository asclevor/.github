# Asclevor Technologies

Developer-first infrastructure for accessing and working with medical knowledge.

Asclevor builds modern APIs and structured-data tools that make complex medical
knowledge more accessible to developers, researchers, physicians, and anyone
else working with medical information.

## What we're building

Our first product focuses on **semantic retrieval of clinically similar
published patient cases**. Finding published cases that resemble a particular
patient presentation traditionally means manually searching large volumes of
medical literature with keyword-based tools. Asclevor's goal is to make that
discovery faster and more accessible.

### How it works

1. Receive a query describing a patient case or clinical scenario
2. Generate a semantic embedding for the query
3. Perform similarity search against a database of embedded patient cases
4. Return the most similar cases, including similarity scores and
   PubMed identifiers (PMIDs)

### Current status

- ✅ 167,000+ patient cases sourced from PubMed data, processed and embedded
  with `BAAI/bge-small-en-v1.5`
- ✅ Semantic similarity search working locally
- ✅ Database deployed (~40,000 cases currently indexed)
- 🚧 Public API — in development

Asclevor is currently a solo, bootstrapped project raising a small pre-seed
round to formally establish the company and grow the team.

## Who it's for

- **Developers** building medical or healthcare applications that need access
  to relevant medical knowledge — for example, retrieving published cases
  similar to a patient's clinical presentation.
- **Researchers** identifying similar published cases for literature review or
  investigation of specific clinical presentations.
- **Physicians and medical professionals** exploring clinically similar
  published cases and the associated literature through tools built on
  Asclevor's retrieval technology.

## Our approach

Many existing medical data sources are difficult to integrate into modern
applications. Asclevor aims to change that with:

- Modern, developer-friendly APIs
- Structured, accessible responses
- A focus on JSON-based developer experiences
- Easy integration into modern software applications

**Strategy:** solve one narrow problem exceptionally well — semantic retrieval
of clinically similar patient cases — and use that foundation to expand into a
broader medical knowledge API platform.

## Important

Asclevor's tools retrieve and surface information. They do **not** diagnose
patients, determine treatments, or replace clinical judgment.

---

*This repository hosts organization-wide profile information for Asclevor on GitHub.*
