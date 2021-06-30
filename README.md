# spiderfish
Information theoretic visualization of a dataset;

A tool to visualize and compare entropy of and mutual information between fields of a dataset.  The initial motivation was to develop a tool to help grok the structure of unfamiliar datasets (e.g.: along with pairplots in python or R).  The metrics and visualization may also lend themselves to application in a whitebox classifier.

I have a history as a research oriented relational database guy.  I always found Entity-Relationship (i.e.: ER) models and diagrams to be useful for the understanding of the systems to which relational databases are applied.  

I have participated in a number of datathons.  One problem I have encountered is despite best efforts to clean and organize data for participants the utility and structural features of (frequently repurposed) data is not always clear.  There are a variety of exploratory tools and techniques that can be used to help with this, mostly based on statistics and a standard suite of visualization techniques.

But wouldn't it be nice to have an ER diagram to understand the structure of datathon data?

There is no chance of this.  A relational database is structured order.  Datathon data is a herd of cats.  They exist at opposite ends of the entropy spectrum.

Enter information theory.  Creating a relational database can be thought of as a process of squeezing the information entropy out of a dataset to crystalize meaning.  I can vouch for this.  My entire experience as a relational database developer was an exercise in herding cats.  It was WORK.  I would much rather have been programming.  But at the end of the process you had a beautiful information gem that could be applied to efficient and useful information addition, retrieval, and exploration.

And the Entity-Relationship model you had created becomes a valuable meta-information artifact that lent itself to an understanding of the subject matter to which it had been applied.

Now you may not be able to stuff a mess of pre-herded cats into anything like an ER model.  But you can try.  And how far you get with the stuffing of those cats is potentially informative.

Information theory lends itself to measuring degrees of fuzziness.  A data field can be more or less structured.  If it is highly structured it is easy to encode and compress, corresponding to low information entropy.  Highly unstructured data corresponds to high information entropy.

Mutual information can be thought of as a measure of to what degree data fields encode for each other.  Multivariate mutual information can generalize this measure of the degree of encoding to larger relationships and also tell us something about the nature of the encoding.

And perhaps most importantly entropy and MI are metrics instead of statistics.  As such they lend themselves as general measurements and to application in models or visualizations.  By modeleing and/or visualizing the entropy and mutual information contained in and between a set of fields a sense of the structure of a dataset can be realized.  Statistics answer specific questions and must be properly focused to be truly effective.  Information theory lends itself to a general sense of potential salience.

This is where the spiderfish visualization tool comes in.  A spiderfish is a deep sea fish attuned to very low light conditions.  It's eyes do not focus but can pick up a general impression of e.g. movement or light (much like our own peripheral vision).  It can then bring other senses to bear on potential food or threats.

The spiderfish visualization tool is an exercise in squeezing as many dimensions of the information entropy metric into a two dimensional representation (e.g.: a printout or computer monitor) as possible.  Once we have a general sense of the structure of a dataset we can then know where to apply more focused tools (e.g.: statistics) more effectively.

The result is not an ER diagram but it does capture some of what an ER diagram captures.  And it can be applied to much messier stuff.  It is potentially a tool for the general exploration and understanding of any given dataset. 




