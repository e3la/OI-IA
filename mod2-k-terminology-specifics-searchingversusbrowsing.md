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

# Terminology Specifics: Searching versus Browsing

Retrieval tools allow for different approaches to finding content in a system like a database. IO and IR have a very precise terminology for how users interact with these tools.

Unfortunately, these terms may be used in everyday language and in interactions with retrieval tools is a less precise and slightly different way.

This means that, as an information professional, you need to be "bilingual"—you need to understand how these terms are used in IO/IR, but also understand that your users and clients will probably mean different things when they use these terms. One of the challenges of the information professions is to act as a go-between.

## Search Query

In this context, the ODLIS defines [query](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query) as:

> A request submitted as [input](https://www.abc-clio.com/ODLIS/odlis_i.aspx#input) in a [search](https://www.abc-clio.com/ODLIS/odlis_s.aspx#search) of an [online catalog ](https://www.abc-clio.com/ODLIS/odlis_o.aspx#onlinecatalog)or [bibliographic database](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibdatabase) to [retrieve](https://www.abc-clio.com/ODLIS/odlis_i.aspx#inforetrieval) [records](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibrecord) or [documents](https://www.abc-clio.com/ODLIS/odlis_d.aspx#document) [relevant](https://www.abc-clio.com/ODLIS/odlis_r.aspx#relevance) to the user's [information need(s)](https://www.abc-clio.com/ODLIS/odlis_i.aspx#infoneed). Some [information storage and retrieval](https://www.abc-clio.com/ODLIS/odlis_i.aspx#isar) systems allow queries to be submitted in [natural language](https://www.abc-clio.com/ODLIS/odlis_n.aspx#naturallang), but most systems require the user to formulate [search statements](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchstatement) in the [artificial language](https://www.abc-clio.com/ODLIS/odlis_a.aspx#artificiallang) used for [indexing](https://www.abc-clio.com/ODLIS/odlis_i.aspx#indexinglang) and in [syntax](https://www.abc-clio.com/ODLIS/odlis_s.aspx#syntax) acceptable to the [search software](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchsoftware). The query is an approximation of the information need that provides the impetus for the search.

What does this mean? Essentially, the user types something into the retrieval tool's search interface. The interface being used is the [search software](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchsoftware):

> A [computer program](https://www.abc-clio.com/ODLIS/odlis_c.aspx#computerprogram) designed to execute a [search](https://www.abc-clio.com/ODLIS/odlis_s.aspx#search) for [information](https://www.abc-clio.com/ODLIS/odlis_i.aspx#information) when [queried](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query) by a user. [User-friendly](https://www.abc-clio.com/ODLIS/odlis_u.aspx#userfriendly) search [software](https://www.abc-clio.com/ODLIS/odlis_s.aspx#software) provides both a [menu-driven](https://www.abc-clio.com/ODLIS/odlis_m.aspx#menudriven) [interface](https://www.abc-clio.com/ODLIS/odlis_i.aspx#interface) for [novices](https://www.abc-clio.com/ODLIS/odlis_n.aspx#novice) and a [command-driven](https://www.abc-clio.com/ODLIS/odlis_c.aspx#commanddriven) interface for experienced searchers. Sophisticated search software permits the use of [Boolean](https://www.abc-clio.com/ODLIS/odlis_b.aspx#boolean) logic, [nesting](https://www.abc-clio.com/ODLIS/odlis_n.aspx#nesting), [truncation](https://www.abc-clio.com/ODLIS/odlis_t.aspx#truncation), [wildcard](https://www.abc-clio.com/ODLIS/odlis_w.aspx#wildcard), and [proximity](https://www.abc-clio.com/ODLIS/odlis_p.aspx#proximity) operators in [search statement](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchstatement)s and allows the user to [limit](https://www.abc-clio.com/ODLIS/odlis_l.aspx#limiting) search results by various [parameters](https://www.abc-clio.com/ODLIS/odlis_p.aspx#parameter). Compare with [search engine](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchengine). **_See also_**: [functionality](https://www.abc-clio.com/ODLIS/odlis_f.aspx#functionality).

What is entered into the retrieval tool's search engine using the keyboard is the [search term](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchterm): 

> A word or [phrase](https://www.abc-clio.com/ODLIS/odlis_p.aspx#phrase) representing one of the main concepts in a [research](https://www.abc-clio.com/ODLIS/odlis_r.aspx#research) [topic](https://www.abc-clio.com/ODLIS/odlis_t.aspx#topic), used alone or in combination with other [terms](https://www.abc-clio.com/ODLIS/odlis_t.aspx#term) in a [search statement](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchstatement), to [query](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query) an [online catalog](https://www.abc-clio.com/ODLIS/odlis_o.aspx#onlinecatalog), [bibliographic database](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibdatabase), or [search engine](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchengine) and [retrieve](https://www.abc-clio.com/ODLIS/odlis_i.aspx#inforetrieval) [relevant](https://www.abc-clio.com/ODLIS/odlis_r.aspx#relevance) [information](https://www.abc-clio.com/ODLIS/odlis_i.aspx#information). A search term can be a [keyword](https://www.abc-clio.com/ODLIS/odlis_jk.aspx#keywords) or phrase supplied by the user, an authorized [subject heading](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subjectheading) or [descriptor](https://www.abc-clio.com/ODLIS/odlis_d.aspx#descriptor) selected from a prescribed list, or a word or phrase found in a [thesaurus](https://www.abc-clio.com/ODLIS/odlis_t.aspx#thesaurus), for example, _The Contemporary Thesaurus of Search Terms and Synonyms_ by Sara Knapp (Oryx, 2000).

Sometimes a query can include more than just words, though. Often, to yield more precise results, specific indexes are searched (e.g., the search term only appears in the title) or the results are limited in some way (e.g., to a certain date range).  The search terms plus other strategies yield the [search ](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchstatement) [statement](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchstatement):

> In [information retrieval](https://www.abc-clio.com/ODLIS/odlis_i.aspx#inforetrieval), an [information need](https://www.abc-clio.com/ODLIS/odlis_i.aspx#infoneed) or [query](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query) entered as [input](https://www.abc-clio.com/ODLIS/odlis_i.aspx#input) in a form acceptable to the [search software](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchsoftware) used by the retrieval system. Most [online catalogs](https://www.abc-clio.com/ODLIS/odlis_o.aspx#onlinecatalog), [bibliographic databases](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibdatabase), and [search engines](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchengine) allow [Boolean](https://www.abc-clio.com/ODLIS/odlis_b.aspx#boolean) logic, [nesting](https://www.abc-clio.com/ODLIS/odlis_n.aspx#nesting), [truncation](https://www.abc-clio.com/ODLIS/odlis_t.aspx#truncation), [wildcard](https://www.abc-clio.com/ODLIS/odlis_w.aspx#wildcard), and [proximity](https://www.abc-clio.com/ODLIS/odlis_p.aspx#proximity) operators to be used in [keyword(s)](https://www.abc-clio.com/ODLIS/odlis_jk.aspx#keywords) [search](https://www.abc-clio.com/ODLIS/odlis_s.aspx#search) statements and permit the user to [limit](https://www.abc-clio.com/ODLIS/odlis_l.aspx#limiting) search results. **_See also_**: [controlled vocabulary](https://www.abc-clio.com/ODLIS/odlis_c.aspx#controlled) and [natural language](https://www.abc-clio.com/ODLIS/odlis_n.aspx#naturallang).

All told, even though the term "search" can show up in a number of places in everyday language (from searching for your keys, to Madonna's [I Don't Search, I Find](https://en.wikipedia.org/wiki/I_Don't_Search_I_Find)), IO (and IR) mean something very precise. Will you be surprised to learn that the term _browse_ is no different in that regard? 

## Browse

The ODLIS has a great definition for [browse](https://www.abc-clio.com/ODLIS/odlis_b.aspx#browse) that really captures the nuances of how the term is used by different groups and in different circumstances. 

> To look through a [library](https://www.abc-clio.com/ODLIS/odlis_l.aspx#library) [collection](https://www.abc-clio.com/ODLIS/odlis_l.aspx#libcollec), [catalog](https://www.abc-clio.com/ODLIS/odlis_c.aspx#catalog), [bibliography](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibliography), [index](https://www.abc-clio.com/ODLIS/odlis_i.aspx#index), [bibliographic database](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibdatabase), or other [finding tool](https://www.abc-clio.com/ODLIS/odlis_f.aspx#findingtool) in a casual [search](https://www.abc-clio.com/ODLIS/odlis_s.aspx#search) for [item](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibitem)s of interest, **without clearly defined intentions \[_emphasis, ours_\]**. To facilitate browsing, libraries assign similar [call numbers](https://www.abc-clio.com/ODLIS/odlis_c.aspx#callnumber) to items on the same [subject](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subject), which groups them together on the [shelf](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bookshelves).  
>   
> In [information retrieval](https://www.abc-clio.com/ODLIS/odlis_i.aspx#inforetrieval), to conduct a directed search in a dynamic but casual way. A clearly formulated [query](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query) may determine the initial point of entry into an index or [database](https://www.abc-clio.com/ODLIS/odlis_d.aspx#database), but searches that begin systematically often give way to an exploratory approach as new [terminology](https://www.abc-clio.com/ODLIS/odlis_t.aspx#terminology) is revealed by the results retrieved. Some researchers consider [printed](https://www.abc-clio.com/ODLIS/odlis_p.aspx#printing) indexes to be more [browsable](https://www.abc-clio.com/ODLIS/odlis_b.aspx#browsability) than **electronic databases because [page](https://www.abc-clio.com/ODLIS/odlis_p.aspx#page) [format](https://www.abc-clio.com/ODLIS/odlis_f.aspx#format) allows the user to scan with ease the [heading](https://www.abc-clio.com/ODLIS/odlis_h.aspx#heading)s and [entries](https://www.abc-clio.com/ODLIS/odlis_e.aspx#entry) that precede and follow the initial [point of access](https://www.abc-clio.com/ODLIS/odlis_a.aspx#accesspoint) \[_emphasis, ours_\].**  
>   
> **Also, to search for [information](https://www.abc-clio.com/ODLIS/odlis_i.aspx#information) available on the [World Wide Web](https://www.abc-clio.com/ODLIS/odlis_w.aspx#www) in a casual, [serendipitous](https://www.abc-clio.com/ODLIS/odlis_s.aspx#serendipity) manner \[_emphasis, ours_\].** [Hypertext](https://www.abc-clio.com/ODLIS/odlis_h.aspx#hypertext) is designed to facilitate [online](https://www.abc-clio.com/ODLIS/odlis_o.aspx#online) browsing by providing embedded [links](https://www.abc-clio.com/ODLIS/odlis_l.aspx#link) to related [documents](https://www.abc-clio.com/ODLIS/odlis_d.aspx#document) and [electronic resources](https://www.abc-clio.com/ODLIS/odlis_e.aspx#eresource) (this online [dictionary](https://www.abc-clio.com/ODLIS/odlis_d.aspx#dictionary) is an example). Compare with [surf](https://www.abc-clio.com/ODLIS/odlis_s.aspx#surf). **_See also_**: [Web browser](https://www.abc-clio.com/ODLIS/odlis_w.aspx#webbrowser).

In the first definition, _browse_ is used interchangeably with _search_ to mean _look for_ in any number of contexts. This is a great natural language use of this term, and is probably the kind of terminology most users will employ. 

In the second definition, the IO/IR definition, browse is what a user does after entering the search query in an interface that allows for further navigation or exploration. This is, again, within the context of IR, so search software has been used to launch a query in a retrieval tool (probably a database of some kind).

The final definition of _browse_ is the one most users will employ when talking about their interactions with the Web. It's similar to the IR meaning of the term, but the Web isn't a retrieval tool in the same way a museum catalog is, for example, so the browsing capabilities are different. 

#### **Next**

_The next page will help you get more of a handle on what is meant by "browse" in the information professions from the IO/IR perspective._

```python

```
