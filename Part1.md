# Part 1

Target Audience: Standardization Engineers/ Bodies

Goal: Towards best practice in semantic interoperability

- State of the art evaluation
(Select Relevant examples
  - Criteria: coverage of design space and importance of approach (e.g. international standard may have more weight than small individual research project))

- Derive recommendations for semantic interoperability

# Requirements for semantic interoperability standards development
In order to get successful standards on semantic interoperability specifications, a number of requirements must be taken in account by organisations that wish to build a standard:

## Separation of concern
It is important to achieve a clear separation of concern between domain experts and semantic interoperability experts. Without this separation of concern, we can get into the trap that a domain expert has to rely on a semantic interoperability expert to propose a specification, and end up with decisions that are taken by the wrong expert. From a method and tools viewpoint we believe that recommendations must be provided in approaches to create separation of concen. An example of good separation of concern was achieved by the SAREF team when they organized a session for the European Large Scale Pilots during the IoT week in Bilbao in June 2018 to get input from domain experts that theycould use in the specification of an ontology.
We believe that we still lack good practices, recommendations and tools on how  this separation of concern takes place. For instance, domain experts should be able to inspect and update a specification using a domain viewpoint, while the semantic interoperability experts should be able to focus on the semantic interoperability mechanics soundness.
## Evaluation of a specification
It is important to be able to evaluate the “usefulness” of a specification. One typical indicator is the level of consensus. A specification that has not reached consensus is likely not to be adopted. Semantic interoperability standards can fall into this trap if the domain experts get lost in the specification process. The goal should be that domain experts can constantly follow the specification process and agree on the content while semantic interoperability experts guarantee that the specification is sound.
## Business concerns
It is important to be able to take into account business concerns in a specification of a semantic interoperability standard. At least two concerns should be taken into account:
*	Provision for profiles and discovery. Some specifications might concern a market segment of a domainc. For instance high-end device manufacturers might want to add specific semantic specification concerning high end features. Some specifications might even be proprietary. This can happen when device manufacturers agree that they will agree on co-existing solutions. This is often solved by service discovery capabilities. The concept of profiles should also be applied to semantic interoperability standards
*	Support for version management. Semantic interoperability specifications will evolve as a domain evolves to match the needs of different generations of products (e.g. a new generation of smart phone) The rules for compatibility must be anticipated. For instance, we could have a SAREF v1 ontology for a domain that is then replaced by SAREF v2 ontology Rules for allowing this evolution must be agreed upfront


# Some suggestions 
 ## Paragraph "standards and semantic models" suggestion for Part 1 (to improve according to the needs and since standardization experts are here)
TO DO: add table (standards and semantic models) with pros and cons?

Better to check here (will all links): http://wiki.knoesis.org/index.php/KE4WoTChallengeWWW2018#Description_of_the_KE4WoT_Challenge

The Web of Things (WoT) is an extension of the Internet of Things (IoT) to ease the access to data using the benefits of Web technologies [2]. Data is generated by things/devices and then exploited by more and more web-based applications to monitor healthcare or even control home automation devices. There is a growing interest in standardization in designing models to represent devices and produced data as demonstrated by the following standards. Those models should be used to design interoperable smart web-based WoT applications:

* W3C Semantic Sensor Networks (SSN) is the first initiative to address interoperability issues to describe sensor networks through an ontology since devices are required to build WoT applications. A new version of the ontology [3] has been recently released and became a W3C recommendation in October 2017. It is a joint contribution with the Open Geospatial Consortium (OGC) standard, extending and improving the SSN ontology published in 2011.

* W3C Web of Things (WoT) Interest Group is designing a vocabulary to describe interactions between objects through the Web, a potential implementation is the WoT ontology [4]. At the current date of writing, WoT ontology is not aligned with W3C SSN ontologies. A healthcare scenario has been designed "Remote health monitoring system" [5] among several use cases.

* OneM2M, an international standard for Machine-to-Machine (M2M) with the development of the OneM2M ontology [6]. It extends the European ETSI M2M standard. At the current date of writing, OneM2M is not aligned with W3C SSN.

* MyOntoSens modular ontology, mainly based on SSN V1 and OGC standards, has been proposed in [Nachabe et al. 2015] as an improvement of existing WSNs ontologies. It has been standardized in 2015 for medical devices and BANs (Body Area Networks) as a Technical Specification (TS) within the SmartBAN Technical Committee of the ETSI standardization body [7]. This ontology is in particular relevant to build health, wellbeing/wellness and personal safety applications based on smart devices.

* Smart Appliances REFerence (SAREF) [8], is a European standard supported by ETSI M2M and SmartM2M. It mainly covers the smart building applicative domain. The SAREF ontology has been designed re-using SSN and oneM2M according to [Moreira et al. 2017].

* Schema.org is a well-known schema catalog to structure data on Web pages to describe the location, person, etc. The IoT Schema.org extension [9] is planned; nothing concrete has been developed yet, but discussions are ongoing.

* Haystack [10] is a project aiming at standardizing semantic data models and web services. For instance, the Haystack Tagging Ontology which employs SSN V1 ontology has been developed [11] [Charpenay et al. 2015].

 ## Cross-domain use case suggestion
 
 Would Ambient Assisted Living (AAL) would be relevant?
 AAL combines smart homes and healthcare applicative domains
 AAL helps elderly people to stay independent at home.
 
  ## Add Appendix section - with technical details for developers?
  an annexe/appendix section with all technical details would satisfy the developers? and the other audience won't be lost within the document
  
  Part 2 is now referencing a set of concrete tools for ontologies.
  
  ## Derive recommendations for semantic interoperability - "Lessons Learned, Recommendations and Best Practices" 
  we can add one section "Lessons Learned, Recommendations and Best Practices" at the end of the document
  - focus on semantic models (e.g., ontologies)
  - other ideas
  - best practices checklist summary 
  
   Check section Ontology Best Practices - Checklist Summary (page 11)
   
   http://perfectsemanticweb.appspot.com/documentation/SemanticWebBestPracticesForDummies.pdf 
  
