---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.10.2
  kernelspec:
    display_name: Python 3
    name: python3
---

<!-- #region id="LNqdy_L_pS_Y" -->
"Metadata for All" (Elings & Waibel, 2007)
==========================================

> Elings, M. W., & Waibel, G. (2007). Metadata for all: Descriptive standards and metadata sharing across libraries, archives and museums. _First Monday_, _12_(3). [https://doi.org/10.5210/fm.v12i3.1628](https://doi.org/10.5210/fm.v12i3.1628)

#### Notes

*   In this final reading for the module, consider how these notions play out in other information agencies.
*   Skim through this reading to reinforce what you know about metadata, to see the names of additional standards, and to clarify the meaning of a few terms used in this module.

#### **Next**

_Congratulations! This is the final page of content for which you are responsible in this module. The next page provides some sources for optional additional readings to further supplement your understanding of metadata and its use in LAMs._
<!-- #endregion -->

<!-- #region id="9j7Y-p9sq1H_" -->

<blockquote><a href="http://www.firstmonday.org/"><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16440" border="0" alt="First Monday" align="BOTTOM"></a><br>
 <hr>

<center><a href="#author"><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16445" alt="Metadata for All: Descriptive Standards and Metadata Sharing across Libraries, Archives and Museums by Mary W. Elings and Gunter Waibel" border="0"></a></center></blockquote>

<br><hr><br>
	
<p>Abstract<br>Integrating digital content from libraries, archives and museums represents a persistent challenge. While the history of standards development is rife with examples of cross-community experimentation, in the end, libraries, archives and museums have developed parallel descriptive strategies for cataloguing the materials in their custody. Applying in particular data content standards by material type, and not by community affiliation, could lead to greater data interoperability within the cultural heritage community.</p>

<p>In making this argument, the article demystifies metadata by defining and categorizing types of standards, provides a brief historical overview of the rise of descriptive standards in museums, libraries and archives, and considers the current tensions and ambitions in making descriptive practice more economic <a name="1a"></a>[<a href="#1">1</a>].</p>

<h3>Contents</h3>

<p><a href="#e1">Introduction</a><br>
<a href="#e2">Key concepts for understanding standards</a><br>
<a href="#e3">A grid of standards</a><br>
<a href="#e4">How did we get here?</a><br>
<a href="#e5">The library community</a><br>
<a href="#e6">The archives community</a><br>
<a href="#e7">The museum community</a><br>
<a href="#e8">More recent trends</a><br>
<a href="#e9">Conclusion</a></p>

<p>&nbsp;</p><hr><p>&nbsp;</p>
<h3><a name="e1"></a>Introduction</h3>

<p>In the networked age, the efforts of the cultural heritage community to create a compelling pool of digital resources for teaching, research and learning have yielded a range of strategies for integrating content. A quick overview of exemplary projects reveals how the sustainability of these strategies is directly related to the maturity of standards enabling data sharing and aggregation. In other words, the more standards start to infuse the daily activities of describing content in museums, libraries and archives, the more successful the attempts to aggregate become.</p>

<p>Consider the following snapshots of prominent content aggregations:</p>

<blockquote><p>The <em>AMICO Library</em> was conceived in 1997, a full year before eXtensible Markup Language (XML) became a W3C recommendation, let alone a household name in cultural heritage institutions. Lacking a readily available standard for data encoding, the AMICO consortium invented a data format consisting of a field-prefix (such as OTY for Object Type) and the field delimiter “}~” to exchange information (AMICO) <a name="2a"></a>[<a href="#2">2</a>]. The burden of gathering data for the 27 required fields describing the artwork, plus the 16 required fields describing its surrogate, and exporting them in a non-standard format required many data contributors to dedicate full-time positions to the endeavor of sharing information.</p>

<p>In 1999, a consortium of California institutions decided to try a different approach to integrating museum content: <em>Museums and the Online Archive of California</em> (MOAC) <a name="3a"></a>[<a href="#3">3</a>] implemented a mark-up standard from the archival community (<em>Encoded Archival Description</em> or EAD) to bring their resources into an existing state-wide aggregation of library special collections and archival content. While the standard proved capable of transporting the desired information, its deep roots in archival practice made EAD an unlikely candidate for museum-wide adoption. One of the keys to the project’s success was the local availability of database tools which masked EAD’s complexity to the museums and facilitated the transformation of collections management information into the Online Archive of California’s data format of choice.</p>

<p><em>RLG Cultural Materials</em>, online since 2001, has reaped some benefit from an increasing adoption of XML in the community. However, the libraries, archives and museums participating in the effort displayed such diversity of practice in describing collections that RLG adopted a policy of “come as you are” rather than to stipulate a single contribution format. In contrast to AMICO and MOAC, this decision shifted the burden of data integration largely to the aggregator. Just as the museums in the case of AMICO, now RLG dedicated full-time positions to re-formatting incoming collections so they could successfully be queried as a union resource. <em>ARTstor</em>, launched in 2004, has faced many of the same challenges.</p>

