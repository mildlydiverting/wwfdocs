#Living Planet Report

Here's the next installment of data from the Living Planet Report - Mara/Serengeti data showing species and locations from the Living Planet Index.
Although some of the data is quite old, we thought you might be able to cross reference it with some of the consumption info or any live data we get about elephants, etc.

We're still trying to find out the frequency of the population numbers, but there is no guarantee that this data will be updated again in future.

[Copy of Data from Masai Mara and Serengeti.xlsx
20 KB]

ZSL have fed back that the figures vary for every species i.e. some might be an annual figure, some might be a one-off estimate.  And we won't know until we actually plough through the data. 

So data from different species is not necessarily comparable AND we have no idea whether the research to do the population counts will ever be done again.  It is not a continuous stream.  But it could be a useful statistic.

Just to add to this, ZSL advised that the ID numbers in the spreadsheet are database references, rather than population numbers - so we'd have to ask for individual records to find out the population data for each species. 

-- 

To clarify – the ZSL population numbers referred to are the ones in the Copy of Data from Masai Mara and Serengeti sheet above?

They would indeed be useful, I think.
However, if the spreadsheets are dumps from a database (and the numbers are references to database IDs) can you ask them
* what format the entire Database is in?
* if it has a public interface anywhere? RESTful? On the web?
* if no public interface, it would be easier for them to supply us with a straight dump of the entire database in eg. MySQL format so we have all the tables to work with.

As currently, the process would be
* hacker wants to do something with elephant numbers
* looks up ID on table
* makes request to ZSL for actual figures from database
Which could be a pain.

--

#Living Planet Index Data: update

they are busy working on getting an online interface to the LPI data sorted!  This will be open source BUT it won't be available until mid/late November (in a test format only).

In the meantime the ZSL guy (third person I've spoken too!) Is getting me the data for Mara/Serengetti region - a dump which basically includes the "count" (population), "frequency" (of the count) and hopefully also geo-reference for where it was done.  I am getting this "soon as he can find time to run the request".

It is an Access database.

Ben, the ZSL guy, was very helpful and happy to answer further question or talk directly to developers.

LPI data for Mara/Serengeti.  Attached here.  Looks quite self explanatory - focus on the common name, location, unit description and then you have a load of dates with related unit counts.  Any queries let me know.

[Copy of Data from Masai Mara and Serengeti_updated.xlsx]
