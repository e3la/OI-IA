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

<!-- #region id="eNJa2GIBvBvH" -->
# Key Ideas in IR: Measuring Success: Precision and Recall

Imagine you've been using the ERIC database ([https://eric.ed.gov/](https://eric.ed.gov/)) to search for content in the collection. You first used the the thesaurus of descriptors ([https://eric.ed.gov/?ti=all](https://eric.ed.gov/?ti=all)) and found descriptors that fit what you need. You carried out your search, and the three of the results seem perfect.

You wonder, however—are there more results that were overlooked? The video you watched about searching in ERIC mentioned that sometimes items can be relevant, but are not retrieved.

As in the video, you change the limiters of the query, and retrieve three additional articles. Though they are not by the author you wanted, they seem relevant. You now have a total of six articles.

The first query is an example of high precision, but low recall. All three of the original results were really good, but out of all the articles indexed in the database, some other good results were not retrieved.

\*\*\*

Later, you carry out the same search in [Google Scholar](https://scholar.google.com/). You end up with 10 results on the first page, but only two articles are by the author you intended and on the topic you are studying. In this instance, your initial results set had low precision. It might also have had low recall.

## Measuring Success in Retrieval

What do **precision** and **recall** mean? In a database environment, like ERIC, or the databases a library subscribes to, or the library catalog (rather than the entire web), there are a certain number of relevant documents and are often numerous ways for users to query the database. 

#### Measures of Precision

Your results set has high precision if the results all are about what you intend. If you search for Java and want information about the programming language, do the eight results meet your need?  Imagine that they do. In this case, the search had high precision.

\begin{equation*}
\text{precision}=\frac{|\{{Relevant Documents\text\}}\cap\{{Retrieved Documents\text\}}|}{|\{{Retrieved Documents\text\}}|}
\end{equation*}


A measure of the *precision* of search effectiveness can be expressed as the ratio fo relevant records retrieved from a database to the total number of results. For example, a database containing 100 records on the topic of "kittens", the search "kittens" retrieves 50 records, 25 of which are about kittens. This would have a 25/50 precision or relevance ratio.

Now, imagine the opposite scenario—that results you got did not meet your needs. You were looking for information about coffee, and all results pertained to the programming language. In that case, the search would have yielded results that were not relevant. These are called "false drops."


A false drop is when the records retrieved by a search are unrelated to the subject of the search. Often this is because the syntatic requirement of the query is met but hte semantic requirement is not. False drops can occur when results are contingent on the order, library school and school library are the same to many automated searches but not to information professionals. Phrase searching, puting the terms in quotes "school library" can force the words to be in the order you want.

Another example of a false drop would be if you were searching for records about AIDS, as it relates to HIV, and found records about hearing aids, band aids or teaching aids. To avoid that trouble adding a qualifier to the search such as "disease" may work.

Measures of precision, therefore, can be subjective. What is relevant to one person might not be relevant to another. The question of relevance can be difficult to define, because it is subjective, too.

#### Measures of Recall

Out of the entire database of articles, how many of the articles about the island nation did you retrieve? Imagine that in reality there are 60 articles on Java the country, but you only retrieved eight. In that case, your search results were not very thorough and you had very low recall.

\begin{equation*}
\text{recall}=\frac{|\{{Relevant Documents\text\}}\cap\{{Retrieved Documents\text\}}|}{|\{{Relevant Documents\text\}}|}
\end{equation*}

The way that information is organized and searched can have an effect on how high or low the precision of the results is, and how high or low the recall is. As a result, information professionals strive to organize materials to promote precision (see Part II of this class for more information) and they learn how information is stored in a database so that they are more adept at formulating queries that promote high recall.

#### **Next**

_Next, a blog post will reinforce your understanding of these concepts by applying them in a slightly different environment._
<!-- #endregion -->

```python id="Dt5Kjvv8vBvL"

```