<p>In the visual resources community, the <em>Union Catalog of Art Images</em> (UCAI) project at the University of California, San Diego began studying the possibility of aggregating descriptions to facilitate copy-cataloging among slide libraries in 2002. The capability to automatically cluster descriptions for surrogates of the same artwork coming from different institutions emerged as a key requirement for the project. While clustering algorithms had been successfully used in the RLG Union Catalog across a body of highly standardized bibliographic MARC records, the lack of standardization in key data elements such as agent, title, date, repository name and work type among UCAI partners turned out to be a major obstacle for replicating the same technique in a visual resources setting <a name="4a"></a>[<a href="#4">4</a>].</p></blockquote>

<p>During the life-time of two UCAI Mellon grants from the Arthur W. Mellon Foundation (from the 2002 inception to the Phase II final report issued in early 2006), the world of standards changed significantly, and not in small part thanks to aggregation projects and organizations with a vested interest in building out the standards infrastructure. The members of the UCAI team and the lessons learned in trying to aggregate visual resources content have been essential in shaping the <em>Visual Resources Association (VRA) Core 4.0</em> (beta), and particularly its associated XML Schema <a name="5a"></a>[<a href="#5">5</a>]. ARTstor supported the Getty Trust in creating and testing an XML Schema for encoding a subset of the <em>Categories for the Descriptions of Works of Art</em> (CDWA), aptly titled CDWA Lite <a name="6a"></a>[<a href="#6">6</a>]. RLG, in its new incarnation as RLG Programs/OCLC, plays an active role in disseminating the use of CDWA Lite among museums <a name="7a"></a>[<a href="#7">7</a>].</p>

<p>Both the VRA Core and CDWA Lite are intimately tied <em>Cataloging Cultural Objects</em> (CCO) (Baca, <em>et al.</em>, 2006), a data content standard for describing works of material culture and their surrogates. While published by American Library Association (ALA) Editions, the standard has been shaped primarily by professionals associated with the visual resources and the museum community, with library and archival professionals serving in advisory roles. As the rest of this article will show, CCO is poised to play a pivotal role in integrating descriptions of cultural objects across the domains of museums, libraries and archives. Wide adoption of a data content standard such as CCO was one of the missing pieces in the standards infrastructure at the inception of all the aggregation projects outlined above.</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e2"></a>Key concepts for understanding standards</h3>

<p>Since the last paragraph displays an increasing use of acronyms as well as the idea of several standards working in concert, it might be helpful to take a step back and consider how the landscape of standards can be categorized. The following taxonomy of standards is in large parts derived from the <em>Descriptive Metadata Guidelines for RLG Cultural Materials</em> (RLG, 2005). To illustrate the different terms and their relationship, these guidelines use a metaphor that likens a record to a case of bottles being labeled, filled, stored, and delivered.</p>

<p>&nbsp;</p>
<table><tbody><tr><td><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16446" alt="Data fields and structure"></td><td><b>Data fields &amp; structure</b></td></tr></tbody></table>
<p>Data fields are the named units of information, often also referred to as “elements” or “categories,” which are organized into a record by a <em>data structure</em>. In terms of our metaphor, <em>data fields and structure</em> standards are like bottles waiting to be filled.</p>

<p>CDWA, for example, defines individual data fields as well as a totality of fields which can be used to construct a record, and therefore can be called <em>data fields and structure</em> standards (often just shortened to <em>data structures</em>).</p>

<p>&nbsp;</p>
<table><tbody><tr><td><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16447" alt="Data content and values"></td><td><b>Data content &amp; values</b></td></tr></tbody></table>
<p><em>Data content</em> and <em>data values</em> are the information proper stored in the data fields. More specifically, <em>data content</em> standards are the rules that guide you in filling a particular data field, while <em>data value</em> standards are the thesauri or name authorities providing preestablished terms to populate a data field. In terms of our metaphor, <em>data content</em> and <em>data value</em> standards establish what goes into a bottle.</p>

<p>CCO, for example, gives guidelines and recommendations for entering information into data fields crucial for documenting material culture, and therefore can be called a <em>data content</em> standard. In many instances, CCO recommends the use of controlled vocabularies such as the <em>Art &amp; Architecture Thesaurus</em> (AAT) or the <em>Union List of Artist Names</em> (ULAN), and those can be called <em>data value</em> standards.</p>

<p>&nbsp;</p>
<table><tbody><tr><td><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16448" alt="Data format"></td><td><b>Data format</b></td></tr></tbody></table>
<p><em>Data format</em> refers to the particular encoding of information contained within a file. In terms of our metaphor, a <em>data format</em> corresponds to the crate in which the bottles can be stored and shipped.</p>

<p>XML, for example, encodes data fields and their values into a hierarchically structured file, and therefore can be called a <em>data format</em> standard. At this point in time, most data structures in the cultural heritage community can be expressed in an official XML instantiation, such as CDWA Lite XML.</p>

<p>&nbsp;</p>
<table><tbody><tr><td><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16449" alt="Data structure"></td><td><b>Data exchange</b></td></tr></tbody></table>
<p><em>Data exchange</em> refers to the particular protocol used to share a collection of records. In terms of our metaphor, <em>data exchange</em> corresponds to a person delivering the crate of bottles.</p>

