# Penman to JSON Converter

The following command converts the JSON files generated by StreamSide to the Penman notation:

```bash
python -m streamside.penman_to_json -i INPUT_PATH [-o OUTPUT_PATH]
```
* `-i` or `--input`: the path to a Penman file or a directory containing Penman files (required).
* `-o` or `--output`: the path to the JSON output file(s) (default: the input directory).