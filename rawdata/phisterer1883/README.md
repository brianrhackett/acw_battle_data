# Phister (1883) Statistical Record of the Armies of the United States

Data from Phisterer, Frederick (1883) *Statistical Records of the Armies of the United States* ([Google books](http://books.google.com/books?id=cVNHr_nnLlYC)).

## Loss in Engagement

Data on major battles along with Union and Confederate casualties from the table "Loss in engagements, etc., where the total was five hundred or more on the side of the Union troops--(149)." on p. 213-219. The caption for the table reads:

   Although the losses here given are generally based on official medical returns, the figures must not be taken
   as perfectly reliable, for in many instances the returns were based on estimates, and the totals of losses were,
   by *later* and more reliable returns, sometimes considerably reduced. Confederate losses are generally based on estimates.

Some notes on specific battles

- 2345: includes several battles and overlaps with 2354. 
- 2351, 2355, 2366, 2373 all refer to Trenches in front of Petersburg,
  but don't seem to point to any specific battles. Most of the battles
  in the Petersburg Campaign have their own entries. See
  http://en.wikipedia.org/wiki/Siege_of_Petersburg
- 2307: Refers to all of
  http://en.wikipedia.org/wiki/Streight%27s_Raid, but there is only
  one battle.
- 2362: This is NOT http://en.wikipedia.org/wiki/Stoneman%27s_Raid.  There appears to be no battle page for this, 
  although it is discussed in http://en.wikipedia.org/wiki/George_Stoneman.
- 2372: http://en.wikipedia.org/wiki/Atlanta_campaign.  Linked to all
  battles in
  http://en.wikipedia.org/wiki/Category:Battles_of_the_Atlanta_Campaign_of_the_American_Civil_War. This battle 
  overlaps with several others.
- 2376: Price's invasion of Missouri; includes a number of engagements http://en.wikipedia.org/wiki/Price%27s_Raid.  This battle is linked to all battles in http://en.wikipedia.org/wiki/Category:Battles_of_Price%27s_Missouri_Expedition_of_the_American_Civil_War
- 2280: http://en.wikipedia.org/wiki/Seven_Days_Battles. Matched to the Seven Day's Battles except Oak Grove, 
  which has its own entry (2279).
- 2395 would appear to refer to Battle_of_Fort_Stedman, but 2394 explicitly refers to Fort Stedman. So 
  I cannot match this entry to a specific battle.
- 2397: http://en.wikipedia.org/wiki/Wilson%27s_raid

## Chronological Record

A list of events on p. 83--212.  Phisterer's introduction to the chronological record is:

   Under the orders of the Surgeon-General of the Army, a work of the greatest importance was undertaken and completed by that Department, viz., '. The Medical and Surgical History of the War of the Rebellion," and great credit is due for the magnificent and instructive work to Surgeons-General Wm. A. Hammond and J. K. Barnes, U. S. Army; Surgeon J. H. Brinton, U. S. Volunteers; Assistant-Surgeons (then) J. J. Woodward and George A. Otis, U. S. Army, who were directly connected with the work, as well as the members of the Medical Department, regulars and volunteers, generally.
   
   In this work there is a chronological record of engagements, etc., compiled by the Chief Clerk of the Surgical Division. Mr. Frederick R. Sparks, from official sources where practicable, from Confederate reports, and from Union and Confederate newspapers in other cases, where the statement was not obviously false. As full as the record is, it is not complete. In preparing it for publication here, several minor engagements were added, and others may find omissions as well; nevertheless, this is the complete record in existence at present.

- `engagements.txt` Raw text of the events
- `engagements.py` Extacts engagements from `engagements.txt` and produces `engagements.csv`.
- `engagements.csv` Parsed list of events
- `engagements_by_year.csv` Small table of the number of egagements by year.

## Links

Links from the "Loss in Engagement" data to CWSAC and dbpedia battles:

- `phisterer_to_cwsac.csv`
- `phisterer_to_dbpedia.csv`