<p>The <em>Open Archives Initiative Protocol for Metadata Harvesting</em> (OAI-PMH) <a name="8a"></a>[<a href="#8">8</a>], for example, makes collections encoded in XML available for harvest by aggregators (in OAI speak, service providers), and therefore can be called a data exchange standard.</p>

<p>Here is an example of how <em>data fields and structure, data content and values, data format</em> and <em>data exchange</em> specifications work hand in hand to establish standards-based, shareable data:</p>

<ul><li><p>A data field and structure specification such as CDWA defines a discrete unit of information as “Creation Date” with sub-categories for “Earliest Date” and “Latest Date.”</p></li>

<li><p>A data content standard such as CCO specifies the rules for formatting the date “Late 14<sup>th</sup> century” for display and using an ISO 8601 format “1375/1399” for machine indexing.</p></li>

<li><p>A data format such as CDWA Lite XML allows you to encode all of the information:<br>

</p><pre>&lt;cdwalite:displayCreationDate&gt;Late 14th century&lt;/cdwalite:displayCreationDate&gt;

&lt;cdwalite:indexingDatesWrap&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;cdwalite:indexingDatesSet&gt;&lt;cdwalite:earliestDate&gt;1375&lt;/cdwalite:earliestDate&gt;

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;cdwalite:latestDate&gt;1399&lt;/cdwalite:latestDate&gt; &lt;/cdwalite:indexingDatesSet&gt;

&lt;/cdwalite:indexingDatesWrap&gt;</pre><p></p></li>

<li><p>A data exchange standard such as OAI allows you to share the record.</p></li></ul>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e3"></a>A grid of standards</h3>

<p>As the example shows, the museum community now for the first time has a complete and appropriate suite of standards for sharing descriptions. Substitute CDWA with VRA Core, and the same (at least in beta) holds true for the visual resources community. The graphic below illustrates both the parallel standards in use across different communities, and how the landscape of acronyms appears somewhat more manageable by classifying standards according to the taxonomy outlined above.</p>

<p>&nbsp;</p>
<center><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16450" alt="table 1"><p><b>Table 1: A representation of primary standards in use by a variety of different communities</b> <a name="9a"></a>[<a href="#9">9</a>].</p></center>
<p>&nbsp;</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e4"></a>How did we get here?</h3>

<p>Looking at the impressive standard’s infrastructure the different knowledge domains have created begs the question of how all of the pieces of this puzzle historically have fallen into place, and what lessons the communities learned from each other as they framed the appropriate way of describing their primary materials of custody. The following overview illustrates that the road to standard’s development in museums, libraries and archives has been long and often bumpy, yet the benefits have always been compelling enough to merit the journey.</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e5"></a>The library community</h3>

<p>Libraries have a long history of using shared standards and tools in their community. The first set of published rules was developed in 1852 by Smithsonian Librarian Charles Coffin Jewett (Jewett, 1852). These, as well as other rules that followed, led to the eventual establishment of the first Anglo-American cataloging code in 1908. The Library of Congress (LC) used this code to produce standardized bibliographic records, which were distributed to thousands of U.S. libraries on printed catalog cards and in the <em>National Union Catalog</em> (Piggot, 1988). The 1908 rules were later codified in <em>Anglo-American Cataloging Rules</em> (AACR) published in 1967. While AACR has enjoyed wide adoption in past decades, rules for bibliographic description are still evolving. AACR will eventually be replaced by a new, more broadly applicable standard called <em>Resource Description and Access</em> (RDA), scheduled for release in early 2009.</p>

<p>Adopting common rules, libraries have also long relied on shared term authorities and thesauri. The main source of controlled vocabulary or data values is the <em>Library of Congress Subject Headings</em> (LCSH). The almost ubiquitous use of this source, as well as other LC vocabularies, such as the <em>Library of Congress Name Authority File</em> (LCNAF) and the <em>Thesaurus for Graphic Materials</em> (TGM I &amp; II), has aided integration of library records and end-user searching.</p>

<p>The creation of <em>MAchine Readable Cataloging</em> (MARC) in the 1960s also greatly facilitated the exchange of standardized bibliographic data among libraries. MARC’s computer-readable format (ISO 2709) and the mature cataloging apparatus that has developed around it have not only encouraged record interchange but also the development of turn-key tools and systems within the library community. Libraries can purchase integrated library systems that “plug and play” with MARC cataloging standards, enabling them to share their information across multiple systems. Through these processes, libraries can contribute records to content aggregators, participate in shared or “copy” cataloging efforts, and merge records in union catalogs <a name="10a"></a>[<a href="#10">10</a>]. Furthermore, the development of the MARC XML schema in the 1990s allows libraries and aggregators take advantage of modern network protocols such as Z39.50/SRU (Search/Retrieve via URL) and SRW (Search Retrieve Web Service) protocols, and OAI <a name="11a"></a>[<a href="#11">11</a>]. The recent creation of MARC’s plain language XML counterpart, <em>Metadata Object Description Standard</em> (MODS), seeks to do the same with less complexity and more efficiency.</p>

<p>The development of data standards for describing bibliographic materials, while still evolving, can be looked upon as a success story. It demonstrates that by using common tools and standards, information can be broadly distributed and systems can be designed to further the goal of sharing resources, reducing costs, and providing increased access.</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e6"></a>The archives community</h3>

