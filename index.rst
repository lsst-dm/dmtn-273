:tocdepth: 1

.. sectnum::

.. Metadata such as the title, authors, and description are set in metadata.yaml

.. TODO: Delete the note below before merging new content to the main branch.

.. note::

   **This technote is a work-in-progress.**

Abstract
========

Describes a set of proposed tools to be used for the validation and maintenance of Felis files within the Rubin context.  

Validation tools support ensuring that all datatypes, UCDs, and units used are valid; assessing how many columns have missing UCDs and units (though this may not always be an error); that all tables and columns have descriptions; that all tables have a subset of columns declared "principal"; etc.

Manipulation tools allow: bulk editing of Felis files to, for instance, change a specified attribute of a specified subset of columns; comparison of two files to determine whether the definitions of columns between them are compatible; conversion of files to/from a tabular/spreadsheet form to facilitate review and editing; etc.

These tools are meant to help complete the work of producing useful, user-friendly schema information with less tedium and fewer problems with updating the DP0.2, ImSim, and HSC schemas in parallel.

Add content here
================

Add content here.
See the `reStructuredText Style Guide <https://developer.lsst.io/restructuredtext/style.html>`__ to learn how to create sections, links, images, tables, equations, and more.

.. Make in-text citations with: :cite:`bibkey`.
.. Uncomment to use citations
.. .. rubric:: References
.. 
.. .. bibliography:: local.bib lsstbib/books.bib lsstbib/lsst.bib lsstbib/lsst-dm.bib lsstbib/refs.bib lsstbib/refs_ads.bib
..    :style: lsst_aa
