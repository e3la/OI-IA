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
    language: python
    name: python3
---

# Key Ideas in IR: Controlled Vocabularies and Thesauri

## Controlled Vocabularies

Certain fields in databases may contain information that must be formatted in a certain way. Contacts in a phone include information about a person, such as name, phone number, etc. Some Contacts might only allow calendar dates to be entered in the Birthday field of a record for a friend, or digits to appear in the phone number field.

Information agencies do something similar when they provide searchable content in a field from a controlled vocabulary such as the Library of Congress Subject Headings (LCSH) or the name authorities. Only terms from the controlled vocabulary may be included. In the example above, there are 12 months from which to choose for date information. In information agencies, controlled vocabularies provide similar lists of allowed information. Usually, instead of months, controlled vocabularies are lists of topics a book might be about, or names of authors (often with the last name first), or genres (e.g., Westerns, etc.). These controlled vocabularies are created by organizations and are added to records by information professionals. 

The ODLIS defines [controlled vocabulary ](https://www.abc-clio.com/ODLIS/odlis_c.aspx#controlledvocabulary) in the following way:

> An established list of [preferred terms](https://www.abc-clio.com/ODLIS/odlis_p.aspx#preferredterm) from which a [cataloger](https://www.abc-clio.com/ODLIS/odlis_c.aspx#cataloger) or indexer must select when assigning [subject headings](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subjectheading) or [descriptors](https://www.abc-clio.com/ODLIS/odlis_d.aspx#descriptor) in a [bibliographic record](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibrecord), to indicate the [content](https://www.abc-clio.com/ODLIS/odlis_c.aspx#content) of the [work](https://www.abc-clio.com/ODLIS/odlis_w.aspx#work) in a [library](https://www.abc-clio.com/ODLIS/odlis_l.aspx#library) [catalog](https://www.abc-clio.com/ODLIS/odlis_c.aspx#catalog), [index](https://www.abc-clio.com/ODLIS/odlis_i.aspx#index), or [bibliographic database](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibdatabase). [Synonyms](https://www.abc-clio.com/ODLIS/odlis_s.aspx#synonym) are included as [lead-in vocabulary](https://www.abc-clio.com/ODLIS/odlis_l.aspx#leadinvocabulary), with instructions to _[see](https://www.abc-clio.com/ODLIS/odlis_s.aspx#see)_ or [USE](https://www.abc-clio.com/ODLIS/odlis_u.aspx#use) the authorized [heading](https://www.abc-clio.com/ODLIS/odlis_h.aspx#heading). For example, if the authorized subject heading for [works](https://www.abc-clio.com/ODLIS/odlis_w.aspx#work) about dogs is "Dogs," then all [items](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibitem) about dogs will be assigned the heading "Dogs," including a work [title](https://www.abc-clio.com/ODLIS/odlis_t.aspx#title)d _All about Canines_. A [cross-reference](https://www.abc-clio.com/ODLIS/odlis_c.aspx#crossreference) to the heading "Dogs" will be made from the [term](https://www.abc-clio.com/ODLIS/odlis_t.aspx#term) "Canines" to ensure that anyone looking for [information](https://www.abc-clio.com/ODLIS/odlis_i.aspx#information) about dogs under "Canines" will be directed to the correct heading. [Controlled](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authoritycontrol) [vocabulary](https://www.abc-clio.com/ODLIS/odlis_v.aspx#vocabulary) is usually listed [alphabetically](https://www.abc-clio.com/ODLIS/odlis_a.aspx#alphabetical) in a subject headings list or [thesaurus](https://www.abc-clio.com/ODLIS/odlis_t.aspx#thesaurus) of indexing terms. The process of creating and maintaining a list of preferred [indexing](https://www.abc-clio.com/ODLIS/odlis_i.aspx#indexing) [terms](https://www.abc-clio.com/ODLIS/odlis_t.aspx#term) is called [vocabulary control](https://www.abc-clio.com/ODLIS/odlis_v.aspx#vocabcontrol).  
>   
> The utility of controlled vocabulary in the [online](https://www.abc-clio.com/ODLIS/odlis_o.aspx#online) environment has been challenged, but a study by Tina Gross and Arlene G. Taylor (_College & Research Libraries_, May 2005) found that more than one-third of records retrieved by successful [keywords](https://www.abc-clio.com/ODLIS/odlis_jk.aspx#keywords) searches in [OPACs](https://www.abc-clio.com/ODLIS/odlis_o.aspx#opac) \[online catalogs\] would be lost if subject headings were not present, and for some searches the loss was as high as 80-100 percent. Synonymous with _controlled terms_. Compare with [free-text search](https://www.abc-clio.com/ODLIS/odlis_f.aspx#freetextsearch).

As easy as it is to search Amazon and get good results, results may not yield desired results since there are not controlled vocabularies in use—not like in libraries. This search for "Delia Owens" in Amazon Books yielded a results list in which the first hit was for a book by Mark James Owens and Cordelia Dykes Owens. That, despite the fact that the query terms were "delia owens"—in quotes.

![Amazon top results "Delia Owens" in Books](https://missouri.instructure.com/courses/45003/files/7748364/preview)

### Thesaurus

In information retrieval, a _thesaurus_ of descriptors can be used as a controlled vocabulary. As with _fields_ and _browse_, _thesaurus_ can mean a lot of different things in LIS, but luckily, it only means one thing in IR!

Wikipedia tells us the following about thesauri used in IR databases, and about the information professionals who use them when carrying out organization of information.

Thesaurus (information retrieval) [https://en.wikipedia.org/wiki/Thesaurus\_(information\_retrieval)](https://en.wikipedia.org/wiki/Thesaurus_(information_retrieval)):

> In the context of [information retrieval](https://en.wikipedia.org/wiki/Information_retrieval "Information retrieval"), a **thesaurus** (plural: "thesauri") is a form of [controlled vocabulary](https://en.wikipedia.org/wiki/Controlled_vocabulary "Controlled vocabulary") that seeks to dictate semantic manifestations of [metadata](https://en.wikipedia.org/wiki/Metadata "Metadata") in the indexing of content objects. ...  
> A thesaurus serves to guide both an indexer and a searcher in selecting the same preferred term or combination of preferred terms to represent a given subject. [ISO 25964](https://en.wikipedia.org/wiki/ISO_25964 "ISO 25964"), the international standard for information retrieval thesauri, defines a thesaurus as a “controlled and structured vocabulary in which concepts are represented by terms, organized so that relationships between concepts are made explicit, and preferred terms are accompanied by lead-in entries for synonyms or quasi-synonyms.”

_Thesaurus_ is definitely one of those terms that means a lot of things to a lot of different people. For now, understand that thesauri are used to support information retrieval in databases, and the descriptors are controlled vocabulary terms that information professionals use in organizing content.

Revisit the ERIC database example and consider the tab labeled "thesaurus" above the search box: [https://eric.ed.gov/ ](https://eric.ed.gov/)

Users know the correct descriptor by first searching the thesaurus for the idea they are researching, and then they launch queries using the descriptors in order get a better, more precise result set. 

### ![](https://missouri.instructure.com/courses/45003/files/7748329/download)  
**Now This**

*   Look at the thesaurus for the ERIC database: [https://eric.ed.gov/?ti=all](https://eric.ed.gov/?ti=all)
*   Which descriptor would you choose if you wanted to help a patron wanting articles on "[Racial Prejudice](https://eric.ed.gov/?ti=Racial+Prejudice)"?

**NOTE:** _This is VERY tricky, because [Racial Prejudice](https://eric.ed.gov/?ti=Racial+Prejudice) is not a descriptor!_

```python

```