<p>Archives amass large collections of unique, primary source materials and, for efficiency, describe them at the collection level using finding aids (registers or inventories). Historically, finding aids were locally developed, hand- or type-written paper documents that resided only in a holding repository, making it difficult to share them broadly.</p>

<p>As MARC developed, archives attempted to share archival information by cataloging collections in library systems, eventually establishing the MARC <em>Format for Archival and Manuscripts Control</em> (AMC) specifically for their collections. Using AACR rules, archives eventually created their own content standard, <em>Archives, Personal Papers, and Manuscripts</em> (APPM), in 1983 to facilitate the description of archival materials within MARC bibliographic systems. While this strategy was no comparison to making the full finding aid available, it did integrate archival records within bibliographic catalogs and make the information, albeit limited, far more accessible than it had been in paper form.</p>

<p>As networked access developed in the 1990s, putting full finding aids online became a possibility. The publication of <em>Encoded Archival Description</em> (EAD) in 1999 provided the archival community with its own data structure and format for sharing the complex hierarchical relationships inherent in archival collections. As a data format it was initially expressed in <em>Standard Generalized Markup Language</em> (SGML) and in 2002 as XML. EAD has since become a common standard for sharing archival finding aids electronically.</p>

<p>As EAD use grew, content standards like AACR and APPM — both tied to the MARC bibliographic format — fell short. What was needed was a set of more broadly applicable descriptive rules that could be used with both EAD and MARC (SAA, 2003). Published in 2004, <em>Describing Archives: A Content Standard</em> (DA:CS) is a more neutral data content standard that can be used to describe all forms of archival materials, at any level of description, regardless of form, medium, or data structure (SAA, 2004).</p>

<p>While MARC is still considered an efficient method for describing archival resources, with EAD and DA:CS — and using data values drawn from Library of Congress vocabularies — archives have a full complement of data standards for describing archival materials. The wealth of information in finding aids is no longer locked away in remote repositories, but rather can be shared broadly online and via content aggregators. The development of <em>Metadata Encoding and Transmission Standard</em> (METS) as a method for encoding and sharing item-level digital objects within finding aids, such as digitized archival photographs and individual letters, also supports the increased sharing and distribution of archival content.</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e7"></a>The museum community</h3>

<p>Museums collect unique materials that focus on a particular area of specialty. Their mission is one more of outreach and interpretation rather than simply describing materials for search and retrieval. Because of the uniqueness of their materials, local systems for description have historically prevailed and there has been little economic incentive to standardize practices or create systems for shared cataloging. Despite this, museums were early in identifying the need for standards and in leveraging the benefits of technology for information management.</p>

<p>As computing technology emerged, museums were eager to explore how it could assist them in managing collection information. In 1967, the <em>Museum Computer Network</em> (MCN) was formed to create a system for integrating registration and catalog data. Working with IBM, the early MCN group succeeded in creating a mainframe network solution that was used from 1968-1978 (Met, 1968; Ellin, 1969). As personal computers evolved, MCN launched the <em>Computer Interchange of Museum Information</em> (CIMI) Initiative in 1988 to develop a common framework for the exchange of museum information and to encourage “the use of automation and the creation of vendor-based products” in their larger community (Bearman and Perkins, 1994, part 4). Somewhat ahead of its time, the resulting <em>CIMI Standards Framework</em> did make recommendations for applying extant library and archive standards and protocols to museum materials, such as using data formats like SGML and data values from controlled vocabularies, but ultimately recognized the need to develop museum-based solutions (Bearman and Perkins, 1994).</p>

<p>The first attempt to create a data structure specifically for museum information was the <em>Categories for the Description of Works of Art</em> (CDWA) <a name="12a"></a>[<a href="#12">12</a>]. CDWA is an exhaustive element set of 512 categories and subcategories initially envisioned as “a standard to which existing art systems may be mapped and upon which new systems can be developed.” <a name="13a"></a>[<a href="#13">13</a>] It was hoped that CDWA would eventually become an SGML data format, following <em>CIMI Framework</em> recommendations, though that was never fully realized. CDWA has, however, become a common data structure for art museum information and serves as the underlying structure for various homegrown and vendor-based collection management systems.</p>

<p>While CDWA’s adoption has been successful, the museum community still needed a smaller, lighter element set for efficiently exchanging data across systems. In 1998, RLG’s REACH project identified twenty key categories of information shared across various systems. Because of idiosyncrasies in cataloging practices and problems with data exchange, the set was never effectively implemented. The outcome, however, clearly indicated that to exchange or aggregate records, museums needed to develop a shared data content standard and a shared data format for describing their materials <a name="14a"></a>[<a href="#14">14</a>].</p>

<p>The recent development of the data content standard CCO has made progress in this direction (Baca, <em>et al.</em>, 2006). Developed specifically for documenting and cataloging cultural objects and their visual surrogates, CCO makes recommendations for how to structure elements of description and encourages the use of common data values found in appropriate controlled vocabularies and thesauri such as <em>The Art &amp; Architecture Thesaurus</em> (AAT), <em>The Union List of Artist Names</em> (ULAN) and <em>The Getty Thesaurus of Geographic Names</em> (TGN), as well as others. With CCO, the museum and visual resources communities now have a data content standard specific to the materials they describe.</p>

