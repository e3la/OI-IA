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
<a href="https://colab.research.google.com/github/e3la/Organizing-Information-in-Information-Agencies/blob/master/mod7_l_FIX_ODLIS.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
<!-- #endregion -->

```python id="NCzFNGKujZLn"

```

<!-- #region id="NXBU_YJIjZ0U" -->
Key Ideas in IO: Structural Metadata
====================================

**Defining Structural Metadata**
--------------------------------

The NISO primer identifies structural metadata as another primary kind of metadata—separate from descriptive metadata and administrative metadata. Specifically, structural metadata demonstrates the "relationships of parts of resources to one another" (Riley, 2017, p. 6).

Why is this important? Consider for a moment what is meant by "audiovisual"—what are the characteristics of a film, for example? If you study preservation, you'll know that there is at least one audio track and at least one video track (more if there are multiple language versions and captions), and they all have to be coordinated to play at the right time. The parts of a video resource need to be in exact alignment. If you are curious, the ODLIS defines [audiovisual (AV)](https://products.abc-clio.com/ODLIS/odlis_a.aspx#audiovisual) in the following way:

> A [work](https://products.abc-clio.com/ODLIS/odlis_w.aspx#work) in a [medium](https://products.abc-clio.com/ODLIS/odlis_m.aspx#medium) that combines sound and visual images, for example, a [motion picture](https://products.abc-clio.com/ODLIS/odlis_m.aspx#motionpicture) or [videorecording](https://products.abc-clio.com/ODLIS/odlis_v.aspx#videorecording) with a [sound track](https://products.abc-clio.com/ODLIS/odlis_s.aspx#soundtrack), or a [slide](https://products.abc-clio.com/ODLIS/odlis_s.aspx#slide) presentation synchronized with [audiotape](https://products.abc-clio.com/ODLIS/odlis_a.aspx#audiotape). [Directory](https://products.abc-clio.com/ODLIS/odlis_d.aspx#directory) [information](https://products.abc-clio.com/ODLIS/odlis_i.aspx#information) for products and services provided by the audiovisual industry is available in _AV Market Place (AVMP)_, [published](https://products.abc-clio.com/ODLIS/odlis_p.aspx#publishing) [annual](https://products.abc-clio.com/ODLIS/odlis_a.aspx#annual)ly by Information Today, Inc. Also spelled _audio-visual_ and [abbreviated](https://products.abc-clio.com/ODLIS/odlis_a.aspx#abbreviation) _a-v_. **_See also_**: [media](https://products.abc-clio.com/ODLIS/odlis_m.aspx#media).

AV is not the only place where the parts need to be in alignment (see Table 1). With metadata that is stored in repositories, the primary way that structural metadata is considered is through multi-part objects meant to be displayed in a certain sequence. 

**Table 1 Example Properties and Primary Uses for Structural Metadata** **(Riley, 2017, p. 7)**

| **Metadata Type** | **Example Properties** | **Primary Uses**                       |
| ---------------------- | ---------------------------------------------- | ------------------------------------------- |
| Structural metadata        | Sequence | Navigation
||  Place in hierarchy |||

### **Examples of Structural Metadata: Self-Study**

In module 4, you learned about Brewster Kahle, founder of the Internet Archive ([https://www.archive.org/](https://www.archive.org/)) and the WayBack Machine.

Take a few moments to visit the Internet Archive. Select an open access book, and look at the software that is available for turning pages in the book. How does the software know which files to display in which order? Easy! Structural metadata. In short, structural metadata helps the viewing software understand which file should be shown immediately after the file with page 8's content -- obviously, that would be the file with the content for page 9, but unless encoded correctly, the system has no way to know which file that is!

#### **Next**

_Next, this module looks to specifics about encoding. You already learned about encoding and standards for "containers" with MARC as the quintessential library-based example, but digital repositories use other standards that align more closely with broad practice in IT on the web and beyond._

* * *

#### Reference

Riley, J. (2017). _Understanding metadata: What is metadata, and what is it for?_ National Information Standards Organization (NISO). [https://groups.niso.org/apps/group\_public/download.php/17446/Understanding%20Metadata.pdf](https://groups.niso.org/apps/group_public/download.php/17446/Understanding%20Metadata.pdf)
<!-- #endregion -->
