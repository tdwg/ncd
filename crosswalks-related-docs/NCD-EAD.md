NCD.v032	|	|	|EAD ELEMENT
<DescriptiveGroup>	|<NCDID>	|	|
	|<CollectionID>                   	|	|<archdesc><did><unitid> 
          Attribute = Source	|	|	|
	|<ParentCollectionID>	|          	|<archdesc><did><unitid> with COUNTRYCODE and REPOSITORYCODE attributes
          Attribute = Source	|	|	|
	|<CollectionName>                  	|	|<archdesc><did><unititle>
          Attribute = Language	|	|	|<langmaterial> with attribute LANGENCODING  (specifies that ISO 639-2 codes are used in the LANGMATERIAL attribute)
	|<CollectionUniformName>	|	|<archdesc><controlaccess><title>
	|<DescriptionText>                 	|	|<archdesc><did><abstract>
          Attribute = Language	|	|	|<langmaterial> with attribute LANGENCODING  (specifies that ISO 639-2 codes are used in the LANGMATERIAL attribute)
	|<DescriptionForSpecialists>	|	|"<archdesc><did><abstract>
or
<archdesc><scopecontent>"
          Attribute = Language	|	|	|<langmaterial> with attribute LANGENCODING  (specifies that ISO 639-2 codes are used in the LANGMATERIAL attribute)
	|<IncludesTypes>	|	|<archdesc><did><abstract>
	|<CollectionExtent>	|	|<archdesc><did><physdesc><extent>
          Attribute1 = Number	|	|	|
          Attribute2 = UnitOfMeasure	|	|	|
	|<CollectionFocus>	|	|<archdesc><did><abstract>
	|<CollectionPurpose>	|	|<archdesc><did><abstract>
	|<Citation>	|how are we defining this field?	|<archdesc><admininfo><prefercite>
	|<Notes>	|	|<archdesc><note>
	|	|	|
	|	|	|
<AdministrativeGroup>	|	|	|
	|<CollectionFormationYearsRange>	|	|<archdesc><did><unitdate type="inclusive">
	|<CollectionDevelopmentStatus>	|	|<note>
          Attribute = Date	|	|	|
	|<ConservationStatus>	|	|<note> or <processinfo>?
          Attribute = Date	|	|	|
	|<DigitalFormats>	|how are we defining this field?	|<dao> or ?? Is this technical metadata?
	|<AccessRestrictions>	|	|<accessrestrict>
	|<UsageRestrictions>	|	|<userestrict>
	|<IPRStatements>                   	|	|<legalstatus>
	|<CollectionContactPost>	|how are we defining this field?	|?
	|	|	|
<InstitutionGroup>	|	|	|
	|<InstitutionID>	|	|
          Attribute = Source	|	|	|
	|<ParentInstitutionID>	|	|
          Attribute = Source	|	|	|
	|<InstitutionName>	|	|<repository>
	|<InstitutionalContactPost>	|	|<repository>
	|<PostalAddressText>	|	|<repository>
	|<ZIPCode>	|	|<repository>
	|<Town>	|	|<repository>
	|<Region>	|	|<repository>
	|<ISOCountryCode>	|	|<repository>
	|<CountryName>	|	|<repository>
	|<Telephone>	|	|<repository>
	|<Fax>	|	|<repository>
	|<Email>	|	|<repository>
	|<LogoURL>	|	|<repository><dao>
	|	|	|
<PersonsGroup>	|	|	|
	|<PersonID>	|<origination>????	|what about using EAC??
          Attribute = Source	|	|	|
	|<NamePrefix>	|	|what about using EAC??
	|<GivenNames>	|	|what about using EAC??
	|<FamilyName>                                 	|	|what about using EAC??
	|<NameSuffix>	|	|what about using EAC??
	|<AdditionalNames>                            	|	|what about using EAC??
	|<PreferredFormOfName>	|	|what about using EAC??
	|<Birthdate>	|	|what about using EAC??
	|<DeathDate>	|	|what about using EAC??
	|<Role>                 	|	|what about using EAC??
<KeywordsGroup>	|	|	|
	|<Verbatim>	|	|
	|	|<TaxonCoverageVerbatim>              	|
                Attribute = Strength	|	|	|
	|	|<CommonNameCoverageVerbatim>         	|
                Attribute = Strength	|	|	|
	|	|<GeospatialCoverageVerbatim>         	|
                Attribute = Strength	|	|	|
	|	|<LivingTimePeriodVerbatim>           	|
                Attribute = Strength	|	|	|
	|	|<CollectionClassVerbatim>            	|
                Attribute = Strength	|	|	|
	|	|<ObjectClassVerbatim>                	|
                Attribute = Strength	|	|	|
	|	|<SpecimenPreservationMethodVerbatim>	|
                Attribute = Strength	|	|	|
	|	|	|
	|<Uniform>	|	|
	|	|<TaxonCoverageUniform>               	|<control access>
                Attribute1 = Source	|	|	|??
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
                Attribute3 = Strength	|	|	|
	|	|<CommonNameCoverageUniform>          	|<control access>
                Attribute1 = Source	|	|	|??
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
                Attribute3 = Strength	|	|	|
	|	|<GeospatialCoverageUniform>          	|<control access>
                Attribute1 = Source	|	|	|??
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
                Attribute3 = Strength	|	|	|
	|	|<LivingTimePeriodUniform>            	|<control access>
                Attribute1 = Source	|	|	|??
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
                Attribute3 = Strength	|	|	|
	|	|<CollectionClassUniform>             	|<control access>
                Attribute1 = Source	|	|	|????????????
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
                Attribute3 = Strength	|	|	|
	|	|<ObjectClassUniform>                 	|<control access>
                Attribute1 = Source	|	|	|????????????
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
                Attribute3 = Strength	|	|	|
	|	|<SpecimenPreservationMethodUniform>	|<control access>
                Attribute1 = Source	|	|	|??
                Attribute2 = IDinSource	|	|	|AUTHFILENUMBER
	|	|	|
<RelatedMaterialsGroup>	|	|	|
	|<RelatedResources>                          	|	|<relatedmaterial>
	|<RelatedCollections>                        	|	|<relatedmaterial>
	|<CollectionDatabaseURL>	|	|<dao>
	|<RichRecordSearchString>	|	|<dao>
	|	|	|
<RecordMetadataGroup>	|	|	|
	|<RecordSource>	|	|
	|<RecordCreator>             	|	|   
	|<RecordIPR>	|	|
	|<RecordCreatedDate>                        	|	|
	|<RecordEditHistory>                        	|	|
	|<RecordEditor>	|	|
	|<RecordEditDate>	|	|
	|<RecordEditComment>	|	|