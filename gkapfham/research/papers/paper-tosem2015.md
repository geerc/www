---
id: -47
title: The Effectiveness of Test Coverage Criteria for Relational Database Schema Integrity Constraints
layout: researchpaper_n
categories: [research, paper, journal, database, testing]
authors: Phil McMinn, Chris J. Wright, and Gregory M. Kapfhammer
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/tosem2015-mcminn-wright-kapfhammer.pdf "Download this Paper!")

### {{ page.authors }}

### <em>Transactions on Software Engineering and Methodology</em>, 25(1), November 2015

### Abstract

Despite industry advice to the contrary, there has been little work that has sought to test that a relational database’s
schema has correctly specified integrity constraints. These critically important constraints ensure the coherence of
data in a database, defending it from manipulations that could violate requirements such as “usernames must be unique”
or “the host name cannot be missing or unknown.” This article is the first to propose coverage criteria, derived from
logic coverage criteria, that establish different levels of testing for the formulation of integrity constraints in a
database schema.  These range from simple criteria that mandate the testing of successful and unsuccessful INSERT
statements into tables to more advanced criteria that test the formulation of complex integrity constraints such as
multi-column PRIMARY KEYs and arbitrary CHECK constraints. Due to different vendor interpretations of the structured
query language (SQL) specification with regard to how integrity constraints should actually function in practice, our
criteria crucially account for the underlying semantics of the database management system (DBMS). After formally
defining these coverage criteria and relating them in a subsumption hierarchy, we present two approaches for
automatically generating tests that satisfy the criteria. We then describe the results of an empirical study that uses
mutation analysis to investigate the fault-finding capability of data generated when our coverage criteria are applied
to a wide variety of relational schemas hosted by three well-known and representative DBMSs &mdash; HyperSQL, PostgreSQL, and
SQLite. In addition to revealing the complementary fault-finding capabilities of the presented criteria, the results
show that mutation scores range from as low as just 12% of mutants being killed with the simplest of criteria to 96%
with the most advanced.
