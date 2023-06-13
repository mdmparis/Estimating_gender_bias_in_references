# Estimating gender ratio in references

To promote gender equality and inclusivity in research, we are convinced of the importance of acknowledging gender bias in research article citation.
To this effect, using surnames, we roughly estimated the gender ratio in the references cited in a publication and add a statement in the acknoledgements such as
*"To promote gender equality and inclusivity in research, we are convinced of the importance of acknowledging gender bias in research article citation. We estimated that among the XX references cited in the main text, approx. XX% (XX) have a female first author and approx. XX% (XX) have a female last author."*

To do this, we used an online reference extractor (https://rintze.zelle.me/ref-extractor/) to extract all references cited in the manuscript. These references were then imported in a new zotero library, and exported as a csv file for further processing.

We then used our custom python script (available in this repo) to obtain a table of all first and last authors of the publication cited. The gender of the first and last authors was pre-annotated based on their given name using an online database (https://archive.ics.uci.edu/dataset/591/gender+by+name). For the names absent from the database or with an unknown gender, we manually annotated the gender of the authors when possible.

As an example, we provide a table and a script based on one reviews we wrote.
