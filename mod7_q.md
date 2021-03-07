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
<a href="https://colab.research.google.com/github/e3la/Organizing-Information-in-Information-Agencies/blob/master/mod7_q.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
<!-- #endregion -->

<!-- #region id="Ed0gLOn9w0Wt" -->
Key Ideas in IO: Embedded Metadata
==================================

Surrogate records by definition will "stand in" for the resource. Often in libraries, these resources are books that are physically located on a shelf, and the surrogate will be used in the retrieval system.

What about, however, when the file itself is digital, and not physical?

**Metadata Associated with Digital Photography in Online Content Sharing Platforms**
------------------------------------------------------------------------------------

Image files are incredibly complex, with much information embedded in the file that you, as a human user, can't see.

#### What Is Involved in a Still Image File

Still image files like digital photographs can be large or small, have a lot or very few colors, seem pixelated at high resolutions, or scale beautifully. Why is this? The National Archives explains:

> [Still Image File (Links to an external site.)](https://www.archives.gov/preservation/products/definitions/raster-type.html): A type of digital object that is created from the digitization of still image (textual documents and photographs) originals. A still image is data in which a grid or raster of picture elements (pixels) has been mapped to represent a visual subject, e.g., the page of a book or a photograph. The term raster data is often contrasted with vector data, in which geometrical points, lines, curves, and shapes are based upon mathematical equations, thus creating an image without specific mapping of data to pixels. \[From the [FADGI Glossary (Links to an external site.)](http://www.digitizationguidelines.gov/glossary.php)\]

Bit-depth, spatial resolution, and color encoding, for example, are all important characteristics of still images. Raster images can be stored in a variety of data formats, such as TIFF (.tif).

Along with all the information that allows the photo to display properly, image files can also contain structured information about the photograph itself. Metadata!

For example, if you have a GPS-enabled device with which you take photographs, the photographs you create will probably include embedded information about the latitude and longitude where you took the photo. If there's a clock on the device, the day and time will also be captured as part of the image file. The image itself will include information about the camera used, as well as the settings. Online platforms designed for sharing will also have information about who took the photo, what the title (or subject) is, when the photo was uploaded to the system, how other users have tagged it, and the comments left by users of the platform. Figure 1 shows a screenshot of an example from Flickr. 

Figure 1 **Screenshot** **of an Image File and Metadata in Flickr**

[![Flickr hummingbird photo with metadata](cropped-flickr.png)](https://flickr.com/photos/shollingsworth/8752433737)

_Note._ Retrieved from [https://www.flickr.com/photos/shollingsworth/8752433737.](https://www.flickr.com/photos/shollingsworth/8752433737)

The image file is visible in the main panel, and Flickr helpfully displays some of the embedded metadata in the area below.

What metadata do you see displayed in this screenshot that you do not have access to when just looking at the photo?

**Web Pages**
-------------

Search engine optimization (SEO) is dependent, at least in part, on metadata in the html code of a webpage. See this example below and and check out a few webpages on your own. If you don't know how to view the html code of a webpage, do a search for the browser you are using and “source code.” Look for metadata information in the <head> information for the page. The content that displays publicly typically is in the <body> section of the html code.

Online article: Miller, P. (1996). Metadata for the masses. _Ariadne, 5_. [http://www.ariadne.ac.uk/issue/5/metadata-masses/](http://www.ariadne.ac.uk/issue/5/metadata-masses/)

The source code for this article includes the following metadata in the behind-the-scenes information embedded in the page. Not all webpages include such metadata, since its inclusion is optional.

<meta http-equiv="X-UA-Compatible" content="IE=edge">  
<meta name="**citation\_journal\_title**" content="Ariadne" />  
<meta name="**citation\_issn**" content="1361-3200">  
<meta name="**citation\_title**" content="Metadata for the Masses" />  
<meta name="**citation\_publication\_date**" content="1996" /> <meta name="citation\_issue" content="5" />  
<meta name="**citation\_author**" content="paul miller" />  
<link rel="alternate" type="application/x-bibtex" href="http://www.ariadne.ac.uk/issue/5/metadata-masses/citation.bibtex" title="Ariadne" />

This metadata is structured and encoded so that it can be read by a computer.

![](metadata.png)

Off and on, librarians explore the idea of using metadata embedded in digital objects as an alternative to surrogate records.  The idea has not caught on in libraries; library retrieval systems are dependent upon surrogate records.

**Wikipedia**
-------------

Wikipedia makes much use of structured data. View this entry for Sanford Berman: [https://en.wikipedia.org/wiki/Sanford\_Berman](https://en.wikipedia.org/wiki/Sanford_Berman). Note the summary box at the top right and the categories at the bottom of the record. (Unrelated to structured metadata, you will hear about Sanford Berman in a future module.)

### **Summary**

Metadata is used in information agencies and beyond. On the web, as in library retrieval tools, metadata can aid in the "identification, discovery, selection, use, access, and management" of resources.

#### **Next**

_More on embedded metadata, in files you may not expect._
<!-- #endregion -->