<p>Following on this, the recent development of CDWA Lite as a shared data format has also moved the community forward. In line with the tenets of the REACH project, CDWA Lite includes a subset of nineteen CDWA categories (plus three administrative metadata elements) and can be used to exchange descriptive information between data formats and systems (Boughida, 2005). Because of CDWA’s broad adoption in the museum community, data can be formatted via CDWA Lite for exchange with aggregators or harvested for inclusion in union catalogs through protocols such as the OAI. As a result, the early hope that CDWA would become a vehicle for sharing museum information across systems is now being realized.</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e8"></a>More recent trends</h3>

<p>At the end of this historical overview, observations about trends in the most recent past help to frame some of the current debate surrounding metadata and descriptive practice <a name="15a"></a>[<a href="#15">15</a>].</p>

<p>In the library community, an intense and complex debate about user-appropriate cataloging and access mechanisms has been stirred up by Karen Calhoun’s report to the Library of Congress titled <em>The Changing Nature of the Catalog and its Integration with Other Discovery Tools</em> (Calhoun, 2006). The following quote from the executive summary gives a flavor of the urgency in Calhoun’s assessment: “The catalog is in decline, its processes and structures are unsustainable, and change needs to be swift.” These uncertainties naturally fuel the desire to generate metadata more cost-effectively, and to exploit it in more user-friendly systems.</p>

<p>In the archival community, back-logs of undescribed collections have prompted significant revisions of processing and description guidelines. A report by Mark A. Greene and Dennis Meissner with the tell-tale title <em>More Product, Less Process: Revamping Traditional Archival Processing</em> (Greene and Meissner, 2006) sounds the clarion call for more efficient practices within the existing framework of standards: “We should be paying more attention to achieving basic physical and intellectual control over [...] all our holdings, rather than being content to process a few of them to perfection.” As in the library community, there is a clear need to move towards more economic methods. In the archival as well of as the library realm, the ultimate measure of success is how well mechanisms for access serve the end user.</p>

<p>The debate in the museum community does not display the same fervor of urgency around reform seen in similar discussions in libraries and archives. Museums have shown great interest in experimenting with user-contributed metadata or folksonomies, arguably because these techniques hold out the promise of generating user-friendly access metadata in an affordable manner <a name="16a"></a>[<a href="#16">16</a>]. On the more formalized end of the descriptive spectrum, museums seem primarily concerned with implementing a more mature descriptive apparatus, including the ability to efficiently describe collections using data content standards such as CCO and the capacity to exchange data effectively using data formats such as CDWA Lite.</p>

<p>The museum community has recently begun to think hard about ways to share descriptions and digital images both in-house and with the outside world. Many of the larger museums in the U.S. have started implementing digital asset management systems, which allow them to share the right digital image in the desired file format with the appropriate staff member in an automated fashion (Waibel, 2006). Moreover, coupling new descriptive technologies such as CDWA Lite and CCO with OAI, the Getty has set an effective example for how to share digitized collections as widely and economically as possible (Boughida, 2005). Since the standards infrastructure in the museums community is still evolving, the implications, economic and otherwise, of shareable metadata have yet to be fully explored.</p>

<p>The library community may be on the verge of taking the utility of shared metadata in a networked environment even a step further. Prompted by the already cited user dissatisfaction with the OPAC, libraries have begun a dialog about raising discovery to the network level — in other words, why maintain a costly local system if users find it more efficient to locate information in a resource such as Google Scholar or Google Book Search, which both have the capacity to resolve a search result to local library holdings? <a name="17a"></a>[<a href="#17">17</a>] The traverse from Google via OCLC’s “Find in A Library” back to the local library actually bears remarkable similarity to the “network effect” Ken Hamma urges museums to exploit. In his keynote address during MCN 2006, Ken envisioned a network economy in which museums release their descriptions and digital images into the Internet using OAI <a name="18a"></a>[<a href="#18">18</a>]. These collections then get exposed to their maximum audience by virtue of re-aggregation at various different sites. However, every time an object from a specific museum gets discovered in these various aggregations, the curious user gets led back to the museum’s Web site through an embedded link embedded <a name="19a"></a>[<a href="#19">19</a>]. Across the cultural heritage community, the debate about how to exploit the network so users find our content in the spaces they already frequent, and how to engage them once they have discovered what we offer, remains crucial to the continued relevance of libraries, archives and museums.</p>

<p>&nbsp;</p>
<p><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16444" alt="++++++++++"></p>
<h3><a name="e9"></a>Conclusion</h3>

<p>As the historic overview and the outline of trends clearly shows, visual resources, museums, libraries and archives in the past have inhabited parallel worlds dominated by similar issues and desires. While each of the different domains has developed its own suite of standards, at the end of this article it is important to point out that the wheel did not get reinvented in doing so. The historic record shows that communities often experimented extensively with each other’s specifications, only to find them wanting. What emerges is not a picture of libraries, archives and museums promulgating different standards to describe the same materials, but a rich toolset of descriptive practices which are uniquely adapted to the particular material type they have been originally designed to characterize.</p>

