# Use Cases 

## Index Herbariorum 

The IH search page is consistently the most-visited webpage in the NYBG Virtual Herbarium (72,998 visits in the past 12 months, or 199/day). Study of web use statistics and direct feedback from users reveals a wide user base, the main groups of which are summarized here. <--- I think this should be a link

### Herbarium commerce 

Annually, herbaria send and receive an estimated 10 million specimens as loans, gifts, exchange, and other transfers. The information contained in IH allows herbaria not only to address their shipping boxes correctly, but also to assess the reliability of herbaria to which they are considering lending specimens. Herbaria use the information included in IH about staff expertise to find individuals who can provide identification or evaluation of specimens of a particular group or region. Herbaria use IH to find partners for the exchange of specimens that augment their own holdings.  

### Biodiversity surveys or evolutionary reconstructions of a taxonomic group 

Researchers use IH to find previously collected specimens that are pertinent to their studies, to determine what taxa and geographic areas are well represented and which are not (and therefore require additional study) and to develop collaborations to facilitate new field studies. In order to obtain permits for field surveys in a foreign country, it is usually essential to develop a partnership with an herbarium in that country, where one set of voucher specimens must be deposited.  Scientists conducting research in foreign countries use IH to determine the best partner in the relevant country and to make contact with those individuals.  

### Scientific journals 

Journals use IH codes in the citation of specimens examined for a given study, including the designation of type specimens in the description of new species.  Journals such as Systematic Botany, Mycologia, Brittonia and The Bryologist will not accept for publication an article describing a new species that does not cite a standard IH acronym as the place of deposition for the type specimen of a new species.

### Collaborative projects 

Collaborative projects often use IH as a tool for identifying the range of participants and resources for such projects.  For example, IH played a key role in identifying potential participants in the Global Plants Initiative (5) a project to digitize all type specimens in the world’s herbaria and serve these through a common web portal. The National Ecological Observation Network (6) has used IH to find taxonomic expertise and collection repositories near NEON sites to help with the biodiversity inventories of these sites.  The International Association of Plant Taxonomists uses IH data to determine the number of institutional votes each herbarium should have for the nomenclature session at the International Botanical Congress meetings every six years.

### U.S. Government agencies use IH for several purposes 

Collecting permits for National Parks and other protected federal lands require that specimens collected on these sites be deposited in IH listed herbaria.  The U.S.  Fish & Wildlife Service uses IH as a resource for determining whether or not an institution should be granted a permit to house endangered species (a CITES permit) and uses IH code as part of the CITES permit identifier.  Recently U.S. Fish and Wildlife used the email contact list for IH to send a questionnaire to all herbaria asking them to evaluate their experiences applying for and managing CITES permits.  Additionally, IH is used by Homeland Security to find specialists for the identification of unknown specimens confiscated at U.S. customs.  Natural Resource Managers use IH to find experts to identify species on federal lands.  The National Park Service uses IH to keep track of specimens collected in National Parks for their annual inventories and collection assessments.



## Smithsonian Field Book Project

The Field Book Project is a collaborative grant-funded initiative based at Smithsonian to catalog, digitize, and provide open access to scientists’ field notes held in the collections of the Smithsonian Institution Archives and other Smithsonian departments.

The Field Book Project cataloging approach involved creating collection level records, item level records, and authority records for people, organizations, and expeditions.  Collection level records were created using a subset of elements from NCD v.0.7.  Item level records were created using MODS (Metadata Object Description Schema, a somewhat simplified version of the widely adopted library schema MARC), and EAC-CPF (Encoded Archival Context for Corporate Bodies, Persons, and Families) for the authority files.

This use case will focus on the collection level records which were created using the subset of NCD v 0.7 data elements.  As of 23 February 2018, 658 collection records have been created by the Field Book Project. The majority of these records have been published to the Smithsonian Collections Search Center and can be viewed here: http://collections.si.edu/search/results.htm?view=&dsort=&date.slider=&q=unit_code%3AFBR+collection+name

### Collections as defined for field book description

