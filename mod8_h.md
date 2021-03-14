OPAC Design Decision: Indexes
=============================

Online catalogs (integrated library systems and OPACs) catalogs are not generally built in-house. Rather, a commercial system is purchased or an open source system is implemented. Even when an outside system is implemented, functions can be customized to meet local needs. In previous pages you read about features of OPACs and some issues. In this page and the next, you have the opportunity to consider decisions that can be made locally to customize an online catalog to meet local needs. 

System design will be based on several criteria, including:

*   **User group(s).** Identify the potential users and characteristics of those groups, especially characteristics related to information seeking behavior. 
*   **User tasks.** Understand what users are seeking to accomplish though online catalogs. IFLA LRM user tasks can be useful here.
*   **Types of material in the collections (books, videos maps, etc.).** Some materials have specific metadata elements that can impact design decisions. Different types of materials may have specific user groups, too. 
*   **Metadata.** Consider the strengths and limitations of the scheme(s) and standards used in local cataloging processes. Also, if brief bibliographic records without subject headings are included, indexes that search subject headings will not make a difference.
*   **Capabilities of the system.** Online catalogs may have built in limitations. For example, the may allow a limited number of indexes to be created.
*   **Technical skills of available staff.** Customizing a system can be time-consuming. Also, when upgrades are made to the software, customizations can make that process more complicated.

A well-designed online catalog can play an important role in meeting the needs of users, whether the users are public patrons or library staff. Ideally, a library might conduct its own user testing. When that is not feasible, a careful analysis of other implementations, reading of the literature, and application of principles can provide guidance.

**Overview of some design elements to be considered**
-----------------------------------------------------

#### **Indexes**

In this context, what is an index? 

In the SAA Dictionary, two definitions for Index are:

> ##### **[index](https://dictionary.archivists.org/entry/index.html)**
> 
> n. (indexes, indices, pl.)
> 
> 1\. An ordered list of headings that points to relevant information in materials that are organized in a different order.
> 
> 2\. A portion of a book, usually located in the back, that provides an ordered list of subjects covered in the book, with page numbers or other reference to where those subjects are discussed.
> 
> **Notes**
> 
> Generally, an index (1) provides no explanation about the information it points to beyond its location. It is distinguished from a catalog, which provides additional information to help determine relevance. An index may be created on cards, with separate cards for each entry to allow interfiling. It may also be on paper or in a database or word processing file. - An index (2) usually uses page numbers for the pointers, but some works may use section numbers.

An index in the back of the book is a static document. Important words or concepts are identified in the book and a list is created based on those. 

An index in an online catalog operates differently. The list of terms is generated from the access points in a bibliographic record. For example, when a user searches for the author, "Tyler, Anne" the search engine searches the bibliographic records for that text in appropriate MARC fields:

100 1\_ Tyler, Anne.

A list of bibliographic records that include that information are retrieved and displayed. 

