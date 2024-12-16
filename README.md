### Dialogue.csv
- contains all dialogues and identifiers in this dataset, 7444 records
- the column "Dialogue" has Dtype as object, and all identifiers that we will use to join with other tables are integer types (e.g. Dialogue ID, Chapter ID, Place ID, etc.)
- no missing rows / cleaning required, maybe with the actual text itself 

### Characters.csv
- we see that there are 166 records in which they all have an ID and a name, but about 41 of them are not assigned a gender or species
- 90 characters are not assigned a house. Other fields in this dataset like Patronus and Wand(s) are nullable for most characters

### Movies.csv
- This small dataframe stores the 8 movies in the Harry Potter series
- no cleaning required, may do additional augmenting of columns to the dataset

### Chapters.csv
- 234 records, no missing values
- contains identifiers (Chapter ID) to join back on dataframes coming frmo Dialogue.csv and Movies.csv

### Places.csv
- all places/locations are non-null, no cleaning will be required
- not all dialogues have a place assigned
