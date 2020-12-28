---
title: pdfcpu
layout: splash
permalink: /
header:
  overlay_color: "#017c9c"
excerpt: "**PDF Processor, written in Go**"


feature_row:
  - title: "About"
    excerpt: "`pdfcpu` is a PDF processor written in Go supporting encryption and a rich set of commands, like creating, stamping 
    and watermarking PDFs."
    btn_label: "more info" 
    url: /about
    btn_class: "btn--info"

  - title: "Command Line"
    excerpt: "Use shell scripts and the CLI to build your PDF processing pipelines for batch processing. `pdfcpu's` rich command line also allows the processing of encrypted files. You can use `pdfcpu` to manipulate your PDF files on the command line of all major platforms.."
    btn_label: "more on CLI"
    url: "/cli"
    btn_class: "btn--info"

  - title: "Library (API)"
    excerpt: "Use the `pdfcpu` API to integrate PDF processing into your Go based backend systems. All operationd are available **file based** and **interface based** (typically using io.ReadSeeker/io.Writer)."
    btn_label: "more on API"
    url: "https://pkg.go.dev/github.com/pdfcpu/pdfcpu/pkg/api"
    btn_class: "btn--info"


---

{% include feature_row %}


# Available Commands (alphabetical)

All commands can be used both via CLI and API
* Change user/owner password
* Collect (generate a PDF page sequence, pages may appear multiple times in any order)
* Crop (apply a Crop Box for selected pages)
* Decrypt (remove password protection)
* Encrypt (set password protection)
* Extract Content (extract the PDF-Source into given dir)
* Extract Fonts (extract all embedded fonts of a PDF file into a given dir)
* Extract Images (extract embedded images of a PDF into a given dir)
* Extract Metadata (extract XML metadata)
* Extract Pages (extract specific pages into a given dir)
* Fonts (install, list supported fonts)
* Grid (rearrange pages into grid layout for enhanced browsing)
* Import convert/import images into PDF
* Info (print file info)
* Manage (add,list) user access permissions
* Manage (add,remove,list) document properties
* Manage (add,remove,list) page boundaries
* Manage (add,remove,list) search keywords
* Manage (add,remove,list,extract) embedded file attachments
* Manage (add,remove,list,extract) portfolio entries
* Manage (add,update,remove) stamps/watermarks for selected pages using text, images or PDF page content.
* Manage (insert,remove) pages
* Merge (a set of PDF files into one consolidated PDF file)
* N-up (rearrange pages into grid layout for reduced number of pages)
* Optimize (get rid of redundancies like duplicate fonts, images)
* Paper (print list of supported papersizes)
* Read (build xref table from PDF file)
* Rotate selected pages
* Split (split multi-page PDF into several PDFs according to split span)
* Trim (generate a custom version of a PDF including selected pages)
* Validate (validate PDF files up to version 7.0)
* Write (write xref table to PDF file)
