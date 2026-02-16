## SEQUENCE TRANSLATOR ##
3rd mini project of my python learning process.

## FEATURES:
1. mini project that converts a dna sequence fasta file into a readable string first.
2. then it is converted into a list of triplet codons, through a function.
3. those codons are then translated through a dictionary having codons [keys] and amino acids [value].
4. input is given as file and output comes out as the list of codons, and their respective amino acids.

## POINTS I LEARNED ALONG THE WAY:
1. using main() to control multi-functional flow of a code, acts as an entry point and only requires input once.
2. using __name__ so that the main() is later reusable and importable into other program.
3. file handing i/o, using with statement over manually opening and closing a file every time, along with some file operations.
4. enforced string slicing and indexing.
5. copy pasted codon-AA pairs and made it into a dictionary and accessed it using dictionary methods.
