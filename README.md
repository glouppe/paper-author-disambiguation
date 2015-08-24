# Ethnicity sensitive author disambiguation of semi-labeled corpora of scientific articles

* Gilles Louppe
* Hussein Al-Natsheh
* Mateusz Susik
* Eamonn Maguire

Author name disambiguation in bibliographic databases is the problem of
grouping together scientific publications written by a same person, accounting
for potential homonyms and/or synonyms. Among solutions to this problem,
digital libraries are increasingly offering tools for authors to manually
curate their publications and claim which ones are theirs. Indirectly, these
tools allow for the inexpensive collection of large annotated training data,
which can be further leveraged to build a complementary automated
disambiguation system capable of inferring patterns for identifying
publications written by a same person.  Building upon more than 1 million of
publicly released crowdsourced annotations, we propose an automated author
disambiguation solution exploiting this data (i) to learn an accurate
classifier for identifying corefering authors and (ii) to guide the clustering
of scientific publications by distinct authors in a semi-supervised way. To the
best of our knowledge, our analysis is the first to be carried out on data of
this size and coverage. With respect to the state of the art, we validate the
general pipeline used in most existing solutions, and improve by proposing
phonetic-based blocking strategies, thereby increasing recall, and strong
ethnicity-sensitive features for learning a linkage function, thereby tailoring
disambiguation to non-Western author names whenever necessary.

---

_Structure of the repository:_
- `beard/`: Source code.
- `data/`: Author disambiguation data extracted from INSPIRE.
- `paper/`: Latex files of the paper.

_License:_ BSD 3 clause

_Contact:_ Gilles Louppe (@glouppe, <g.louppe@gmail.com>)