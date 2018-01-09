# Physical Description

* DACS: Extent Element 2.5
* EAD3: Physical Description <physdesc>
* ArchivesSpace: Physical Description Note
* MARC: 300
* ISAD(G): 3.1.5
* RDA: Extent 3.4
  
 _See also [Extent](https://github.com/shirapeltzman/uc-guidelines/blob/master/DESCRIPTIVE_ELEMENTS/extent.md)_


### REQUIRED
Physical Description **[8]** must include units of measure for born-digital material. This should _always_ include both the size of the digital material in GB as well as the total number of files that have been preserved. Use ‘GB’ instead of “Gigabytes”, “gigabyte”, “Gb”, “GBs”, or any other variations thereof. Consult a digital data storage conversion tool if necessary, such as: http://www.thecalculatorsite.com/conversions/datastorage.php

When calculating size, round to three decimal points only when content is less than 1 GB. If content is smaller than 1 MB, default to “.001 GB”. Otherwise, round to two decimal points (e.g. 9.25 GB).

For unprocessed material where capacity is unknown or difficult to estimate, include a count of the unprocessed media formats. 

In certain cases, processors can also include other units of measure that may help a researcher better gauge or contextualize the amount of digital material present in the collection. This could include, for instance, total runtime or duration (for audiovisual files), total number of disk images, or total number of emails.

#### EXAMPLES:
* "Physical Description: 3 unprocessed hard drives (100 GB, 3000 GB, and 1000 GB) and 14 unprocessed CDs."

* "Physical Description: 4.5 linear feet (6 oversize boxes, 1 manuscript box), and 3400 GB (37,364 digital files)"

* "Physical Description: 13.4 linear feet (26 document boxes, 10 half document boxes, and 1 oversize flat box), and 385 GB (12,938 digital files)"

* "Physical Description: 19.5 linear feet (29 boxes) and 3750 GB (58,439 digital files, including 20,879 WAV files that total approximately 75 hours in duration)"

* "Physical Description: 109 linear feet (204 boxes) and 985 GB (11,905 digital files, including 17 disk images and 209 digital video files that total approximately 19 hours in duration)"

* "Physical Description: .5 linear feet (1 box) and 113 GB (1,097 WARC files representing periodic crawls of approximately 193 web sites)" 

* "Physical Description: 17 linear feet (25 boxes) and .011 GB (31 digital files)"

___
[8] “Physical Description” is used here to mean a brief narrative summary noting the type and number of containers present, their physical attributes and/or dimensions, or other information related to their size, shape, or appearance. Please note that “Physical Description” and “Extent” actually map to two separate EAD3 elements: <physdesc> and <physdescstructured>. These two elements are independent of each other, and are differentiated in order to record different kinds of information about physical description. See https://www.loc.gov/ead/EAD3taglib/index.html#elem-physdesc and https://www.loc.gov/ead/EAD3taglib/index.html#elem-physdescstructured 

[9] SAA-ACRL/RBMS Joint Task Force on the Development of Standardized Holdings Counts and Measures for Archival Repositories and Special Collections Libraries (Affiliated Group). “Guidelines for Standardized Holdings Counts and Measures for Archival Repositories and Special Collections Libraries.” Society of American Archivists. (2014-2016). http://www2.archivists.org/groups/saa-acrlrbms-joint-task-force-on-holdings-metrics/guidelines-for-standardized-holdings-coun-1

[10] The total size and number of files recorded in the <physdesc> field should refer only to the collection material being described; it should not include any accompanying metadata files or related submission documentation. 
