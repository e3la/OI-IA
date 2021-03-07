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

<!-- #region id="m2fX4aXZvihx" -->
# A Short History of Information Retrieval in the Digital Era

## Further Advances in Retrieval

From ancient times, retrieval has been essential to finding information—both to finding documents and to finding information within documents. This page primarily looks at how computer power came to be used to organize and subsequently retrieve documents.

## Documentalism's Role

Information science grew out of the documentalist tradition, and Suzanne Briet was a preeminent documentalist of her time. But why was she (and this movement) so important?

Scholarly articles (as kinds of documents) were increasing in number in the time leading up to WWII, and there were not good ways to manage them. Paper indexes existed, but the most recent articles, not yet represented in the print indexes, were invisible. Scientists needed access to the newest information. This was a problem.

After WWII, [Vannevar Bush](https://www.asist.org/about/history-of-information-science/pioneers-of-information-science/vannevar-bush-2/) dreamed of the [Memex.](https://en.wikipedia.org/wiki/Memex) This started moving the field of documentalism toward information science. Advances in information retrieval drove the move.

## Gerard Salton’s SMART

[Gerard Salton](https://en.wikipedia.org/wiki/Gerard_Salton) developed a retrieval system with a fantastic acronym—[SMART](https://en.wikipedia.org/wiki/SMART_Information_Retrieval_System): System for the Mechanical Analysis and Retrieval of Text—in the United States in the 1960s. Salton identified the [vector-space model](https://en.wikipedia.org/wiki/Vector_space_model) (yes, math) which supported better retrieval in database systems. Databases then did not look like they do today, so this was all very revolutionary! Salton also made use of TF-IDF (term frequency/inverse document frequency) to infer relevance. For example, if in a set of documents the character string “space-c-a-t-s-space” appeared more frequently in one document than in all of the other documents in the set, that document was inferred to be primarily about cats, and therefore most relevant to the query, “cats.”

How relevant search results are achieved has changed over time, too, as seen in the sections below.

## What Is _Relevance_?

Perhaps, not unlike pornography and quality metadata, relevance is one of those things that we know when we see it. Unfortunately, it is also highly personal and context-dependent. The ODLIS defines [relevance](https://www.abc-clio.com/ODLIS/odlis_r.aspx#relevance) as: 

> The extent to which [information](https://www.abc-clio.com/ODLIS/odlis_i.aspx#information) retrieved in a [search](https://www.abc-clio.com/ODLIS/odlis_s.aspx#search) of a [library collection](https://www.abc-clio.com/ODLIS/odlis_l.aspx#libcollec) or other resource, such as an [online catalog](https://www.abc-clio.com/ODLIS/odlis_o.aspx#onlinecatalog) or [bibliographic database](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibdatabase), is judged by the user to be applicable to ("[about](https://www.abc-clio.com/ODLIS/odlis_a.aspx#aboutness)") the [subject](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subject) of the [query](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query). Relevance depends on the searcher's subjective perception of the degree to which the [document](https://www.abc-clio.com/ODLIS/odlis_d.aspx#document) fulfills the [information need](https://www.abc-clio.com/ODLIS/odlis_i.aspx#infoneed), which may or may not have been expressed fully or with precision in the [search statement](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchstatement). Measures of the effectiveness of [information retrieval](https://www.abc-clio.com/ODLIS/odlis_i.aspx#inforetrieval), such as [precision](https://www.abc-clio.com/ODLIS/odlis_p.aspx#precision) and [recall](https://www.abc-clio.com/ODLIS/odlis_r.aspx#recall), depend on the relevance of search results. Compare with [pertinence](https://www.abc-clio.com/ODLIS/odlis_p.aspx#pertinence). **_See also_**: [false drop](https://www.abc-clio.com/ODLIS/odlis_f.aspx#falsedrop) and [relevance ranking](https://www.abc-clio.com/ODLIS/odlis_r.aspx#relevanceranking).

Google deals with relevancy by capturing information about each user and creating a [filter bubble](https://en.wikipedia.org/wiki/Filter_bubble) of information tailor-made for each user. So that for the astronomer, the used-car buyer, and the Latin mythology scholar, different results, in theory, will be displayed for the single-search term “Saturn.” This is both astonishing and frightening at the same time!

## Further Advances through the 1970s

In the 1960s and 1970s, a lot of progress was made in information retrieval and the databases and queries that powered it. [Hans Peter Luhn](https://en.wikipedia.org/wiki/Hans_Peter_Luhn) of IBM invented [KWIC (Key Words In Context)](https://en.wikipedia.org/wiki/Key_Word_in_Context) indexing. With KWIC, the display of search results included more information about the search terms, not unlike Google snippets today… and were organized for browse display based on the words in the query.

Through it all, something was missing. There was progress in dealing with the information explosion and in harnessing the power of computers as they came on the scene, yet…

#### Where Were the End-Users?

By the late 1970s, [Nicholas J. Belkin](https://en.wikipedia.org/wiki/Nicholas_J._Belkin) was giving thought to the users of systems, not just the mechanics of search and retrieval. He identified the [ASK (the anomalous state of knowledge)](https://en.wikipedia.org/wiki/Information_seeking_behavior#Anomalous_state_of_knowledge_%28ASK%29) that the user brings to a retrieval system, and tried to adapt information retrieval to the needs of the users.

Finally, cognitive science was being applied to the problem of information retrieval. Peter Ingwersen and Kalervo Järvelin call this _The Turn_ in their [classic book.](https://www.amazon.com/Turn-Integration-Information-Seeking-Retrieval/dp/140203850X?SubscriptionId=AKIAILSHYYTFIVPWUY6Q&tag=duckduckgo-d-20&linkCode=xm2&camp=2025&creative=165953&creativeASIN=140203850X) And the rest, as they say, is history...

## From the 1980s Onward

Personal computers came along and [punched cards](https://en.wikipedia.org/wiki/Punched_card), used in the earlier data processing systems, were no longer needed for searching.

:::{figure,myclass} punchcard
![Image of a punched card](https://upload.wikimedia.org/wikipedia/commons/f/fe/Used_Punchcard_%285151286161%29.jpg)

{margin}CC-BY [Pete Birkinshaw](https://commons.wikimedia.org/wiki/File:Used_Punchcard_(5151286161).jpg)
:::

As time went on, [graphical user interfaces (GUIs)](https://en.wikipedia.org/wiki/Graphical_user_interface) replaced [command-line interfaces](https://en.wikipedia.org/wiki/Command-line_interface) (still used in some computer programming) and made searching easier and accessible to more users.

Relevance ranking alleviated the need to understand how to apply Boolean operators for searching, though the use of ANDs and ORs are still helpful (system permitting). The ODLIS defines [relevance ranking](https://www.abc-clio.com/ODLIS/odlis_r.aspx#relevanceranking) as: 

> A feature of some [search software](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchsoftware) that [weights](https://www.abc-clio.com/ODLIS/odlis_w.aspx#weighting) the [document](https://www.abc-clio.com/ODLIS/odlis_d.aspx#document)s or [record](https://www.abc-clio.com/ODLIS/odlis_b.aspx#bibrecord)s [retrieved](https://www.abc-clio.com/ODLIS/odlis_i.aspx#inforetrieval) in a [search](https://www.abc-clio.com/ODLIS/odlis_s.aspx#search) according to the degree to which they meet the requirements of the [query](https://www.abc-clio.com/ODLIS/odlis_q.aspx#query). [Ranked](https://www.abc-clio.com/ODLIS/odlis_r.aspx#ranking) results are normally presented in decreasing order of [relevance](https://www.abc-clio.com/ODLIS/odlis_r.aspx#relevance), computed on the basis of the number of occurrences of each [search term](https://www.abc-clio.com/ODLIS/odlis_s.aspx#searchterm) in the document or record, and the weight assigned to the [field](https://www.abc-clio.com/ODLIS/odlis_f.aspx#field)(s) in which each term appears ([title](https://www.abc-clio.com/ODLIS/odlis_t.aspx#title), [subject headings](https://www.abc-clio.com/ODLIS/odlis_s.aspx#subjectheading), [abstract](https://www.abc-clio.com/ODLIS/odlis_a.aspx#abstract), or [full-text](https://www.abc-clio.com/ODLIS/odlis_f.aspx#fulltext)).

And on the web… Yahoo! (a [web directory ](https://en.wikipedia.org/wiki/Web_directory)organized by users) showed that the early web could be described. Google (a [web search engine ](https://en.wikipedia.org/wiki/Web_search_engine)making use of the [PageRank](https://en.wikipedia.org/wiki/PageRank) algorithm) showed it could be indexed and searched.

All of these advances in IR have led to the user-friendly search mechanisms in use today, ones that users in information agencies know and like.

#### **Next**

_The rest of the pages in this Module focus on key concepts in IR/IO._

_The next page looks at key concepts related to databases. Why? The answer, quite simply, is that computerized retrieval tools rely largely on databases. For information to be retrievable, information intermediaries must first understand some basics about databases, including their structure and how they are designed._
<!-- #endregion -->

```python id="0x7RLRXtvih3"

```
