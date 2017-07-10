# Collections Descriptions Interest Group Charter

TDWG Interest Group

## Convenors

Alex Thompson (godfoder(at)acis.ufl.edu)
Deb Paul (dpaul@fsu.edu)

## Core Members

Wouter Addink	(wouter(at)eti.uva.nl)	Technical - NCD Toolkit

Carol Butler	(butlercr(at)si.edu)	Terminology

~Markus Döring	(m.doering(at)BGBM.org)	Technical - RDF~

~Doug Holland	(doug.holland(at)mobot.org)	Data mapping~

~Barbara Mathé	(mathe(at)amnh.org)	Data mapping~

Connie Rinaldo	(crinaldo(at)oeb.harvard.edu)	Documentation

~Larry Speers	(lspeers(at)gbif.org)	GBIF liaison~

~Günter Waibel	(Guenter_Waibel(at)notes.rlg.org)	Resource organiser~

## Motivation

The Group is developing and supporting a data standard, called Natural Collections Description (NCD) for describing entire collections of natural history materials. Examples include collections of specimens, observations data, original artwork, photographs and those from the many voyages of discovery. Collection description records contain information about the collection, access and usage of the collection and where to get more detailed information.

There are valuable collections that have no information stored in any database and many do not have a presence on the Internet. Institutional and Collection-level data currently shared along with specimen-record-level data records is often sparse and not in any way complete. This collection-level data is currently mapped to the Ecological Metadata Language (EML) standard originally developed to meet the data-sharing needs of the ecological community. Data provided in the EML data file often conflates data about what is in the dataset being shared with data about the entire collection or institution.

Collection-level information mapped to EML and currently provided with biodiversity datasets is not sufficient to answer current-day data needs for institutional, regional, national, or international planning. More and richer data about collection holdings and the institutions that house them is desperately needed for strategic prioritization of collections data mobilization. Data-sharing at this level is also problematic as it is not currently available through an API. In other words, there is no machine-to-machine data-sharing or data-update capability. This means all collections-level information worldwide must be updated by hand, by humans and is therefore quickly out-of-date and out-of-sync across disparate resources. Also, collection data provided in the EML data model cannot be used to automatically discover such information as what percentage of a collection is digitized or georeferenced. The original NCD charter and work recognized many of these issues but all members of the group agree the charter needs to be updated in light of new momentum to address these needs, including plans by GBIF for the development of a new resource to manage and share collections-level data.

## Becoming Involved

The Convener would be pleased to hear from anyone, and particularly:

* those that have skills in the implementation of Web-based information systems, or
* in writing descriptions based on interviews with collection owners, or
are owners of collections that would themselves like to test and make use of the standard and associated software, or
* just have an interest in the use of collection descriptions in resource discovery systems.

## History and Context

### What is NCD?

Natural Collections Description (NCD) is a data standard for describing collections of natural history materials at the collection level; one NCD record describes one entire collection.

As part of addressing the critical need for much better knowledge about worldwide collection holders and their holdings, this NCD group recognizes the need for data standards to capture concepts not currently part of the EML standard. Current steps are being taken at GBIF to create an automated collection-level data-sharing resource that will encompass the data currently housed in GRBio. In this sense, the NCD group recognizes our path is one of looking at an implementation and developing a standard that envelops the data and data model found in this implementation. At the same time we will strive to provide a rich, but carefully curated, set of terms and relationships directed at addressing known knowledge gaps and accessibility issues. We understand the need to keep the model as simple as possible, and thoughtfully choosing what collections-level data is critical to providing policy-makers and researchers alike - with the best data available when planning. Making this data available, in a structured format, with a robust API available, would mean, for example, that we could more easily show how many herbarium are digitizing - and how much is done; or what expertise and equipment are available in a given institution. Visualizing institution and collections-level data of this type also presents a captivating way to show the value of this metadata.

The NCD standard covers any type of natural history collection, including specimens, original artwork, archives, observations, library materials, datasets, photographs or mixed collections such as those that result from expeditions and voyages of discovery.

### What are collections descriptions?

~~Collection descriptions are electronic records that document the holdings of organisations as groups of items. Such descriptions complement the more traditional item-level records describing a single specimen or a library book. Each collection record describes one entire collection, including information on the extent and purpose of the collection, conditions of access and use and who to contact for more information.~~

~~A collection is loosely defined as any group of things that have something in common. That "something in common" can be defined by the basic questions that users ask when accessing collections - who, what, where and when. Examples of collections include:~~

* ~~items that were collected or made by a particular person~~
* ~~items that have the same format, such as art on paper~~
* ~~items that came from the same place~~
* ~~specimens that belong to the same taxonomic group~~
* ~~all specimens collected on a research voyage~~

~~In natural history museums, for example, the best known collections are the specimens, the library and the archives. Exhibitions, paintings and sculptures are also collections. The electronic equivalents include datasets and databases (which are collections of item-level records) and the thematic sections of Web-sites.~~

### What are the uses of collection descriptions?

Three main areas are served by collection-level description records:

* Resource discovery, providing a descriptive overview of each collection
* Establishment of relationships between collections in several locations
* As an aid for collections management processes
* Provide complete metadata for other data records (e.g. specimen records)