[Search results in MERLIN](http://merlin.lib.umsystem.edu/search/?searchtype=a&SORT=D&searcharg=tyler+anne&searchscope=8). 

This is a dynamic list. When a new item is added to the library collection, that item will subsequently be included in search results once the index has been updated. To better understand what an "index" is in an online catalog, view the entries in the drop-down box under "Extended Display" in the MERLIN catalog: [http://merlin.lib.umsystem.edu/search/?searchtype=t&SORT=D&searcharg=car&searchscope=8](http://merlin.lib.umsystem.edu/search/?searchtype=t&SORT=D&searcharg=car&searchscope=8). In the case of Tyler, Anne, the patron will want to search in the author index if seeking a resource by Anne Tyler.

In terms of search mechanics, other than the keyword index, the indexes are browse indexes, which also influences the user's search strategy. 

##### **Local Design Decisions**

What indexes will you need? 

*   Some basic indexes:
    *   Author, contributors, etc.
    *   Title
    *   Subject
*   Beyond those, will you want or need an index for:
    *   Publisher
    *   People: A combined index of persons who are authors or contributors and those who are the subjects of resources. This index will retrieve records that list  Anne Tyler as the author AND as the subject. When library users are looking for the names of people, they do not always make this distinction, so a single index may be helpful. 
    *   Instruments: If  your library includes music materials, do you want an index for instruments needed to perform a score? This can be helpful for all the flutists out there uninterested in piano music.
    *   Identifying numbers, like ISBN, or a CD number.
    *   Geographic areas
    *   Genre and form
    *   Different controlled vocabularies for subjects. If your library uses Library of Congress Subject Headings and Medical Subject Headings, do you need a separate index for each?

Compare the indexes in these two online catalogs. There is overlap. There also are differences that may reflect user needs. Also, note what the indexes are called or labeled. That will be a design decision, too.  

<table table-bordered" width="100%">
<thead>
<tr style="background-color: #de5b49;">
<th>
<h4 class="text-center text-white"><strong>University of Missouri—MERLIN</strong></h4>
<h5 class="text-center text-white"><a class="text-white external" href="http://merlin.lib.umsystem.edu/search/X" target="_blank" rel="noreferrer noopener"><span>http://merlin.lib.umsystem.edu/search/X</span><span aria-hidden="true" class="ui-icon ui-icon-extlink ui-icon-inline" title="Links to an external site."></span><span class="screenreader-only">&nbsp;</span></a></h5>
</th>
<th>
<h4 class="text-center text-white"><strong>Altoona Area Public Library</strong></h4>
<h5 class="text-center text-white"><a class="text-white external" href="https://altoona.sparkpa.org/eg/opac/home" target="_blank" rel="noreferrer noopener"><span>https://altoona.sparkpa.org/eg/opac/home</span><span aria-hidden="true" class="ui-icon ui-icon-extlink ui-icon-inline" title="Links to an external site."></span><span class="screenreader-only">&nbsp;</span></a></h5>
</th>
</tr>
</thead>
<tbody>
<tr>
<td class="p-all-xl style=">
<ul>
<li>Quick search:
<ul class="mt-sm">
<li>Title begins with</li>
<li>Journal, Magazine, Newspaper title begins with</li>
<li>Author (last name first)</li>
</ul>
</li>
<li class="mt-sm">Subjects
<ul class="mt-sm">
<li>Subject (Library of Congress)</li>
<li>Medical Subject (MeSH)</li>
<li>Genre/Form</li>
</ul>
</li>
<li class="mt-sm">Numbers/Other
<ul class="mt-sm">
<li>ISBN/ISSN/Standard Number</li>
<li>Government Publication</li>
<li>Music Number</li>
<li>OCLC/WorldCat</li>
<li>Call Number (Library of Congress)</li>
<li>Medical Call Number</li>
<li>Dewey/Other Call Number</li>
<li>Donor/Honoree</li>
</ul>
</li>
</ul>
</td>
<td class="p-all-xl style=">
<ul>
<li>Titles&nbsp;</li>
<li>Authors</li>
<li>Subjects</li>
<li>Series</li>
<li>Journal Title</li>
<li>Digital Bookplate</li>
<li>Numeric Search
<ul class="mt-sm">
<li>ISBN</li>
<li>UPC</li>
<li>ISSN</li>
<li>Call Number (Shelf Browse)</li>
<li>LCCN</li>
<li>TCN</li>
<li>Item Barcode</li>
</ul>
</li>
</ul>
</td>
</tr>
</tbody>
</table>


##### **Metadata Fields to Include in Each Index**

Once the basic categories of indexes have been identified, system designers must determine what metadata fields should be included in each index.

#### **Examples**

*   What fields will be included in your "author" index? Think of the range of persons and corporate entities that are involved in creating and producing various information resources. Will one index suffice for the following, or do you really need additional indexes for some of these roles?
    *   Authors
    *   Editors
    *   Illustrators
    *   Commentators
    *   Directors
    *   Choreographers
    *   Conductors
    *   Issuing bodies
    *   Authors of individual chapters
*   What fields will be included in your title index? Again, will one index suffice for all of these?
    *   Main title (in libraries, this is called the [title proper](https://products.abc-clio.com/ODLIS/odlis_t.aspx#titleproper)
        
        )
    *   Series titles
    *   Chapter titles
    *   Titles of individual works within the resource. E.g., poems or movie shorts
    *   Movie titles
    *   Video game titles
    *   Portions of titles (e.g., subtitles)
    *   Variations of titles (e.g., the title on the spine of the book if different from the one on the title page/cover)

This decision needs to be made for every index. There will need to be a balance between having indexes that are too specific versus having indexes that do not allow users to differentiate types of information, like titles of books and titles of chapters.

#### Facets

Some online catalogs have facets that allow search results to be limited or refined. 

See these two examples:

*   MERLIN—the facets are listed on a page separate from the search results page: [http://merlin.lib.umsystem.edu/search~S8/Y?NOSRCH=(car)&searchscope=8&SORT=D&SUBKEY=(car)](http://merlin.lib.umsystem.edu/search~S8/Y?NOSRCH=(car)&searchscope=8&SORT=D&SUBKEY=(car))
*   WorldCat—The facets are listed in a men to the left of the search results: [https://www.worldcat.org/search?qt=worldcat\_org\_all&q=car](https://www.worldcat.org/search?qt=worldcat_org_all&q=car)

Facets may include the fields that appear in the browse indexes. Other categories may be used only for facets. Will you have facets in addition to your main indexes that can be used to limit search results? Possibilities:

*   Limit by a single date or date ranges
*   Limit by type of resource—book, video, map, etc.
*   Limit to online resources or material in the library

#### Keywords

Google has made the single search box the expected and desired mode of searching for many users. A system designer must decide which metadata elements will be included in the keyword indexes.

As you consider the following questions, look at the information in this bibliographic record and consider what elements would be useful in a keyword index and which would not: [http://merlin.lib.umsystem.edu/record=b13470522~S8](http://merlin.lib.umsystem.edu/record=b13470522~S8)

*   What fields will be included in your overall keyword index?
*   Do you need subsets of the keyword index, to provide keyword searching for certain types of metadata? Possibilities:
    *   Author
    *   Title
    *   Subject
*   In addition to establishing the keyword indexes, there may be an option to determine how to weight different metadata fields. Example: For a subject keyword index, the words in the title and summary may be given more weight than a word in the title.

#### **Next**

_Additional design elements: Displays. This page focused extensively on decisions about indexes, but also showed how display can factor in. The next page looks more closely at design elements for representing catalog information in libraries._