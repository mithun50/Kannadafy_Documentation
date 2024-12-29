# How Kannadafy Works 🛠

## Encoding Characters
Each character in your Python script is mapped to a unique Kannada character.
---
## Wrapping with exec()
To ensure the obfuscated script remains functional, it’s wrapped in a Python `exec()` statement.
---
## **Error Handling**

1. **File Not Found**:
   - If the `.py` extension is omitted in the input file, Kannadafy automatically checks for a file with the `.py` extension.

2. **Missing Output File Name**:
   - Kannadafy ensures that the output file has a `.py` extension.

3. **Invalid Characters in Alphabet/Words**:
   - Kannadafy validates the input alphabet and words to ensure compatibility.

---
## Customization
You can specify custom Kannada words for obfuscation using the `-w` or `--words` option.
---
## Some Examples
- ## Let`s we Consider the Python Script "main.py"
```python
#main.py
print("ನಮಸ್ಕಾರ")
```
- **And When I Obfuscate the `main.py` with default Kannada Letters**
```python
#obf_kan_lett_main.py
exec("".join(map(chr,[int("".join(str({'ಅ': 0,
 'ಅ:': 14,
 'ಅಂ': 13,
 'ಆ': 1,
 'ಇ': 2,
 'ಈ': 3,
 'ಉ': 4,
 'ಊ': 5,
 'ಋ': 6,
 'ಎ': 7,
 'ಏ': 8,
 'ಐ': 9,
 'ಒ': 10,
 'ಓ': 11,
 'ಔ': 12,
 'ಕ': 15,
 'ಖ': 16,
 'ಗ': 17,
 'ಘ': 18,
 'ಙ': 19,
 'ಚ': 20,
 'ಛ': 21,
 'ಜ': 22,
 'ಝ': 23,
 'ಞ': 24,
 'ಟ': 25,
 'ಠ': 26,
 'ಡ': 27,
 'ಢ': 28,
 'ಣ': 29,
 'ತ': 30,
 'ಥ': 31,
 'ದ': 32,
 'ಧ': 33,
 'ನ': 34,
 'ಪ': 35,
 'ಫ': 36,
 'ಬ': 37,
 'ಭ': 38,
 'ಮ': 39,
 'ಯ': 40,
 'ರ': 41,
 'ಲ': 42,
 'ಳ': 48,
 'ವ': 43,
 'ಶ': 44,
 'ಷ': 45,
 'ಸ': 46,
 'ಹ': 47}[i]) for i in x.split())) for x in
"ಆ ಆ ಇ  ಆ ಆ ಉ  ಆ ಅ ಊ  ಆ ಆ ಅ  ಆ ಆ ಋ  ಉ ಅ  ಈ ಉ  ಈ ಇ ಉ ಅ  ಈ ಇ ಉ ಋ  ಈ ಇ ಊ ಋ\
  ಈ ಇ ಎ ಎ  ಈ ಇ ಇ ಆ  ಈ ಇ ಋ ಇ  ಈ ಇ ಉ ಏ  ಈ ಉ  ಉ ಆ  ಆ ಅ"
.split("  ")])))
```


- **And When I Obfuscate the `main.py` with default Kannada Words.**
```python
#obf_kan_words_main.py
exec("".join(map(chr,[int("".join(str({'ಅಪ್ಪ': 1,
 'ಅಮ್ಮ': 0,
 'ಕನಸು': 3,
 'ಗೌತಮ್.ಎಂಸಿ': 14,
 'ಜೀವನ': 6,
 'ನದಿ': 4,
 'ನಮಸ್ಕಾರ': 12,
 'ಬೆಳಕು': 8,
 'ಮಗು': 2,
 'ಮಳೆ': 7,
 'ಮಿಥುನ್ ಗೌಡ.ಬಿ': 13,
 'ಮೆಚ್ಚುಗೆ': 11,
 'ರಾಹುಲ್.ವಿ': 15,
 'ಸಂಬಂಧ': 9,
 'ಸಮಯ': 5,
 'ಹಸಿರು': 10}[i]) for i in x.split())) for x in
"ಅಪ್ಪ ಅಪ್ಪ ಮಗು  ಅಪ್ಪ ಅಪ್ಪ ನದಿ  ಅಪ್ಪ ಅಮ್ಮ ಸಮಯ  ಅಪ್ಪ ಅಪ್ಪ ಅಮ್ಮ  ಅಪ್ಪ ಅಪ್ಪ\
 ಜೀವನ  ನದಿ ಅಮ್ಮ  ಕನಸು ನದಿ  ಕನಸು ಮಗು ನದಿ ಅಮ್ಮ  ಕನಸು ಮಗು ನದಿ ಜೀವನ  ಕನಸು \
ಮಗು ಸಮಯ ಜೀವನ  ಕನಸು ಮಗು ಮಳೆ ಮಳೆ  ಕನಸು ಮಗು ಮಗು ಅಪ್ಪ  ಕನಸು ಮಗು ಜೀವನ ಮಗು  \
ಕನಸು ಮಗು ನದಿ ಬೆಳಕು  ಕನಸು ನದಿ  ನದಿ ಅಪ್ಪ  ಅಪ್ಪ ಅಮ್ಮ"
.split("  ")])))
```
---
