# Processor

* DACS: Processing Information in Notes Element, 7.1.8
* EAD3: Processing Information <processinfo>; Control <control> (replaces <eadheader> from EAD 2002)
* ArchivesSpace: Processing Information Note, and/or Collection Management --> Processors (internal field; not exported in EAD)
* MARC: N/A
* ISAD(G): 3.7.1
* RDA: N/A

### REQUIRED
If the digital materials were processed either at a later date and/or by a different person than the rest of the collection, specify when and by whom they were processed. 
* Ex. **“Digital materials processed by [processor] in [year]”.** If processed by a student, consider including, **“under the supervision of [supervisor]”.**  

Some organizations may have a local practice of recording the processor’s name and the period of time over which that processing took place in the front matter of the finding aid. In that case, use the EAD header <author> element. The header element <author> can also be used to note the actual author of the finding aid if this differs from the processor, and can be helpful to note additions where new description has been added to an existing finding aid.**[7]** Note that this element contains information on the processor only, and that more specific information on the Processing Information should be contained within the “Processing Information” element, which is outlined in the “Processing Information” section of this document. 

#### EXAMPLES:
**Susan Sontag papers, circa 1933-2004** 
2002 installment processed by Lorain Wang and Catherine Lee, August 2002; 2005 installment processed and integrated with 2002 installment by Lauren McDaniel, February 2007-April 2008; 2012 installment processed by Mitchell Erzinger, October 2013-March 2014; **digital materials processed by Lori Dedeyan in 2014.**

Barbara Jones papers, 1942-2007 (bulk 1945-1986)
Processed by Timothy Smith in 2011. **Digital materials processed in 2016 by Victoria Maches and Scott Reed in the Center for Primary Research and Training (CFPRT), under the supervision of  Shira Peltzman.**

___
[7] These guidelines distinguish “Processor” as a separate descriptive element from “Processing Information”. Note that there is no corresponding “Processor” element in DACS or EAD. Information about the processor may be publicly recorded in the <author> element of the EAD header, or privately noted in internal collection files or collection management systems. ArchivesSpace (version 2.0) provides a staff-only field labeled “Processors” in the Collection Management sub-record.
