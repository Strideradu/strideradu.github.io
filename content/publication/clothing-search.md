+++
abstract = "Single-molecule, real-time sequencing (SMRT) developed by Pacific BioSciences produces longer reads than secondary generation sequencing technologies such as Illumina. The long read length enables PacBio sequencing to close gaps in genome assembly, reveal structural variations, and identify gene isoforms with higher accuracy in transcriptomic sequencing. However, PacBio data has high sequencing error rate and most of the errors are insertion or deletion errors. During alignment-based homology search, insertion or deletion errors in genes will cause frameshifts and may only lead to marginal alignment scores and short alignments. As a result, it is hard to distinguish true alignments from random alignments and the ambiguity will incur errors in structural and functional annotation. Existing frameshift correction tools are designed for data with much lower error rate and are not optimized for PacBio data. As an increasing number of groups are using SMRT, there is an urgent need for dedicated homology search tools for PacBio data. In this work, we introduce Frame-Pro, a profile homology search tool for PacBio reads. Our tool corrects sequencing errors and also outputs the profile alignments of the corrected sequences against characterized protein families. We applied our tool to both simulated and real PacBio data. The results showed that our method enables more sensitive homology search, especially for PacBio data sets of low sequencing coverage. In addition, we can correct more errors when comparing with a popular error correction tool that does not rely on hybrid sequencing. The source code is freely available at https://sourceforge.net/projects/frame-pro/."
abstract_short = "Single-molecule, real-time sequencingdeveloped by Pacific BioSciences produces longer reads than secondary generation sequencing technologies such as Illumina. However, PacBio data has high sequencing error rate and most of the errors are insertion or deletion errors, causing frameshifts and leading to marginal alignment scores and short alignments in homology search. As SMRT has been adopted widely for various sequencing projects, there is an urgent need for dedicated homology searchtools for PacBio data. In this work, we introduce Frame-Pro, a profile homology search tool for PacBio reads. Our tool corrects sequencing errors and also output the profile alignments of the corrected sequences against characterized protein families. We applied our tool to both simulated and real PacBio data. The results showed that our method enables more sensitive homology search and corrects more errors compared to a popular error correction tool that does not rely on hybrid sequencing."
authors = ["Nan Du", "Yanni Sun"]
date = "2016-08-29"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *Oxford Bioinformatics*."
publication_short = "In *Bioinformatics*"
selected = true
title = "Improve homology search sensitivity of PacBio data by correcting frameshifts"
url_code = "https://sourceforge.net/projects/frame-pro/"
#url_dataset = "#"
#url_pdf = "#"
#url_project = "project/bioinformatics/"
#url_slides = "#"
#url_video = "#"

[[url_custom]]
name = "Online Version"
url = "https://academic.oup.com/bioinformatics/article/32/17/i529/2450788/Improve-homology-search-sensitivity-of-PacBio-data"

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/ModifiedHMM.jpg"
caption = ""

+++

More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.
