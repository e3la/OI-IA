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

<!-- #region id="view-in-github" colab_type="text" -->
<a href="https://colab.research.google.com/github/e3la/Organizing-Information-in-Information-Agencies/blob/master/mod7_p_fixodlis.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
<!-- #endregion -->

<!-- #region id="Ed0gLOn9w0Wt" -->
Creating and Managing Metadata
==============================

**"Flavors" of Metadata**
=========================

![](metadata-icon.png)  
It may be coming clear that there are actually many different kinds of metadata that can describe many kinds of resources. The users, the retrieval tool, the nature of the resource, and the context for use will all determine the kinds of metadata that are recorded or used by the system.

Consider these aspects of metadata:

*   Some metadata is created automatically, some manually.
*   Some metadata is used behind the scenes and some is exposed for user by users.
*   Some metadata helps end users understand what the resource is about or who made it, etc.
*   Some metadata helps end users understand whether they have permission to use, for example, a digital file.
*   Some metadata helps databases display digital files correctly.
*   Other metadata helps users understand whether a file is authentic, or the most recent version.

Previous modules on metadata related to resources description and subject content assumed that much of the metadata was created by humans. Not all metadata is.

**Automatically Generated Metadata**
------------------------------------

Whether metadata is created manually or automatically depends on the metadata, the system, the needs of the user,  and the expertise of the information intermediary. Most of the descriptive metadata used in the information professions is created manually, and most of the technical metadata is created automatically. On the web, most everything is done automatically. In digital libraries and digital archives, a mix of the two environments might be found. 

What is the automated creation of metadata? Technical metadata such as the metadata in Flickr images is created at the time the file is created and is immediately embedded. Other metadata might be created later. For example, optical character recognition (OCR) is usually run over a file after the image is created. OCR enables the text of the file to be searchable. Compare the following two documents: one is basically a digital photo of a document, the other is the same file, but has had OCR and has corrected the text and made it searchable.

[Example 1](Extension-NoOCR.jpg)

[Example 2](/Extension-OCR.pdf)

The ODLIS defines [optical character recognition](https://products.abc-clio.com/ODLIS/odlis_o.aspx#opticalcharacter) in the following way: 

> A process by which [characters](https://products.abc-clio.com/ODLIS/odlis_c.aspx#character) typed or [printed](https://products.abc-clio.com/ODLIS/odlis_p.aspx#printing) on a [page](https://products.abc-clio.com/ODLIS/odlis_p.aspx#page) are electronically [scanned](https://products.abc-clio.com/ODLIS/odlis_s.aspx#scanner), analyzed, and if found recognizable on the basis of appearance, [converted](https://products.abc-clio.com/ODLIS/odlis_d.aspx#dataconversion) into a [digital](https://products.abc-clio.com/ODLIS/odlis_d.aspx#digital) character code capable of being [processed](https://products.abc-clio.com/ODLIS/odlis_d.aspx#dataprocessing) by a computer. OCR eliminates the time-consuming process of re-keying [information](https://products.abc-clio.com/ODLIS/odlis_i.aspx#information) produced in [print](https://products.abc-clio.com/ODLIS/odlis_p.aspx#print), but results can be unpredictable if the scanned [copy](https://products.abc-clio.com/ODLIS/odlis_c.aspx#copy) is imperfect or contains [diacritical mark](https://products.abc-clio.com/ODLIS/odlis_d.aspx#diacriticalmark)s or unrecognizable characters. Compare with [intelligent character recognition](https://products.abc-clio.com/ODLIS/odlis_i.aspx#icr) (ICR).

The book edited by Murtha Baca (2016) and published by the Getty called _Introduction to Metadata_ has a fantastic glossary. The definition for [automatic indexing](http://www.getty.edu/publications/intrometadata/glossary/#automatic_indexing) it provides is the following:

> **automatic indexing**
> 
> In the context of online retrieval, indexing by the analysis of text or other content using computer algorithms. The focus is on automatic, behind-the-scenes methods involving little or no input from individual searchers, with the exception of relevance feedback.

Metadata can take many forms, it can be visible or invisible to users and to information intermediaries. One thing to remember, if any of this starts to seem too daunting, is that consistency is key. If metadata is used and applied consistently, that goes a long way toward ensuring future use and usability.

#### **Next**

_Another "flavor" of metadata: metadata embedded in digital objects._
<!-- #endregion -->
