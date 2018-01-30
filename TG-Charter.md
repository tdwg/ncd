# Collections Descriptions Task Group Charter
## Rationale and Motivation
Meetings of the Natural Collections Description (NCD) Interest Group at TDWG 2016 and TDWG 2017 confirm the need for a collections description standard. This Scientific Collections Descriptions Task Group seeks to provide a standard that results in the ability to provide automated collections-level metrics and better collections visibility. Prior work done by the NCD Interest Group provides the starting point. We need an acceptable (adequate) vocabulary that describes the collections themselves, not the published datasets. This is especially critical for discovering collections that are not yet publishing there data anywhere.
There are valuable collections that have no information stored in any database and many do not have a presence on the Internet. Institutional and Collection-level data currently shared along with specimen-record-level data records is often sparse and not in any way complete. This collection-level data is currently mapped to the Ecological Metadata Language (EML) standard originally developed to meet the data-sharing needs of the ecological community. Data provided in the EML data file often conflates data about what is in the dataset being shared with data about the entire collection or institution. 
Collections-level data are often also shared in free-text fields making automated tracking of worldwide collections status and metrics, very difficult or impossible. Development, adoption, and implementation of a carefully curated set of collections concepts will support much-needed access to collections-level information necessary for policy, regional, organization, governmental, and individual decision making. This information must be accessible via a collaboratively developed API.

## Mission and Scope
The overall mission includes reaching out to the broader collections community to insure we are including terms and concepts in the standard that are critical to collections discovery, collections use, collections expertise documentation, and worldwide collections status. Some of this work has been done through the TDWG 2016 and TDWG 2017 meetings, but also through other initiatives such as the GRBio group, GBIF, iDigBio, VertNet, the ABCD standard development group and others. Our 2016-2017 meetings suggest a narrower scope from the original NCD existing draft. Since the original draft, much has changed in the data standards landscape. Those providing input to this endeavor suggest focusing on scientific collections while recognizing the need to be able to share data about related collections (such as art derived from the science collections).
Standards developed by other groups can now be used so that while the original NCD set of terms were completely stand-alone, going forward we should be able to pull most terms from other standards such as schema.org organizations, FOAF for people, etc.
Development of this collections-level data resource also facilitates further development of a linked-data scenario making it simpler and more automated to cite and attribute collections use and track these uses. Such a resource helps administrators / collection managers / curators / universities to learn about and demonstrate the value of their collections.

## Issues of the Task Group 
* Resource discovery -- taxonomic and geographic coverage; collecting/collector history (expeditions?); ancillary collections and data sets, such as tissues, field notes, measurements, inventories.
* Provide guidelines for referencing collections and specimens in both human readable and machine actionable forms
* Integrate registration of data providers with collection-level descriptions, including material that is not yet digital
* Estimating the scope of digitization work to be done; conversely, summarize what has been digitized
* Data quality assessment

## Challenges
* tracking undigitized collections (need to discover them first)
* allow / deal with merging / splitting collections
* DH / AT suggest we can authoritatively manage the IDs necessary to implement this. Will need to use contextual clues embedded in records to disambiguate.
* exactly which parts of these records need to be (must be) machine readable?
example: collectionCodes confusion, who are the contacts for what purpose
* prototype. Will there be a public interface for humans to update? Some (most?) of this will be via an API - not human-mediated. So how do these fit / link so everyone can fulfill their role.
* access / curatorial control: Authorization (Authentication), Curation, Accreditation
* authority. Who are the authors of this data?
* life-cycle issues. (from DH) what can we learn about life-cycle issues from the publishers?
* collection outreach / invitation. We will need carrots / incentives to invite / include people in this endeavor. We need a model (is there one)?
* DH can we use this as a way to bootstrap curation of collections data? (future)

## Responsibilities by Task Groups
* Use Cases group (Barb Thiers): gather and evaluate. Gathering done (not exhaustive). Use cases don’t need to be comprehensive. Barb notes it would be good to figure out how to identify compelling collections (for conservation, CITES, transfer of material, discovering which are at risk, etc). These use cases assist with scoping the data standard. Those wishing to help include: Barbara Thiers, Jana Hoffmann, Carolyn Sheffield, and Anissa Lybaert. (Perhaps Connie Rinaldo too).
* Next - Update mappings and crosswalks between other relevant standards such as (ABCD, EML, GRBIO, IH, iDigBio, GBIF). Jana, Falko, (others?) will walk through this exercise to make sure we use DwC, ABCD, ABCD-EFG where appropriate.
* Hypothetical datasets (Dag E?)
* Drafting this charter
* Update the standard

## Organization
* Meet online every other month (or as needed)
* Two co-conveners
* Subcommittees to take on tasks as needed
  * Use Cases group (Barb Thiers)
  * Update mappings and crosswalks (Jana, Falko, ...)
  * Hypothetical datasets (Dag E?)
  * Document data-sharing standard changes needed to implement (DwC-A changes? IPT changes?, etc)
  * Drafting this charter

## Membership
Currently assumed to be those who expressed interest at the last two TDWG meetings.

Barbara Thiers, Joanna McCaffrey, Kevin Love, Alex Thompson, Donald Hobern, Deborah Paul, Sharon Grant, Kate Webbink, (et al at Field Museum), Mike Trizna, William Ulate, Connie Rinaldo, Andrea Hahn, Wouter Addink, Carolyn Sheffield, Holly Little, James Macklin, Anissa A, Joel Ramirez, Melissa Tulig, Falko Glöckler (MfN Berlin), Jana Hoffmann (MfN Berlin), Dag Endresen, Judith Price

## Meetings, documentation and reporting

## Historical documents and Background
* https://terms.tdwg.org/wiki/Natural_Collections_Description
* https://github.com/tdwg/ncd/blob/master/NCD-v090_TDWG/NCD-v090_TDWG-NonNormative.doc
* https://github.com/tdwg/ncd/blob/master/NCD-v090_TDWG/NCD-v090_TDWG-Normative.doc
* [also mapping from David Schindel]
* link to 2016 and 2017 interest group abstracts
* Randy’s thesis findings / products on what can be learned / deduced from collections that are publishing

## Draft Specifications
* https://github.com/tdwg/ncd/tree/master/NCD-v090_TDWG

## Expert reviews
* Jonathan Rees
* GBIF
* iDigBio
* VertNet
* Symbiota
* Specify?
* ARCTOS

