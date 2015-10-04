---
layout: doc
title: Case
model: case
---

# Case

A case is a way to track transactions with a citizen.


## Use cases and requirements

The Case model should have properties for:

**subject**

> Describe what the case is about.

**date created**

> When the case was opened.

**status**

> Current status of the case.


## Types

This maps to the Smart Cities Concept Model [Case type](http://www.legsb.gov.uk/smartcityconceptmodel/index.php?Action=ShowConcept&Id=172).

### Sub-types

Just as Action and other common types have a number of sub-types, here are specific Service request sub-types for different kinds of services councils provide:

* AdditionalBinRequest
* AssistedCollectionRequest
* BulkyCollection
* ChargeableBulkyCollection
* ClinicalOneTimeCollection
* ClinicalCollection
* ReportDamage
* DeadAnimal
* EmergencyCollection
* FreezerCollection (why not bulky?)
* NewCollection
* 



## Properties

Term     | Mapping | Definition
---------|---------|-----------
subject | [schema:name](http://schema.org/name) | Subject of the case.


## Serialisation

{% include serialisation.html %}



