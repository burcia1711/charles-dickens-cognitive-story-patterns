## Mental Models and Narrative Structures in Charles Dickens' Novels

This repository is created for my personal interest in Victorian Literature (here, Charles Dickens particularly). It aims to identify and analyse recurring cognitive patterns in the narrative structures and character arcs of Charles Dickens’ novels, using frameworks from cognitive science, such as the theory of mind, mental schemas, narrative comprehension, and identity construction.

### 🧠 Coding Goals
#### - Detect Cognitive Verbs / Mental State Terms
Automate detection of Theory of Mind (ToM) instances in Dickens' texts.

#### - Analyze Narrative Perspective Shifts
Track which characters are being "mentalised" and when.

### 🧰 Libraries & Tools To Use
spaCy (NLP pipeline for sentence and token analysis)

NLTK or TextBlob (for sentiment or lexical stats)

matplotlib / seaborn (for visualizing trends)

pandas (for structured analysis)

transformers (for BERT-based emotion/sentiment detection (later?))

### 🤯 Ideas
* Compare the emotional arc of a narrator vs other characters (can only be done for Great Expectations and David Copperfield, i guess).
* Detect general emotional trends (do for all)

| Novel                                      | First-Person? | Narrator             | Main Characters                                                                 |
|-------------------------------------------|----------------|----------------------|----------------------------------------------------------------------------------|
| The Pickwick Papers (1836)                | ❌ No           | Omniscient           | Mr. Pickwick, Sam Weller, Nathaniel Winkle, Augustus Snodgrass                  |
| Oliver Twist (1837–39)                    | ❌ No           | Omniscient           | Oliver Twist, Fagin, Nancy, Bill Sikes, Mr. Brownlow                            |
| Nicholas Nickleby (1838–39)               | ❌ No           | Omniscient           | Nicholas Nickleby, Smike, Ralph Nickleby, Kate, Mrs. Nickleby                   |
| The Old Curiosity Shop (1840–41)          | ❌ No (intro is 1st person, rest 3rd) | Omniscient | Little Nell, Grandfather, Quilp                                                 |
| Barnaby Rudge (1841)                      | ❌ No           | Omniscient           | Barnaby Rudge, Gabriel Varden, Hugh, Lord George Gordon                         |
| Martin Chuzzlewit (1843–44)               | ❌ No           | Omniscient           | Martin (Sr. and Jr.), Tom Pinch, Seth Pecksniff, Mark Tapley                    |
| Dombey and Son (1846–48)                  | ❌ No           | Omniscient           | Paul Dombey, Florence Dombey, Mr. Carker, Edith Granger                         |
| David Copperfield (1849–50)               | ✅ Yes          | David Copperfield     | Agnes Wickfield, Dora Spenlow, Uriah Heep, Mr. Micawber, Steerforth            |
| Bleak House (1852–53)                     | 🌓 Mixed        | Esther + Omniscient   | Esther Summerson, Lady Dedlock, Mr. Jarndyce, Tulkinghorn                       |
| Hard Times (1854)                         | ❌ No           | Omniscient           | Thomas Gradgrind, Louisa, Sissy Jupe, Josiah Bounderby                          |
| Little Dorrit (1855–57)                   | ❌ No           | Omniscient           | Amy Dorrit, Arthur Clennam, Mr. Dorrit, Rigaud                                  |
| A Tale of Two Cities (1859)               | ❌ No           | Omniscient           | Sydney Carton, Charles Darnay, Lucie Manette, Madame Defarge                    |
| Great Expectations (1860–61)              | ✅ Yes          | Pip                  | Estella, Joe Gargery, Miss Havisham, Magwitch, Biddy                            |
| Our Mutual Friend (1864–65)               | ❌ No           | Omniscient           | Bella Wilfer, John Harmon, Lizzie Hexam, Mr. Boffin                             |
| The Mystery of Edwin Drood (unfinished, 1870) | ❌ No        | Omniscient           | Edwin Drood, John Jasper, Rosa Bud, Neville Landless                            |

