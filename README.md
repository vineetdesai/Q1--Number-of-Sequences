Q1--Number-of-Sequences
=======================
# Assignment 1: Count the total number of sequences
add = 0
for line in file("shortversion.fasta", 'r'):
    if line.startswith('>'):
        add = add + 1
print "The file contains", add, "sequences"
