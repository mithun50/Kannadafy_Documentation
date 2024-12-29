# Using Kannadafy in Your Python Code 🧑‍💻

-  **Use Kannadafy programmatically in your code:**
```python
from Kannadafy import obfuscate, DEFAULT_ALPHABET, DEFAULT_WORDS

# Example script content (from a file or string)
input_file = "example.py"
output_file = "obfuscated_example.py"

# 1. Using default Kannada letters
obfuscate(input_file, output_file, custom_alphabet=DEFAULT_ALPHABET)

# 2. Using default Kannada words
obfuscate(input_file, output_file, custom_alphabet=DEFAULT_WORDS)

```

---
