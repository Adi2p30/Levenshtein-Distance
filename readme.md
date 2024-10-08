The Levenshtein distance, also called the edit distance, is a way to measure how different two sequences of characters (usually strings) are. It shows the least number of single-character changes (insertions, deletions, or substitutions) needed to turn one string into another.

## Definition
Definition
Given two strings a and b, the Levenshtein distance is calculated as the minimum number of edits (insertion, deletion, substitution) needed to change one string into the other. If |a| is the length of string a and |b| is the length of string b, then the function lev(a, b) can be defined as follows:

If either string is empty, the distance is the length of the other string. \
If the first characters of a and b are the same, we ignore them and compute the distance for the rest of the strings.

Otherwise, we compute the minimum cost by considering:
Deleting a character from a.\
Inserting a character into a.\
Substituting a character in a for one in b.

