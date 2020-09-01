# HackerRank-Python-capital-First-Letter
import string

words = raw_input().split(' ')
for i in xrange(len(words)):
    words[i] = string.capitalize(words[i])

print ' '.join(words)