<p>&nbsp;</p>
<center><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16451" alt="table 2"><p><b>Table 2: Reconceptualizing standards as material specific, not limited to one particular community.</b></p></center>
<p>&nbsp;</p>

<p>The revision of Table 1 (Table 2) illustrates this point: for example, rather than conceiving of the suite of standards consisting of CDWA, CCO, CDWA Lite and OAI as the “museum way” of describing objects, this combination of standards emerges as the appropriate form of description for cultural materials, regardless whether they happen to be housed in a library, archive or museum. This argument makes eminent sense: nobody would question the rule of thumb that a book should be described with the suite of standards housed in the “Bibliographic” column (formerly “Library”), even if it is managed by an archive or a museum. By extension, the cultural heritage community should come to an agreement that objects of material cultural should be described by the standards now aligned under “Material Culture,” regardless of which community the owning institution affiliates with. In practice, however, materials often receive their descriptions not on the basis of material type, but on the basis of the availability of local systems to house the description and the expertise to generate it.</p>

<p>The successful integration of digital images of material culture from library, archive and museum collections hinges on the emergence of a more homogenous practice in describing like-materials in different institutions. While data structures can be mapped with relative ease <a name="20a"></a>[<a href="#20">20</a>], data content variance still effectively prohibits economic plug-and-play aggregation of collections. Data content standards such as CCO emerge as the linchpin in a cross–community strategy to make descriptions versatile, shareable and readily integrated into union resources. <img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16443" alt="End of article"></p>

<p>&nbsp;</p>
<a name="author"></a>
<h3>About the authors</h3>

<p><b>Mary W. Elings</b> is Archivist for Digital Collection at The Bancroft Library, University of California at Berkeley and adjunct faculty in the School of Information Studies at Syracuse University, New York. She writes and lectures on metadata and digital collection development in libraries, museums and archives.<br>
Web: <a href="http://bancroft.berkeley.edu/">http://bancroft.berkeley.edu/</a><br>
E–mail: melings [at] library.berkeley [dot] edu</p>

<p><b>Günter Waibel</b> is a Program Officer in OCLC Programs and Research and primarily works with the museum and art library partners of RLG Programs. He blogs at hangingtogether.org, serves on the Museum Computer Network (MCN) board and teaches as adjunct faculty in the School of Information Studies at Syracuse University, New York.<br>
Web: <a href="http://hangingtogether.org/?page_id=11">http://hangingtogether.org/?page_id=11</a><br>
E–mail: waibelg [at] oclc [dot] org</p>

<p>&nbsp;</p>
<h3>Notes</h3>

<p><a name="1"></a><a href="#1a">1.</a><a name="note1"></a> A different version of this article appears in the <em>VRA Bulletin</em> special issue “Creating Sharable Metadata: CCO and the Standards Landscape,” volume 34, number 1 (Spring 2007) under the title “Metadata for All: Descriptive Standards and Metadata Sharing across Cultural Heritage Communities.”</p>

<p><a name="2"></a><a href="#2a">2.</a><a name="note2"></a> <em>AMICO Data Specification</em>, at <a href="http://www.amico.org/AMICOlibrary/dataspec.html">http://www.amico.org/AMICOlibrary/dataspec.html</a>, accessed 18 December 2006.</p>

<p><a name="3"></a><a href="#3a">3.</a><a name="note3"></a> <em>Museums and the Online Archive of California</em>, at <a href="http://www.bampfa.berkeley.edu/moac/">http://www.bampfa.berkeley.edu/moac/</a>, accessed 18 December 2006.</p>
 
<p><a name="4"></a><a href="#4a">4.</a><a name="note4"></a> <em>Union Catalog of Art Images</em>, UCAI Phase 1 and Phase 2 Final Reports, <em>passim.</em> at <a href="http://gort.ucsd.edu/ucai/">http://gort.ucsd.edu/ucai/</a>, accessed 18 December 2006.</p>
 
<p><a name="5"></a><a href="#5a">5.</a><a name="note5"></a> <em>VRA Core 4.0 XML Schema</em>, at <a href="http://gort.ucsd.edu/escowles/vracore4/">http://gort.ucsd.edu/escowles/vracore4/</a>, accessed 18 December 2006.</p>

<p><a name="6"></a><a href="#6a">6.</a><a name="note6"></a> <em>CDWA Lite</em>, at <a href="http://www.getty.edu/research/conducting_research/standards/cdwa/cdwalite.html">http://www.getty.edu/research/conducting_research/standards/cdwa/cdwalite.html</a>, accessed 18 December 2006.</p>

<p><a name="7"></a><a href="#7a">7.</a><a name="note7"></a> The RLG Programs Working Group “Museum Collections Sharing” has created a supportive network of peers interested in implementing CDWA Lite and OAI harvesting. More information at <a href="http://www.rlg.org/en/page.php?Page_ID=335">http://www.rlg.org/en/page.php?Page_ID=335</a>, accessed 18 December 2006.</p>

<p><a name="8"></a><a href="#8a">8.</a><a name="note8"></a> <em>Open Archives Initiative</em>, at <a href="http://www.openarchives.org/">http://www.openarchives.org/</a>, accessed 27 November 2006.</p>

<p><a name="9"></a><a href="#9a">9.</a><a name="note9"></a> All of the acronyms used in this table have either already been spelled out, or will be explained in the next segment of this article.</p>

