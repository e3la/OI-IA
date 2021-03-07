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

<!-- #region id="t0JVq8EelFkH" -->
Key Ideas in IO: Vocabulary Control
===================================

**Vocabulary Control in Action: Subject Headings**
--------------------------------------------------

The searching you just did of the full-text of digital resources and the experimentation with natural language queries is the search style common to many, many users of information systems, who probably have not reflected on these processes as you are learning to do!

This section changes focus, to look instead at how retrieval systems in information agencies tend to organize materials for _aboutness_: using controlled vocabularies.

You are probably familiar with subject headings used in libraries, and already in this OER you have looked at library catalogs that include subject headings. Look at the surrogate  record in Figure 1. Figure 1 is a surrogate record in the online catalog of the Library of Congress. Library of Congress Subject Headings (LCSH) are provided, as well as a lot of other _descriptive metadata_ to help users find, identify, select, and obtain this resource.

LCSH is an example of a controlled vocabulary. The subject headings are clearly marked (i.e., LC Subjects) in Figure 1 and are circled in red.

**Q: How did these long strings of terms come to be associated with this surrogate?**

A: These subject headings are from a _controlled vocabulary_ and were assigned by an information professional.

**Figure 1** **Sample Catalog Record from the** **Library** **of Congress Catalog, with the LCSH Terms Circled**

[![LC Catalog—Record with LC Subjects](https://missouri.instructure.com/courses/49361/files/8633275/preview)](https://lccn.loc.gov/2016053518)

_Note._ Retrieved from [https://catalog.loc.gov/vwebv/search?searchCode=LCCN&searchArg=2016053518&searchType=1&permalink=y](https://catalog.loc.gov/vwebv/search?searchCode=LCCN&searchArg=2016053518&searchType=1&permalink=y). 

#### Controlling Vocabulary?

As with many terms in this class, _vocabulary control_ is a term of art—it is jargon specific to the field with a very specific meaning.

Take a look at the definition of [vocabulary control](https://products.abc-clio.com/ODLIS/odlis_v.aspx#vocabcontrol) in the ODLIS.

> In [indexing](https://products.abc-clio.com/ODLIS/odlis_i.aspx#indexing), the process of creating and maintaining a list of [preferred terms](https://products.abc-clio.com/ODLIS/odlis_p.aspx#preferredterm) to indicate (1) which of two or more equivalent terms will represent a concept as the authorized [subject heading](https://products.abc-clio.com/ODLIS/odlis_s.aspx#subjectheading) or [descriptor](https://products.abc-clio.com/ODLIS/odlis_d.aspx#descriptor) in the [classification system](https://products.abc-clio.com/ODLIS/odlis_c.aspx#classificationsys) and (2) the relations of [hierarchy](https://products.abc-clio.com/ODLIS/odlis_h.aspx#hierarchicalclass) ([broader](https://products.abc-clio.com/ODLIS/odlis_b.aspx#broaderterm) and [narrower terms](https://products.abc-clio.com/ODLIS/odlis_n.aspx#narrowerterm)) and [association](https://products.abc-clio.com/ODLIS/odlis_a.aspx#associative) ([related terms](https://products.abc-clio.com/ODLIS/odlis_r.aspx#relatedterm)) among [headings](https://products.abc-clio.com/ODLIS/odlis_h.aspx#heading) once they have been selected. [Controlled vocabulary](https://products.abc-clio.com/ODLIS/odlis_c.aspx#controlled) is recorded in a subject headings list or [thesaurus](https://products.abc-clio.com/ODLIS/odlis_t.aspx#thesaurus) that is [updated](https://products.abc-clio.com/ODLIS/odlis_u.aspx#updated) as new concepts emerge and older [terminology](https://products.abc-clio.com/ODLIS/odlis_t.aspx#terminology) becomes obsolete. Compare with [authority control](https://products.abc-clio.com/ODLIS/odlis_a.aspx#authoritycontrol).

Controlling _vocabulary_ (i.e. words) does not come naturally, but does support information retrieval, especially recall. Controlling vocabulary is something information professionals learn to do, and controlled vocabularies are something they learn to use.

As a minor aside, we refer to "natural language" as being the opposite of "controlled vocabularies."

**Controlling Vocabulary: Why?**
--------------------------------

Here are two easy scenarios to get you started.

### **Scenario 1**

_What do you mean by “frames”?_

*   Frames can mean many things (the word for this is [polysemy](https://en.wikipedia.org/wiki/Polysemy))
*   If you are working in an art museum, the artworks will all have _frames_.
*   If you have an interest in architecture, you might be interested in the _frame_ of a structure.
*   If you are describing cartoon strips, you will need to describe each _frame._
*   If you If you wear glasses, you purchase _frames_ for them.
*   If you are a bowling aficionado, you will be interested in the scores earned in each _frame_.
*   The list goes on and on!

This is the problem of polysemy. One "character string" (a set of letters/spaces appearing together) may mean many things! A spontaneous interpretation will depend on the viewer. BUT! This is a huge problem for retrieval!

As an information professional, how can you ensure [recall](https://en.wikipedia.org/wiki/Precision_and_recall) (remember that concept?) if a single search term input by your end-users can mean many things?

### **Scenario 2**

Q: _What do you call  [![Panoz Roadster](https://live.staticflickr.com/57/204620564_e209385237_n.jpg)](https://www.flickr.com/photos/nateone/204620564/in/photolist-j5JyL-zbDjXS-DsGVgc-6kAGAd-azeTPP-6e2MMk-dWpXjq-8J5Aey-DKZPTQ-fuAqGg-DNaE58-2gfqmrJ-Gpyx3M-4gSNdx-xpVuqy-5a81YP-upMyYC-dWjiRD-vjucCE-dWjiQi-v5dhk5-6NTGp8-JHHy4-264DMUF-DU6o6b-6kwyti-264Dsgx-8J2u84-6RVP25-RLgjSr-4bdEKf-6kwxDH-Dm8Jb-8J2tVt-71CMwd-6RVMpf-6kAHgL-DNaCe4-6kAH9E-6kAHnJ-DKZPsj-cR1q3h-bHDDmR-6nn25Y-DNaEgF-DWqe9x-zu8wbX-sdr7HE-24z96iD-H5XsY9 "Panoz Roadster") ?_

There are many words that can be used to identify the object in this picture, and as long as people understand, there is nothing wrong with any of them. The word for this situation is [synonymy](https://en.wikipedia.org/wiki/Synonym) in that they all mean exactly or nearly the same thing.

*   The object might be identified as a _car_.
*   Or as an _automobile_
*   Or a _convertible._
*   Or a _roadster_.

All of these terms mean roughly the same thing. Albeit, upon closer inspection, differing degrees of specificity can be identified in this example. A car is a kind of automobile in American English. A convertible is a kind of car (and a kind of auto), and a roadster is a kind of convertible (also a kind of car, and a kind of auto). 

Synonymy is a challenge for retrieval, and for [precision](https://en.wikipedia.org/wiki/Precision_and_recall) in particular. What if a user has been reading a lot of old Nancy Drew recently, and that end-user spontaneously searches for _roadster?_ Or if that end-user is an automobile aficionado? 

And what if, when describing this image, you as the information intermediary do not call it that? If you call it something else, in an exact-match retrieval system, the user will not find it!

Controlled vocabularies allow information professionals to address problems of polysemy and synonymy that are evident in natural language. The information professional uses a specific term in surrogate records to avoid these problems, so when the end-user searches using that term, precision and recall are improved.

#### **Next**

_Next, a look at subject headings lists and thesauri, with mention of some that are in wide use in libraries._
<!-- #endregion -->
