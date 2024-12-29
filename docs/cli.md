# CLI Usage 💻

Obfuscate a Python script directly from the command line:
Run Kannadafy directly from the command line using:
[Prefferable For Windows]
```bash
python -m Kannadafy [options]
```
---
[Prefferable For Linux]
```bash
Kannadafy [options]
```


### Advanced Options
- **Custom Words**: Use `-w` or `--words` to specify custom Kannada words for obfuscation.
- **Default Words**: If no words are specified, Kannadafy uses its default set of Kannada letters.
---

### **Command-Line Options**
| Option             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `-i` / `--input`   | Input Python file to obfuscate (e.g., `script.py`).                         |
| `-o` / `--output ` | Output file for the obfuscated script (e.g., `obfuscated_script.py`).       |
| `-w` / `--words`   | Use Default Kannada words for obfuscation .                                 |
| `-v` / `--version` | Display the version of Kannadafy.                                           |

---
```bash
python -m Kannadafy -i your_script.py -o obfuscated_script.py
```
---
- **You can use for default words**
```bash
python -m Kannadafy -i input.py -o output.py -w
```
---
