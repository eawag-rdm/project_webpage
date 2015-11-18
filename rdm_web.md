
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
<link rel="stylesheet" href="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/themes/smoothness/jquery-ui.css">
<script src="https://ajax.googleapis.com/ajax/libs/jqueryui/1.11.4/jquery-ui.min.js"></script>


# Eawag Research Data Management Project

## Summary

<div id="accordion">

## Objectives

<div>

**1. Provide better support to the scientists to fulfill their data management duties.**

+ Provide a central research storage and archiving facility, including long-term maintenance and support.
+ Support departmental data managers and scientists in organizing, documenting, uploading and accessing data using this facility.

**2. Provide guidance for the robust, person-independent and standards-compliant handling of research data.**

**3. Exploit the collateral benefits of a central data-management platform**

</div>

## Guiding Principles

<div>
+ **For the scientists, data-management should be a well-defined, simple and quickly executed routine task.**
+ Ensure longevity and interoperability of the software by adhering to established standards.
+ Ensure the practicability of software and processes by continuous user-involvement at every stage.
+ Ensure compatibility with estabished meta-data standards.
+ Strive for collaboration with related inititives within the ETH domain and at other research institutions.
</div>

## Deliverables 

<div>

[[Eawag Research Data Platform]](#eawag-research-data-platform)   [[Metadata Schemes]](#metadata-schemes) [[RDM Guidelines]](#research-data-management-guidelines) [[Support Activities]](#support-activities)

### Eawag Research Data Platform (ERDP) [&#8593;](#deliverables)

The project will establish an institution-wide central research data
repository. The repository will be accessible to all Eawag research
groups to

1. store and maintain their own datasets, to
2. search the repository content, and
3. to retrieve datasets

The repository is based on the well-established open-source
datamanagement software [CKAN](http://ckan.org). While CKAN is being
used by many organizations around the world in an
["OpenData"](https://en.wikipedia.org/wiki/Open_data) context, its use
as a research data management tool requires the development of
custom-tailored extensions that adapt CKAN to the specific needs at
Eawag.

**Features of the ERDP will include:**

+ a batch upload facility
+ customized interfaces for data submission
+ spatial and temporal search across all datasets
+ search for other dataset attributes and global full-text search
+ preview for suitable datasets (as table, map, or graph)
+ ERDP will act as staging area for submitting datasets to other
repositories and for registering a Digital Object Identifier (DOI).

[A link to more technical information to be provided later on GitHub]

### Metadata Schemes [&#8593;](#deliverables)

Development of a metadata structure that is 

+ compatible with international standards, such as the [Dublin Core](https://de.wikipedia.org/wiki/Dublin_Core) conventions,
+ covers the requirements for all data stored at Eawag,
+ will be extended as needed, and
+ is compliant to the extent possible with common requirements of
  external services, such as [dataCite](https://www.datacite.org/),
  [PANGAEA](http://www.pangaea.de/), or [figshare](http://figshare.com).

### Research Data Management Guidelines [&#8593;](#deliverables)

The repository roll-out will be accompanied by the development of
data-management guidelines. These guidelines will be developed with
user-input in an interative fashion and compliance will be supported
by the actual software implementation. The content of the guidelines
presumably specifies the precise meta-data requirements, the types of
datasets that should be submitted to the repository, rules for
write-access to the repository and similar topics.

### Support activities [&#8593;](#deliverables)

Research groups will receive support to streamline their data
submission procedures. This includes case-by-case analysis of current
workflow and requirements, support with structuring, formatting,
annotation, uploading, searching and downloading, the provision of
software to automate such tasks, if applicable, and the cooperative
development of specific meta-data schemes.
</div>

## Background

<div>
The
[Eawag Guidelines for Good Scientific Practice](http://www.eawag.ch/fileadmin/Domain1/About/Arbeiten/Forschungsumfeld/integritaet_forschung.pdf)
assigns to a research project's PI the responsibility for data
management. In particular that includes ensuring the data's safe
(person-independent) storage and accessibility for a prolonged time
period, coming up with a suitable set of metadata and the respective
annotation of datasets, care against misuse of data by temporary or
external collaborators, and transfer of their own knowledge and data
if they leave Eawag.

In practice, secure storage and retrievability handled individually in
each workgroup is riddled with difficulties. Fluctuating scientific
staff, diverse storage locations, ad-hoc or missing meta-data schemes
are among the reasons for sub-optimal storage of often irreplaceable
and non-reproducible datasets that were produced at substantial cost.

In general, individually carried out proper mid- and long-term storage
and archival of research data requires an undue amount of effort,
time and know-how outside their respective research area from the
scientist in charge, whose time would be much better spent for doing
research.

Therefore, the natural strategy is the establishment of a
professionally managed central data repository. This goes hand in hand
with the establishment of data-management procedures that can be
followed "blindly". 
</div>

## People

<div>
Project lead: [Harald von Waldow](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/harald-von-waldow/)   
Steering Group:  [Jochen Bihn](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/jochen-bihn/),
 [Lothar Nunnenmacher](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/lothar-nunnenmacher/),
 [Gabriel Piepke](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/gabriel-piepke/),
 [Peter Reichert](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/peter-reichert/),
 [Raoul Schaffner](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/raoul-schaffner/),
 [Rosi Siber](http://www.eawag.ch/de/ueberuns/portraet/organisation/mitarbeitende/profile/rosi-siber/)
 </div>
 
## Co-operation with other projects

<div>
We aim to connect with related initiatives within the ETH-domain and Swiss universities. Currently we are in contact with WSL.
With regard to the software, we are part of the global CKAN developer community.
</div>

## Time-line

</div>

<script>

$( document ).ready(function() {
	$( "#accordion" ).accordion({
	heightStyle: "content",
	collapsible: true
	});
});
</script>

<style>
.ui-widget-content a {
    color: #00F;
	}
</style>
