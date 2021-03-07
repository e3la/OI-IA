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

<!-- #region id="lWxIMazJufDs" -->

<!-- #endregion -->

<!-- #region id="NHxKj9UQufDx" -->
# Module 2. For Further Study


 **![](recommend-icon.png) For Further Study**

> Bush, V. (1945). As we may think. _The Atlantic Monthly, 176_(1), p. 101–108. [https://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/](https://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/)

#### Notes

*   Quintessential historical perspective on what the future of search (and research) might be. Bush was working for the U.S. government during World War II and was working to support research.
*   Read more about Bush—including about his subsequent work at MIT and all the rest—on Wikipedia: [https://en.wikipedia.org/wiki/Vannevar\_Bush](https://en.wikipedia.org/wiki/Vannevar_Bush)
*   ![Portrait of Vannevar Bush (from Wikipedia)](https://upload.wikimedia.org/wikipedia/commons/e/ea/Vannevar_Bush_portrait.jpg)

* * *

> CS 276 / LING 286: Information retrieval and web search. [https://web.stanford.edu/class/cs276](https://web.stanford.edu/class/cs276)

#### Notes

*   This course site will give you a view of information retrieval from the perspective of computer science. It is much more technical!
*   From this perspective, components of an information retrieval system include tiered indexes, query-term proximation, and designing, parsing and scoring functions.

* * *

#### **Term Frequency/Inverse Document Frequency**

Relating to retrieval algorithms supporting relevance, one of the essential notions is that of term frequency/inverse document frequency (TF/IDF). What does this mean?

In a set of documents (like a database—ERIC, for instance), an algorithm can be trained to identify documents based on the the full text (not the metadata) and the uniqueness of the words. Any document in English will contain the word "the"—but if a document contains the word "cats" 15 times, and is the only document out of 100 documents to contain the word "cats" the frequency in the document is high, compared to the frequency in the other documents, which is low (zero, in this case) so that document is the most relevant to the query "cats."

#### Notes

*   See this website for some additional information about TF/IDF: [http://www.tfidf.com/](http://www.tfidf.com/)
*   For more specifics, including how to calculate, along with a nice bibliography of IR texts of interest: [http://www.tfidf.com/](http://www.tfidf.com/)

* * *

> Philbin, C.A. (2017, August 2). Keyboards & command line interfaces: crash course computer science #22 \[Video\]. YouTube. [https://www.youtube.com/watch?v=4RPtJ9UyHS0](https://www.youtube.com/watch?v=4RPtJ9UyHS0)

#### Notes

*   An interesting 11.25 minute video if you are interested in the history of computers. The concepts do not related directly to topics in the class, other than to give you an understanding of how sophisticated our systems today are in comparison to how computers operated even thirty years ago. 
*   Covers the evolution of computer input mechanisms, including the command line interface which was mentioned in this module.
*   Part of CrashCourse. The energetic instructor and a lot of images make this an interesting and informative video.
*   If you are really interested, follow-up with the next video in the series, which covers computer screens and 2D graphics: [https://www.youtube.com/watch?v=7Jr0SFMQ4Rs](https://www.youtube.com/watch?v=7Jr0SFMQ4Rs) 
<!-- #endregion -->

```python id="mW-f8YxFufDy"

```
