# Review_defence_systems

To promote gender equality and inclusivity in research, we are convinced of the importance of acknowledging gender bias in research article citation.
To this effect, we estimated the proportion of female versus male authors in the references cited in this review. 
We used an online reference extractor (https://rintze.zelle.me/ref-extractor/) to extract all references cited in the manuscript. These references were then imported in a new zotero library, and exported as a csv file for further processing.

We then used our custom python script to obtain a table of all first and last authors of the publication cited. The gender of the first and last authors was pre-annotated based on their given name using an online database (https://archive.ics.uci.edu/dataset/591/gender+by+name). For the names absent from the database or with an unknown gender, we manually annotated the gender of the authors when possible.
