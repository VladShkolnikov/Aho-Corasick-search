# Aho-Corasick-search

This code is a python realization of a Aho-Corasick algorithm. The aim of the code is to find the number of occurences of strings s1,s2,s3,...,sn in a given string a. The class Tree is trie Tree data structure, supplemented with suffix links (see Aho-Corasick algorithm for details). A constructor accepts a variable number of parameters, each of which must be a string, and constructs the tree. The function occurences the uses this tree to efficiently search and count all occurences of s1,s2,....,sn in the string a. 
