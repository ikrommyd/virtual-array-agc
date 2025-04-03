# Analysis Grand Challenge (AGC) demo with virtual arrays

## How to run it

First, create a python virtual environment any way you like and install the necessary requirements.\
For example with `uv`:
```bash
uv venv --python 3.12 --seed
source .venv/bin/activate
uv pip install -r requirements.txt
```

Then download the root files to run the demo (this will probably take a while as it is ~40GB of data):
```bash
python download_files.py --json-file fileset.json --target-dir root_files --key all --num-threads <NUMBER_OF_THREADS>
```

Finally, open jupyter lab and run the demo notebook:
```bash
jupyter lab
```
Then open the notebook `ttbar_analysis_pipeline.ipynb` and do whatever you like.