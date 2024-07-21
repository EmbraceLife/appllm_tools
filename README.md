# appllm_tools

## start a new env
```bash
conda deactivate

mamba create -n fasthtml "python>=3.10" (issue 1: python=3.9 won't work for fasthtml, it requires python >=3.10)
mamba activate fasthtml
pip install python-fasthtml (issue 2: if still only install python-fasthtml version , try the one below)
pip install python-fasthtml==0.1.7 (issue 3: if still can't run example like `python basic_app.py`, then run the local dev mode)
mamba deactivate 
```

## run local dev mode

```
git clone git@github.com:AnswerDotAI/fasthtml.git
cd fasthtml
pip install -e .
cd examples
python basic_app.py (should work now)
```