<p><a name="10"></a><a href="#10a">10.</a><a name="note10"></a> <em>The MARC 21 Formats: Background and Principles, 2.1</em>, at <a href="http://www.loc.gov/marc/96principl.html#two">http://www.loc.gov/marc/96principl.html#two</a>, accessed 9 May 2004.</p>

<p><a name="11"></a><a href="#11a">11.</a><a name="note11"></a> Z39.50, at <a href="http://www.loc.gov/z3950/agency/">http://www.loc.gov/z3950/agency/</a>, accessed 27 November 2006. SRU/SRW, at <a href="http://www.loc.gov/standards/sru/">http://www.loc.gov/standards/sru/</a>, accessed 27 November 2006. OAI, <em>ibid.</em></p>

<p><a name="12"></a><a href="#12a">12.</a><a name="note12"></a> <em>Categories for the Description of Works of Art</em>, at <a href="http://www.getty.edu/research/conducting_research/standards/cdwa/introduction.html">http://www.getty.edu/research/conducting_research/standards/cdwa/introduction.html</a>, accessed 27 November 2006.</p>

<p><a name="13"></a><a href="#13a">13.</a><a name="note13"></a> Imagelib posting: <em>Art Information Task Force</em> (Mon, 3 October), at <a href="http://library.wustl.edu/~listmgr/imagelib/Oct1994/0003.html">http://library.wustl.edu/~listmgr/imagelib/Oct1994/0003.html</a>, accessed 18 December 2006.</p>

<p><a name="14"></a><a href="#14a">14.</a><a name="note14"></a> <em>RLG REACH Element Set for Shared Description of Museum Objects</em>, at <a href="http://www.rlg.org/reach.elements.html">http://www.rlg.org/reach.elements.html</a>, accessed 5 May 2004.</p>

<p><a name="15"></a><a href="#15a">15.</a><a name="note15"></a> Out of scope for this article was the discussion of conceptual references models on the cultural heritage community. Both the museum community (<em>CIDOC Conceptual Reference Model</em>, ISO 21127:2006) and the library community (<em>Functional Requirements for Bibliographic Records</em>) have a framework within which to discuss description at a higher level.</p>

<p><a name="16"></a><a href="#16a">16.</a><a name="note16"></a> For an example supporting this view, <em>cf.</em> Daniel Starr’s talk (MP3 and PowerPoint) “The Art Museum Community Cataloguing Project” during the RLG Partner Forum “More, Better, Faster, Cheaper: the Economics of Descriptive Practice,” at <a href="http://www.rlg.org/en/page.php?Page_ID=20968">http://www.rlg.org/en/page.php?Page_ID=20968</a>, accessed 18 December 2006.</p>

<p><a name="17"></a><a href="#17a">17.</a><a name="note17"></a> To experience the path from the networked collection to the local collections, search for “cataloging cultural objects” in Google Book Search at <a href="http://books.google.com/">http://books.google.com/</a>, follow the link “About this book,” and then click on “Find Libraries.” You’ll be prompted to enter your local ZIP code, and subsequently have a choice of local libraries owning a copy of CCO.</p>

<p><a name="18"></a><a href="#18a">18.</a><a name="note18"></a> Summary of Ken Hamma’s MCN 2006 keynote, at <a href="http://hangingtogether.org/?p=161">http://hangingtogether.org/?p=161</a>, accessed 18 December 2006.</p>

