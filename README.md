List of New Zealand birds
=========================

[New Zealand Birds Online](http://nzbirdsonline.org.nz) is a comprehensive record of the bird species that occur in New Zealand, including vagrant and extinct birds. This website is a joint project between Museum of New Zealand Te Papa Tongarewa, Ornithological Society of New Zealand (Birds New Zealand), and Department of Conservation Te Papa Atawhai. The common and scientific names may be considered to be reliable.

Using the list
--------------
The list is presented as a `csv` file, suitable for opening with Excel*, or loading into databases.

The list may be [downloaded as a zip file](https://github.com/wayne-shih/dds-nzbirdslist_en_mi/archive/master.zip). This file contains a csv file with a list of all the birds on [New Zealand Birds Online](http://nzbirdsonline.org.nz), giving their common name, scientific name, status, and a link to the corresponding web page.

The script that was used to generate the list, and this help text, are also included in the zip file.

Te reo Māori names
------------------
Te reo Māori names (`tereomāori_names` column) have been complied by [Wayne Shih](https://github.com/wayne-shih/) and was not part of the original repository compiled by Edward Abraham and Chris McDowall at [Dragonfly Data Science](https://github.com/dragonfly-science/) nor on the New Zealand Birds Online dataset. Names have been sourced from Te Ara and Te Aka Māori-English English-Māori Dictionary. Due to various dialects there may be variations to the names, if in doubt check with the local iwi or [professional translators](https://www.tetaurawhiri.govt.nz/en/services/national-translators-and-interpreters-register/).

*Note the `.csv` is Unicode (UTF-8) text encoded and contains tohutō/macrons, for some reason this does not play well with Microsoft Excel. [Here's a work around](https://quizandsurveymaster.com/getting-excel-properly-show-accented-characters/). Alternatives: Apple Numbers or [LibreOffice Calc](https://www.libreoffice.org/download/download/); otherwise, good ol text editor.

Licence
-------
Thanks to Colin Miskelly, the principal curator of New Zealand Birds Online, this list is released into public domain under a [CC0 licence](https://creativecommons.org/publicdomain/zero/1.0/). You are welcome to use this list for whatever purpose you want.

Note that the other text, image, and media content on New Zealand Birds Online is copyright, and only the species names and status information are released into the public domain.

Generating the list
-------------------
The csv file was generated from the New Zealand Birds Online website by running the python script `nzbirdsonline_index.py`. This script depends on `BeautifulSoup` and uses the older version 3.

Note the python script will not generate the `tereomāori_names` column.
