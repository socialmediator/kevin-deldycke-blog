date: 2008-06-05 20:35:58
title: I wrote the best Open-Source Payroll Software of the world !
category: English
tags: company, consulting, ERP, floss, free software, open source, OpenERP, ERP5, OpenBravo, Neogia, Adempiere, Compiere

... at least [according Smile](http://www.smile.fr), a French consulting company. In their latest white paper ([available for download here](http://www.smile.fr/Livres-blancs/ERP-et-decisionnel/ERP-open-source)), they've studied [Open-Source ERPs](http://en.wikipedia.org/wiki/Category:Free_ERP_software).

Here is what they said about ERP5 in page 87:

> ERP5 va même jusqu'à gérer les paies alors qu'aucun autre ERP libre n'est allé aussi loin

Which roughly translates to:

> ERP5 even manage payroll, while any other free software ERP has gone as far

Hey wait. I wrote this module !

And here is their final evaluation (0 is the lowest, 5 the highest note) of all payroll systems for each ERP (from page 88):

ERP | Evaluation
--- | ---
TinyERP | <i class="icon-star"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i>
OpenBravo | <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i>
Neogia | <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i>
ERP5 | <i class="icon-star"></i> <i class="icon-star"></i> <i class="icon-star"></i> <i class="icon-star"></i> <i class="icon-star-empty"></i>
Adempiere | <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i>
Compiere GPL | <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i> <i class="icon-star-empty"></i>

Sorry for the shameless self-promotion, but I was so happy to get this distinction that I couldn't resist... :)

The payroll modules were one of my biggest [contribution as a core developer on ERP5](https://www.ohloh.net/p/erp5/contributors/18391049963153). It was capable of [producing the paysheets](http://web.archive.org/web/20110128111823/http://www.erp5.org/workspaces/project/erp5_payroll/erp5_pay_sheet_for_n/view) of all Nexedi's employees. Here is an example:

![](/static/uploads/2008/erp5-final-paysheet.png)

These modules were so extensive that I wrote a detailed tutorial based on them. As it was the only comprehensive documentation available on ERP5, my work virtually became the [ERP5's bible for developers](http://web.archive.org/web/20050924101245/http://www.erp5.org/sections/documentation/articles/erp5_developer_tutor3829/downloadFile/file/Tutorial-Kevin-en.pdf?nocache=1114902907.39) for a while.

You can download the [English translation](http://web.archive.org/web/20050924101245/http://www.erp5.org/sections/documentation/articles/erp5_developer_tutor3829/downloadFile/file/Tutorial-Kevin-en.pdf?nocache=1114902907.39) or read the original [French version](http://www.docstoc.com/docs/42926223/D%C3%A9veloppez-votre-propre-ERP-gr%C3%A2ce-aux-Business-Templates-ERP5) online:

<iframe src="http://www.docstoc.com/docs/document-preview.aspx?doc_id=42926223" width="574" height="613" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" allowfullscreen webkitallowfullscreen mozallowfullscreen> </iframe>

This document had enough influence to be cited in four academic papers from 2006 to 2009:

  * [A comparison of Open Source ERP Systems](http://www.big.tuwien.ac.at/system/theses/20/papers.pdf)

  * [A Research on Corporate ERP Systems used for Supermarket Supply Chain Inventory Management in Turkey](http://www.slideshare.net/Agcristi/a-research-on-corporate-enterprise-resource-planning-erp)

  * [Open Source Enterprise Resource Planning Systems](http://behdasht.gov.ir/uploads/101_195_baresiye%20ERP%20haye%20matn%20baz.pdf)

  * [Comparatif ERP5 / COMPIERE](http://wiki.itin.fr/index.php/Comparatif_ERP5_/_COMPIERE_MT09_FR)