1. SPEED

  Collections of natural history material can be large. Consequently detailed item-level descriptions often take a long time to generate. A collection-level record can ensure that knowledge about a collection can be rapidly revealed.

  It is also useful to hold the details that are common to the whole collection once, rather than being repeated with the record for each item.

2. CROSS-DOMAIN RESOURCE DISCOVERY

  Relating collections that are in museums, libraries, archives and other organisations (cross-domain resources) is a priority for many governments. By adopting the same standard for collections in each domain, it is possible to search across all collections, regardless of domain or location.

3. RE-UNITING SCATTERED COLLECTIONS

  "Virtual collections" are another way to link resources. Some organisations divide collections between departments for curatorial purposes. Researchers would need to contact each department individually to assess the complete collection. Similarly, some collections, such as those of Darwin, have been dispersed throughout several organisations. These collections may be re-united in a virtual sense, using collection descriptions for each component.

4. POINTER TO ITEM-LEVEL DETAIL

  Collection descriptions are verbose, and therefore complement the rows of raw data that are produced by item-level databases.

  A collection description record can be created for a collection whether the items in that collection have their own records in a database, or not. Where a database containing item-level details exists, a link can be provided to that database to provide more detail.

  If the collection does not have an item-level database, producing a collection description reduces the chances of that collection being overlooked by researchers using the Web for resource discovery.

5. TOOL TO HELP WITH COLLECTIONS MANAGEMENT

  Collection descriptions enable a broad perspective. A set of collection descriptions could serve a variety of additional purposes for any organisation:

  * A collections inventory is helpful in protecting against both loss of data and loss of collections and thus serves as a form of audit control and security against unauthorised disposal.
  * It can help with the assessment of the strengths and gaps in the organisation as a whole, so that finding collaboration partners that have either the same or complementary strengths is simplified.
  * It can help to identify which areas should be a priority for development in strategic plans and to establish priorities for item-level cataloguing.
  * By recording conservation concerns, the priorities for conservation / preservation treatment can be established. Collections cannot be protected if it is not known that they exist.

6. EARLY WARNING OF TECHNOLOGICAL OBSOLESCENCE

  Collection descriptions can serve to prevent loss of data that is in a physical form or data in a format that is nearing technological obsolescence.

  Creating collection descriptions for datasets that includes format information will help to act as an early warning so that data can be transferred to a current format. Data then becomes part of a digital preservation programme, rather than a digital archaeology project.

7. REPOSITORY FOR ADDITIONAL INFORMATION

  Collection description records act as a convenient place to store information volunteered by visitors.

8. MULTIPLE USE OF DATA

  Re-use of data is important. Collection description records can be created with the use of existing published or unpublished resources such as printed catalogues, exhibition planning documents or archival finding aids. Conversely, data recorded in the collection description records can be used to produce exhibit labels.

  The data can also be provided to external initiatives, some of which wish to merge data from several sources to provide regional coverage of biodiversity collections.

### How has NCD evolved and who is involved?

The first steps in standardising collection-level description began with a European Union Framework V project known as BioCASE - the Biodiversity Collections Access Service for Europe. This project ran from November 2001 until early 2005 (more on this at the BioCASE project website.)

An RLG Programs working group of mainly North American natural history librarians and archivists known as RAVNS (Resources AVailable in Natural Sciences) has made the BioCASE metadata standard more generally applicable, rather than dealing only with specimen collections it is now a standard that covers any type of natural history collection. RAVNS includes representatives from the following institutions:

* American Museum of Natural History
* Missouri Botanical Garden
* Museum of Comparative Zoology, Harvard University
* National Museum of Natural History, Smithsonian Institution
* Natural History Museum, London
* New York Botanical Garden
* Peabody Museum of Natural History, Yale University

Discussion at the TDWG 2004 meeting in Christchurch, New Zealand, concluded that a standard for describing natural history collections would fit well with the suite of data standards being developed on behalf of the Global Biodiversity Information Facility (GBIF).

## Summary

The Collections Descriptions Interest Group brings together work on collections descriptions being carried out for the European Union Framework VI programme known as SYNTHESYS and the work performed by RAVNS under the auspices of RLG with that carried out by TDWG members.

Natural Collections Descriptions (NCD) covers all types of collections of natural history material; specimens, original artwork, photographs, archives, published material or a mixture.

The Interest Group is developing NCD for use with RDF to ensure that it integrates with TDWG's common development architecture. The standard enables the aggregation of collections descriptions from many sources and facilitates resource discovery - particularly for collections that do not have a Web presence.

NCD is a standard between the general resource discovery standards such as Dublin Core, and the rich collections description standards such as EAD. Mappings enable the extraction of a Dublin Core record from an NCD record or, conversely, filling out an NCD record into an EAD record.

## Resources

* The NCD Website is at: http://www.tdwg.org/activities/ncd/
* To join the mailing list see: http://lists.tdwg.org/mailman/listinfo/tdwg-ncd
* Discussion and documents are on the Wiki: http://wiki.tdwg.org/twiki/bin/view/NCD/WebHome
