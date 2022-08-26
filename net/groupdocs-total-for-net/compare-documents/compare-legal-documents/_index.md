---
title: "Compare Legal Documents"
description: "This article explains how to use GroupDocs.Comparison API (which is a part of Conholdate.Total for .NET) to compare legal documents."
keywords: Compare legal documents, Compare legal documents in C#
type: docs
url: /compare-legal-documents/
weight: 50
---

## Compare legal documents in C#

The Microsoft Word comparison features may be not enough to compare contracts and legal documents. Suppose you need your own way to implement comparison logic or you are developing your own app. The [**GroupDocs.Comparison**](https://products.groupdocs.com/comparison/net) (which is a part of Conholdate.Total for .NET) gives the ability to compare documents programmatically and manage found differences in code for wide range of [supported file formats](https://docs.groupdocs.com/comparison/net/supported-document-formats/). Here is an example of how to compare two contracts using GroupDocs.Comparsion API. You just have to follow these steps


## Code Sample
Here is the code that is used to compare two contracts.

{{< gist "conholdate-docs-gists" "01e03338e930f4d1aa19e23242383c99" "compare-legal-documents.cs" >}}

As a result, we get a DOCX file where the deleted elements are marked in <font color="red">**red**</font>, the added – in <font color="blue">**blue**</font>, and the modified – in <font color="green">**green**</font>.

![](https://docs.groupdocs.com/comparison/net/images/how-to-compare-contracts-drafts-and-legal-documents_5.png)

For more details you can visit [this article](https://docs.groupdocs.com/comparison/net/how-to-compare-contracts-drafts-and-legal-documents/).






