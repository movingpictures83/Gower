# Gower
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: vegan_2.5.6

PluMA plugin to compute dissimilarity between samples, using the Gower Index (Gower, 1971).
The plugin accepts input in the form of a CSV file, where rows represent samples and columns
abundances of community members.
It then produces an output file, also in CSV format, where rows and columns represent samples.
Entry (i, j) will then contain the dissimilarity between samples i and j in the input file.
