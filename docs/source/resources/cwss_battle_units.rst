###############################
CWSS battle data: units engaged
###############################

:name: cwss_battle_units
:path: cwss_battle_units.csv
:format: csv

Units engaged in each battle in :doc:`cwss_battles` on each side. These units correspond to units in :doc:`cwss_regiments_units`, and are largely at the size of the regiment. This data does not include naval forces.

This data was extracted from the CWSS database file ``battleunitlinks.xml``.

The primary sources of the battle unit data are Frederick Dyer (1908), *A Compendium of the War of the Rebellion*
for the Union forces, and Joseph Crute *Units of the Confederate States Army* for
Confederate Units. While these data appear relatively complete for the Union,
they do not appear to be complete for the Confederate battles.
Many battles have missing data on the Confederate side (e.g. Gettysburg), and
even within battles, there are sometimes fewer Confederate units than would be
expected.


Sources: [CWSS]_


Schema
======



===============  ======  ================
BattlefieldCode  string  Battlefield code
Comment          string  Comment
Source           string  Source
UnitCode         string  Unit code
companies        number  companies
batteries        number  batteries
detachment       number  detachment
section          number  section
===============  ======  ================

BattlefieldCode
---------------

:title: Battlefield code
:type: string
:format: default
:constraints:
    :minLength: 5
    :maxLength: 6
    :pattern: [A-Z]{2}[0-9]{3}[A-Z]?
    

CWSAC battle identifier


       
Comment
-------

:title: Comment
:type: string
:format: default





       
Source
------

:title: Source
:type: string
:format: default





       
UnitCode
--------

:title: Unit code
:type: string
:format: default





       
companies
---------

:title: companies
:type: number
:format: default





       
batteries
---------

:title: batteries
:type: number
:format: default





       
detachment
----------

:title: detachment
:type: number
:format: default





       
section
-------

:title: section
:type: number
:format: default





       

