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
# Key Ideas in IO: KOSs

In Module 2, a number of key notions in information retrieval were presented. It is worth returning to these key notions now to take a closer look at how they fit together.

**Knowledge Organization Systems (KOSs)**
-----------------------------------------

Hodge (2000) describes KOSs in the introduction to the CLIR report on KOSs in digital library environments. She writes:

> The term _knowledge organization systems_ is intended to encompass all types of schemes for organizing information and promoting knowledge management[1](https://www.clir.org/pubs/reports/pub91/1knowledge/#1). Knowledge organization systems include classification schemes that organize materials at a general level (such as books on a shelf), subject headings that provide more detailed access, and authority files that control variant versions of key information (such as geographic names and personal names). They also include less-traditional schemes, such as semantic networks and ontologies. Because knowledge organization systems are mechanisms for organizing information, they are at the heart of every library, museum, and archive.  
> Knowledge organization systems are used to organize materials for the purpose of retrieval and to manage a collection. A KOS serves as a bridge between the user’s information need and the material in the collection. With it, the user should be able to identify an object of interest without prior knowledge of its existence. Whether through browsing or direct searching, whether through themes on a Web page or a site search engine, the KOS guides the user through a discovery process. In addition, KOSs allow the organizers to answer questions regarding the scope of a collection and what is needed to round it out.

Wikipedia ([https://en.wikipedia.org/wiki/Knowledge\_organization\_system](https://en.wikipedia.org/wiki/Knowledge_organization_system)) tells us the following:

> **Knowledge Organization Systems** (**KOS**), **concept system** or **concept scheme** is a [generic term](https://en.wikipedia.org/wiki/Generic_term "Generic term") used in [knowledge organization](https://en.wikipedia.org/wiki/Knowledge_organization "Knowledge organization") about [authority files](https://en.wikipedia.org/wiki/Authority_file "Authority file"), [classification schemes](https://en.wikipedia.org/wiki/Classification_scheme "Classification scheme"), [thesauri](https://en.wikipedia.org/wiki/Thesaurus_(information_retrieval) "Thesaurus (information retrieval)"), [topic maps](https://en.wikipedia.org/wiki/Topic_maps "Topic maps"), [ontologies](https://en.wikipedia.org/wiki/Ontology_(information_science) "Ontology (information science)") etc.

You have already seen the entry for Knowledge organization in Wikipedia, as well as the one for Thesaurus (information retrieval) . What about these others, though? Let's start with authority file (though—you should feel free to look through all the Wikipedia pages before continuing)—below, we look at these from a specifically LIS point of view.

**Authority Files**
-------------------

The concept of "authority files" may seem intimidating. It is just a database in which  librarians store information about how they want to enter particular pieces of data into a field in a surrogate record.

The ODLIS defines [authority files](https://products.abc-clio.com/ODLIS/odlis_about.aspx#authorityfile) in the following way:

> [**authority file**](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authorityfile)  
> A list of the [authoritative](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authoritative) forms of the [headings](https://www.abc-clio.com/ODLIS/odlis_h.aspx#heading) used in a [library](https://www.abc-clio.com/ODLIS/odlis_l.aspx#library) [catalog](https://www.abc-clio.com/ODLIS/odlis_c.aspx#catalog) or [file](https://www.abc-clio.com/ODLIS/odlis_f.aspx#file) of [bibliographic records](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibrecord), maintained to ensure that headings are applied [consistently](https://www.abc-clio.com/ODLIS/odlis_c.aspx#consistency) as new [items](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibitem) are added to the [collection](https://www.abc-clio.com/ODLIS/odlis_l.aspx#libcollec). Separate authority files are usually maintained for [names](https://www.abc-clio.com/ODLIS/odlis_n.aspx#nameauthority), [uniform titles](https://www.abc-clio.com/ODLIS/odlis_u.aspx#uniformtitle), [series titles](https://www.abc-clio.com/ODLIS/odlis_s.aspx#seriestitle), and [subjects](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subjectheading). All the references made to and from a given heading are also included in the file. **_See also_**: [authority control](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authoritycontrol).

#### Authority Records

Now that you know the terminology a little, you probably will not be surprised to learn that authority files, which are databases, are searchable collections of authority records. Per the ODLIS, [authority records](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authorityrecord) are the following:

> [**authority record**](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authorityrecord)  
> A [printed](https://www.abc-clio.com/ODLIS/odlis_p.aspx#printing) or [machine-readable](https://www.abc-clio.com/ODLIS/odlis_m.aspx#machinereadable) [record](https://www.abc-clio.com/ODLIS/odlis_r.aspx#record) of the decision made concerning the [authoritative](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authoritative) form of a name ([personal](https://www.abc-clio.com/ODLIS/odlis_p.aspx#personalname) or [corporate](https://www.abc-clio.com/ODLIS/odlis_c.aspx#corporatename)), [uniform title](https://www.abc-clio.com/ODLIS/odlis_u.aspx#uniformtitle), [series title](https://www.abc-clio.com/ODLIS/odlis_s.aspx#seriestitle), or [subject](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subjectheading) used as a [heading](https://www.abc-clio.com/ODLIS/odlis_h.aspx#heading) in a [library](https://www.abc-clio.com/ODLIS/odlis_l.aspx#library) [catalog](https://www.abc-clio.com/ODLIS/odlis_c.aspx#catalog) or [file](https://www.abc-clio.com/ODLIS/odlis_f.aspx#file) of [bibliographic record](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibrecord)s, listed in an [authority file](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authorityfile) governing the application of headings to new [item](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibitem)s as they are added to the [library collection](https://www.abc-clio.com/ODLIS/odlis_l.aspx#libcollec). An authority record may also contain _See from_ and _See also from_ records, as well as notes concerning the application of the authorized form. [Click here](http://authorities.loc.gov/) to connect to _Library of Congress Authorities_, a [searchable](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchable) [database](https://www.abc-clio.com/ODLIS/odlis_d.aspx#database) of [authority](https://www.abc-clio.com/ODLIS/odlis_a.aspx#authoritycontrol) headings. **_See also_**: [_Functional Requirements for Authority Data (FRAD)_](https://www.abc-clio.com/ODLIS/odlis_f.aspx#frad).

So far, the "records" in library catalogs have been surrogates that stand in for a book, etc. Authority records are very different! 

Authority records establish the way, for example, an author's name will be included _in the surrogate_. This is complex, but luckily, database technology allows for surrogates to make use of information recorded in authority records, especially to help pull together—or _collocate_—all the works by a given author. 

#### Value added cataloging

View the results of an author browse search in MERLIN for [Richardson, T. ](http://merlin.lib.umsystem.edu/search~S8/?searchtype=a&searcharg=richardson%2C+t)

A goal in cataloging is to provide a unique form of name for each person. As you scroll through the list of the search results, you will see some of the conventions used to achieve this. Some names include birth and/or death dates (Richardson, Thomas, 1816–1867). Others include a middle initial or a middle name (Richardson, Thomas R.). When those pieces of information are unknown or are not enough to construct a unique form of the name, an occupation may be added (Richardson, Ted (Musician)). The unique form is documented in an authority record, so that other catalogers will use that same form of name.

Consider the value(s) this practice provides for users.

#### Example Authority File and Record Exercise: LCNAF

Let's consider a specific example of an authority record. The Library of Congress Name Authority File ([LCNAF](http://id.loc.gov/authorities/names.html)) helps librarians figure out how to provide author names in the author name field of a bibliographic record.

### ![](https://missouri.instructure.com/courses/45003/files/7748332/download)  
**Exercise**

Search in the LCNAF database ([http://id.loc.gov/authorities/names.html](http://id.loc.gov/authorities/names.html)) for the entry (i.e., for the record) for Lady Gaga. You know already that librarians usually enter names Lastname, Firstname (dates). So what did they do with Lady Gaga, who doesn't go by a last name?

**HINT:** Look at the snippets in the result set under "Label" to see which form of the name librarians will use based on this authority file. Click on the result to open the authority record for Lady Gaga.

**When you're ready, click Next to see the answer on the following page.**

* * *

#### Reference

Hodge, G. (2000). _Systems of knowledge organization for digital libraries: Beyond traditional authority files_. CLIR.  . [https://www.clir.org/pubs/reports/pub91/](https://www.clir.org/pubs/reports/pub91/)
<!-- #endregion -->
