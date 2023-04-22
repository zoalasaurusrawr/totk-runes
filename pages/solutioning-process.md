# Solutioning Process

As a primer for this process, you'll want to check out the documents "Pre-Analysis" and "Wall Art Cipher Text" at a minimum. 

## Terms

**Rune**

A symbol that does not match a known alphabet

**Syllable**

In the context of Kana, refers to either a single Hiragan or Katakana character. For Romaji, it refers to a pair of characters.

**Digraph**

Unlike English, Romaji digraphs are three characters for the sake of this solutioning process. They can still be represented by one character in Kana. An example of this is "shi" which is represented by し in Hiragana.

**N-Gram**

A section of text for a specified size. For example, a 2-gram might be NO, 3-gram might be SHI, and so on.

# Steps

## 1. Develop an inventory of the symbols (runes)

- Catalog all the symbols and arbitrarily assign a single character to them. These single characters are known as "key characters" for the sake of this process. This is captured in the document "rune-inventory".

## 2. Transliterate all of the runes to key characters
   
- This step develops proto-ciphertext. Transliteration should be deterministic and for the sake of this process, it's going to be transliterated by reading the runes from top to bottom, right to left.

## 3. Perform frequency analysis on the ciphertext and find (or create) a frequency analysis of the theorized language, in this case Japanese represented as Romaji.

- 3.1 Sort the frequencies of the ciphertext and source text frequency in descending order. For the sake of following along, you can enter the ciphertext and sourctext into a tool such as https://www.boxentriq.com/code-breaking/frequency-analysis. Most any frequency analysis tools will work here, just make sure they provide options to change the n-gram size and/or stepping. You can see the full frequency analysis in the document "wall-art-cipher-analysis".

## 4. Replace the ciphertext characters with characters based on frequency. 

- As an example, if X has the highest frequency in the ciphertext and A has the highest frequency in the source text analysis, replace with an A. An important and often overlooked step is to try to replace characters based on consonant & vowel patterns. Romaji often follows patterns like: 
  
- CVCV (For series of syllables)
- CVV (For syllable followed by a vowel)
- CCV (For common diagrams)
- VVC (For vowel first syllables preceded by a vowel)

For this process, I took the first seven characters in the ciphertext and generated a pattern of CVCVCVC and then used those character to fill out the pattern for the rest of the text on the left panel, resulting in a pattern of:  CVCVVCVVCVCVVVCCCVC.

You can see a progress of the substitution process in the "Solution v0.1" document. **It's not exhaustive** and only included for demonstrative purposes.
