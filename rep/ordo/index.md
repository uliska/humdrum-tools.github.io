---
sidebar:	representations
chapternav:	rep
author:		David Huron
creation-date:	1 Sep 1998
revision-date:	3 Feb 2000
last-edited:	
vim:		ft=html
---


Sequential Order
===========================================

## REPRESENTATION ##

<span class="rep">ordo</span> &mdash; sequential order of events representation

## DESCRIPTION ##

The <span class="rep">ordo</span> representation consists of a set of numerical values
indicating the order of events. An <span class="rep">ordo</span> spine simply encodes a
series of ascending integers marking the succession of events:

``

----------
\*\*ordo
1
2
3
4
5
\*-
----------

The <span class="rep">ordo</span> representation recognizes \"common system\" barlines
&mdash; see [**barlines**](barlines.rep.html).

## FILE TYPE ##

It is recommended that files containing predominantly <span class="rep">ordo</span> data
should be given names with the distinguishing \`.ord\' extension.

## SIGNIFIERS ##

The following table summarizes the <span class="rep">ordo</span> mappings of signifiers
and signifieds.

----- ----------------
0-9   decimal values
.     null token
=     barlines
==    double barline
----- ----------------

*Summary of <span class="rep">ordo</span> Signifiers*

## EXAMPLES ##

A sample document is given below:

``

----------
\*\*ordo
=1
1
2
3
=2
4
.
5
\*-
----------

## PERTINENT COMMANDS ##

The following Humdrum command produces <span class="rep">ordo</span> data as output:

-- --------------------------------- --------------------------------------
<span class="tool">num</span>   number selected Humdrum data records
-- --------------------------------- --------------------------------------

## TANDEM INTERPRETATIONS ##

The following tandem interpretations can be used in conjunction with
<span class="rep">ordo</span>:

------------------ ------------
meter signatures   `*M6/8`
key signatures     `*k[f#c#]`
key                `*c#:`
tempo              `*MM96.3`
timebase           `*tb32`
------------------ ------------

*Tandem interpretations for <span class="rep">ordo</span>*

## SEE ALSO ##

` barlines, **date, **dur, **metpos, **recip, scramble, **takt, **time, **Zeit`

