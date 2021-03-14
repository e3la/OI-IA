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

<!-- #region id="NVC9cbOOH_qv" -->
Key Ideas in IO: The Catalog and Cutter's Objects
=================================================

A library catalog has been described as a primary retrieval system in libraries. But, what is the point of a catalog, anyway?

**The Functions of Catalogs**
-----------------------------

The primary functions of library catalogs are to help users, both a community of users and information professionals, search the collection for a known item or for items by subject. In this case, the user already knows the name of the author and/or the title of the item, or has identified a topic of interest. In their searches, users hope to bring together everything in the collections based on the search (i.e., to collocate based on author, title, or topic), and then to evaluate what they find. You will find these ideas presented below.

Below is part of the definition of [catalog](https://products.abc-clio.com/ODLIS/odlis_c.aspx) from the ODLIS:

> **catalog**  
> The purpose of a library catalog, as stated by Charles C. Cutter in _Rules for a Dictionary Catalog_ (1904), later modified by Bohdan S. Wynar in _Introduction to Cataloging and Classification_ (8th ed., 1992), is to offer the user a variety of approaches or [access points](https://products.abc-clio.com/ODLIS/odlis_a.aspx#accesspoint) to the [information](https://products.abc-clio.com/ODLIS/odlis_i.aspx#information) contained in the collection:
> 
> **Objects:**
> 
> 1\. To enable a person to find any work, whether [issued](https://products.abc-clio.com/ODLIS/odlis_i.aspx#issue) in [print](https://products.abc-clio.com/ODLIS/odlis_p.aspx#printing) or in [nonprint](https://products.abc-clio.com/ODLIS/odlis_n.aspx#nonprint) [format](https://products.abc-clio.com/ODLIS/odlis_f.aspx#format), when one of the following is known:
> 
> a. The author
> 
> b. The title
> 
> c. The subject
> 
> 2\. To show what the library has
> 
> d. By a given author
> 
> e. On a given and related subjects
> 
> f. In a given kind of [literature](https://products.abc-clio.com/ODLIS/odlis_l.aspx#literature)
> 
> 3\. To assist in the choice of a work
> 
> g. As to the bibliographic [edition](https://products.abc-clio.com/ODLIS/odlis_e.aspx#edition)
> 
> h. As to its character ([literary](https://products.abc-clio.com/ODLIS/odlis_l.aspx#literarywork) or [topical](https://products.abc-clio.com/ODLIS/odlis_t.aspx#topic))
> 
> The preparation of [entries](https://products.abc-clio.com/ODLIS/odlis_e.aspx#entry) for a library catalog (called [cataloging](https://products.abc-clio.com/ODLIS/odlis_c.aspx#cataloging)) is performed by a [librarian](https://products.abc-clio.com/ODLIS/odlis_l.aspx#librarian) known as a [cataloger](https://products.abc-clio.com/ODLIS/odlis_c.aspx#cataloger). British spelling is _catalogue_. [Abbreviated](https://products.abc-clio.com/ODLIS/odlis_a.aspx#abbreviation) _cat_. Compare with [bibliography](https://products.abc-clio.com/ODLIS/odlis_b.aspx#bibliography) and [index](https://products.abc-clio.com/ODLIS/odlis_i.aspx#index). **_See also_**: [classified catalog](https://products.abc-clio.com/ODLIS/odlis_c.aspx#classifiedcatalog), [dictionary catalog](https://products.abc-clio.com/ODLIS/odlis_d.aspx#dictionarycatalog), [divided catalog](https://products.abc-clio.com/ODLIS/odlis_d.aspx#dividedcatalog), and [online catalog](https://products.abc-clio.com/ODLIS/odlis_o.aspx#onlinecatalog).

### **Charles Ammi Cutter**

Charles Ammi Cutter's name will appear several times throughout this class. Curious to know more? The Wikipedia entry on Cutter is a great place to start: [https://en.wikipedia.org/wiki/Charles\_Ammi\_Cutter](https://en.wikipedia.org/wiki/Charles_Ammi_Cutter)

[![Charles Ammi Cutter](https://upload.wikimedia.org/wikipedia/commons/f/f2/CharlesAmmiCutter_BostonAthenaeum.png)](https://commons.wikimedia.org/wiki/File:CharlesAmmiCutter_BostonAthenaeum.png#/media/File:CharlesAmmiCutter_BostonAthenaeum.png)

These "objects" (today, they would likely be called "objectives") of the catalog were written over 100 years ago by Charles Ammi Cutter, and were a first and very influential attempt at describe the functions of a catalog, so as to identify what needed to be included in surrogate records. This allowed librarians to work backwards and to devise rules about the content they would provide in surrogate records.

**Choice of Content in Bibliographic Records**
----------------------------------------------

The list of objectives devised by Cutter might seem limited today. Why were librarians initially so hesitant to include too much information in a catalog card? Several very practical reasons guide this work:

*   Catalog cards needed to include just enough to meet the needs presented
    *   Too much information took too much time for the cataloger to supply.
        *   The more information there was, the greater the chance for mistakes.
    *   Too much information would not fit on a single card catalog card. Catalog cards are quite small, really.

Information professional found that focusing on the aspects laid out in Cutter's objectives was sufficient, and the objectives guided information professionals for a century.

**Cutter's Objects and Implications for Catalogs**
--------------------------------------------------

Cutter's objects had implications for the functionality of catalogs, whether they were print catalogs or online catalogs. The table below shows some of the implications for the design of the catalog and the content of the surrogate record. Some of the functions listed for systems were not available in card catalogs.

|  **Object**                                                                                                            |  **Implications for system functionality**                                               |  **Implications for surrogate records**                                                                                  |
| --------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| 1\. To enable a person to find any work,<br> whether issued in print or in nonprint<br> format, when one of the following is known: |
| a. The author                                                                                                               | Can browse by author                                                                          | Includes field for author,<br> with names entered in a standardized format                                                        |
| b. The title                                                                                                                | Can browse by title                                                                           | Includes field for title                                                                                                      |
| c. The subject                                                                                                              | Can browse by subject based<br> on a controlled vocabulary, such as LCSH                          | Includes field for<br> subjects                                                                                                   |
| 2\. To show what the library has                                                                                            |
| d. By a given author                                                                                                        | Search results include a comprehensive<br> list of records that meet the criteria                 | Form of name for each author is unique and consistently used                                                                  |
| e. On a given and related subjects                                                                                          | Search results include a comprehensive<br> list of records that meet the criteria                 | Subject terms are assigned consistently and accurately                                                                        |
| f. In a given kind of literature                                                                                            | Ability to limit results by type                                                              | Surrogate<br> record must include this information in a field that can<br> be used for limiting searches or organizing search results |
| 3\. To assist in the choice of a work                                                                                       |
| g. As to the bibliographic edition                                                                                          | Displays edition information in the search results<br> and/or in the display of surrogate records | Includes edition statement                                                                                                    |
| h. As to its character (literary or subject)                                                                                | Displays edition information in the search results<br> and/or in the display of surrogate records | Includes information on literary and subject characteristics                                                                  |


#### **Next**

_Charles A. Cutter contributed a great deal to librarianship in the U.S. The next page continues the exploration of his legacy through the presentation of one of the guiding principles that supported his objectives for a catalog: The principle of user convenience._
<!-- #endregion -->

```python id="SyTh9dGaStQZ"

```

```python id="bY7p4orUSA3x"

```