From Nakasone, S. and Sheffield, C. Descriptive Metadata for Field Books D-Lib Magazine, Volume 19, Number 11/2 (November/December 2013) http://www.dlib.org/dlib/november13/nakasone/11nakasone.html#4 :
“A "collection" is defined as any group of field books with a unifying relationship(4). Field book collections can be assembled in many ways; Smithsonian collections, however, are usually grouped by collector or expedition. For example, a collection grouped by the collector Alexander Wetmore would consist of field books created or owned by Wetmore. Alternatively, a collection grouped by the expedition United States Exploring Expedition might consist of field books created by various individuals that participated in that expedition. Less frequently, collections are assembled by the organizations as a creator. However they are grouped, collections are determined based on the way the field books were physically organized, with respect to the provenance and order in which they were received and maintained, prior to our involvement, in accordance with archival practice.”(5)  

4. Society of American Archivists, Describing archives: A content standard, (Chicago: Society of American Archivists, 2004),, 203.  

5. We retain the organization of collections already accessioned by SIA. We use descriptive information in finding aids, when available, as a spring board for our own records and to maintain consistency. For collections maintained by museum departments, generally each collector is given her own collection because that is how the museum organizes it. If the museum chose another way to organize a collection, for example, kept all the field books inherited by another museum together as one group, we would organize the collection in the same way.  

### NCD 0.7 as used by Smithsonian Field Book Project 

These collection records are currently used to aggregate item records from a single field book collection together on the Smithsonian Collections Search Center (SI-CSC): http://collections.si.edu/search/results.htm?view=&dsort=&date.slider=&q=unit_code%3AFBR+collection+name

Each of these collection and item records also link to the Field Book Project-produced authority profiles for persons, organizations, and/or expeditions involved in their creation. 

For more information on how the Field Book Project used NCD v0.7, the Field Book Project Cataloging Manual is available here:
https://drive.google.com/file/d/0BzbZIJVfq9rPUHQ3NDl6Y2Zha0U/view
Section 1 focuses on Collection Level Description and includes a summary of elements used followed by detailed information specific to how the Field Book Project uses those elements, including definitions, recommended data values, and examples.

## GBIF Data Management

GBIF has a multi-faceted interest in collection descriptions metadata.

### Publishing and sharing collection description metadata

Some GBIF nodes (notably Atlas of Living Australia) collect and manage collection metadata as a national-scale catalogue.  This is frequently a scale at which such information can efficiently be gathered and curated, and GBIF is interested in promoting and reinforcing this approach across its nodes, while at the same time avoiding unproductive overlaps with Index Herbariorum and other community initiatives.

### Increasing linked-open-data aspects of GBIF aggregated data

A primary goal for GBIF in aggregating and indexing specimen data (and other occurrence records) is to increase normalisation and to deduplicate diffuse text references to known concepts and entities, including e.g. countries, taxon concepts, field collection protocols, etc.  A key class of entities for which this should be possible is the set of natural history collections.  A well-managed catalogue/vocabulary of the world's NHCs would offer many opportunities to normalise collection codes/identifiers in specimen records and establish linked-open-data pathways within accessible biodiversity data.

### Collection description metadata as anchor for subsequent digitisation

Publishing a collection description can be seen as the first step in bringing a collection online and is concsequently a useful point to start engagement with collections.  The description record can then serve as the anchor point for linking further digitisation products, including refining taxonomic scope through checklists, publishing Darwin Core records, and augmenting with rich digital media and other artefacts.

### Promoting data mobilisation by GBIF national nodes

A comprehensive baseline catalogue of the world's NHCs, including information on taxonomic/geographic scope and coverage and of current digitisation status, would form a key tool to support annual planning by nodes for priority actions to support or advance data mobilisation, and a baseline for measuring progress.

### Supporting researcher discovery and access for undigitised materials

GBIF is interested in understanding which collections hold currently indigitised materials, so these collecitons can be highlighted as part of some searches.  This will assist taxonomists and others in locating material and perhaps stimulating digitisation.

### Developing fundable digitisation proposals

It will be much easier to plan and seek funding for digitisation projects for a single institution or a network of related collections if there is a clear public view of what they hold and what they have to offer as part of an integrated biodiversity knowledge resource.  This is an opportunity for collections to highlight what they have that is unique.