<p><a name="19"></a><a href="#19a">19.</a><a name="note19"></a> For an example of the traverse from an aggregator back to the museum, <em>cf.</em> Erin Coburn’s presentations (both MP3 and PowerPoint at the RLG Partner Forum “More, Better, Faster, Cheaper: the Economics of Descriptive Practice,” at <a href="http://www.rlg.org/en/page.php?Page_ID=20968">http://www.rlg.org/en/page.php?Page_ID=20968</a>, accessed 18 December 2006.</p>

<p><a name="20"></a><a href="#20a">20.</a><a name="note20"></a> At 
<a href="http://www.getty.edu/research/conducting_research/standards/intrometadata/metadata_element_sets.html">http://www.getty.edu/research/conducting_research/standards/intrometadata/metadata_element_sets.html</a>,
accessed 20 December 2006, for a crosswalk of the data structures discussed in this article.</p>

<p>&nbsp;</p>
<h3>References</h3>

<p>Murtha Baca, Patricia Harpring, Elisa Lanzi, Linda McRae, and Ann Baird Whiteside, 2006. <em>Cataloging Cultural Objects: A Guide to Describing Cultural Works and Their Images</em>. Chicago: ALA Editions.</p>

<p>David Bearman and John Perkins, 1994. “Standards Framework for the Computer Interchange of Museum Information,” at <a href="http://www.cni.org/pub/CIMI/framework.html">http://www.cni.org/pub/CIMI/framework.html</a>, accessed 27 November 2006.</p>

<p>Karim Boughida, 2005. “CDWA lite for Cataloguing Cultural Objects (CCO): A new XML schema for the cultural heritage community,” In: <em>Proceedings of the XVI International Conference of the Association for History and Computing</em>. Amsterdam: Royal Netherlands Academy of Arts and Sciences, pp. 49–56, at <a href="http://www.knaw.nl/publicaties/pdf/20051064.pdf">http://www.knaw.nl/publicaties/pdf/20051064.pdf</a>, accessed 25 January 2007.</p>

<p>Karen Calhoun, 2006. <em>The Changing Nature of the Catalog and its Integration with Other Discovery Tools</em>. Library of Congress (17 March), at <a href="http://www.loc.gov/catdir/calhoun-report-final.pdf">http://www.loc.gov/catdir/calhoun-report-final.pdf</a>, accessed 18 December 2006.</p>

<p>Mary W. Elings and Günter Waibel, 2007. “Metadata for All: Descriptive Standards and Metadata Sharing across Cultural Heritage Communities,” <em>Visual Resources Association Bulletin</em>, volume 34, number 1 (Spring 2007).</p>

	<p>Everett Ellin, 1969. “Museums and the Computer, an appraisal of new potentials,” <em>Computers and the Humanities</em>, volume 4, number 1, pp. 25–30. <a href="http://dx.doi.org/10.1007/BF02393447">http://dx.doi.org/10.1007/BF02393447</a></p>

<p>Mark A. Greene and Dennis Meissner, 2005. “More Product, Less Process: Revamping Traditional Archival Processing,” <em>American Archivist</em>, volume 68, number 2, pp. 208–263.</p>

<p>Charles C. Jewett, 1852. <em>On the Construction of Catalogues of Libraries, and Their Publication by Means of Separate, Stereotyped Titles with Rules and Examples</em>. Washington, D.C.: Smithsonian Institution.</p>

<p>Metropolitan Museum of Art, 1968. <em>Computers and their potential applications in museums: A conference</em>. New York: Published for the Museum by Arno Press.</p>

<p>Mary Piggott, 1988. <em>A Topography of Cataloging</em>. London: Library Association, pp. 13–15.</p>

<p>RLG, 2005. <em>Descriptive Metadata Guidelines for RLG Cultural Materials</em>, at <a href="http://www.rlg.org/en/pdfs/RLG_desc_metadata.pdf">http://www.rlg.org/en/pdfs/RLG_desc_metadata.pdf</a>, accessed 4 March 2007.</p>

<p>Society of American Archivists, 2004. <em>Describing Archives: A Content Standard</em>. Chicago: Society of American Archivists.</p>

<p>Society of American Archivists, 2003. <em>Statement of Principles for the CUSTARD Project</em>, at <a href="http://www.archivists.org/news/custardproject.asp">http://www.archivists.org/news/custardproject.asp</a>, accessed 18 December 2006.</p>

<p>Günter Waibel (editor), 2006. “Digital Asset Management in US Museums,” <em>RLG DigiNews</em>, special issue, volume 10, number 6 (15 December), at <a href="http://www.rlg.org/en/page.php?Page_ID=20999">http://www.rlg.org/en/page.php?Page_ID=20999</a>, accessed 20 December 2006.</p>

<p>&nbsp;</p>
<hr width="300">
<p>&nbsp;</p>
  
<h3>Editorial history</h3>
<p>Paper received 30 January 2007; accepted 20 February 2007.</p>
<hr>
  
<a href="../index.html"><img src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16442" border="0" alt="Contents" align="BOTTOM"></a> <a href="/issues/index.html"><img border="0" src="https://firstmonday.org/ojs/index.php/fm/article/download/1628/1543/16441" alt="Index"></a>

<p><!--Creative Commons License--><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/2.5/"><img alt="Creative Commons
License" style="border-width: 0" src="http://i.creativecommons.org/l/by-nc-sa/2.5/88x31.png"></a><br>This work is
licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/2.5/">Creative Commons
Attribution-Noncommercial-Share Alike 2.5  License</a>.<!--/Creative Commons
License--><!-- <rdf:RDF xmlns="http://web.resource.org/cc/"
xmlns:dc="http://purl.org/dc/elements/1.1/"
xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#">
        <Work rdf:about="">
                <license rdf:resource="http://creativecommons.org/licenses/by-nc-sa/2.5/" />
        <dc:type rdf:resource="http://purl.org/dc/dcmitype/Text" />
        </Work>
        <License rdf:about="http://creativecommons.org/licenses/by-nc-sa/2.5/"><permits
rdf:resource="http://web.resource.org/cc/Reproduction"/><permits
rdf:resource="http://web.resource.org/cc/Distribution"/><requires
rdf:resource="http://web.resource.org/cc/Notice"/><requires
rdf:resource="http://web.resource.org/cc/Attribution"/><prohibits
rdf:resource="http://web.resource.org/cc/CommercialUse"/><permits
rdf:resource="http://web.resource.org/cc/DerivativeWorks"/><requires
rdf:resource="http://web.resource.org/cc/ShareAlike"/></License></rdf:RDF> --></p>

<p>Metadata for All: Descriptive Standards and Metadata Sharing across
Libraries, Archives and Museums by Mary W. Elings and Günter Waibel<br>
<i>First Monday,</i> volume 12, number 3 (March 2007),<br>
URL: http://firstmonday.org/issues/issue12_3/elings/index.html</p>
<!-- #endregion -->
