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
pip install -e . (issue 3: it will require you to update python >= 3.10, run the line below to solve this issue)
mamba install "python>=3.10"
pip install -e . (now, should run without a problem and fasthtml is install properly)
cd examples
python basic_app.py (should work now. issue 4: But if you use vpn, then turn it off and refresh the page. The first time starting the app will take a little time, but the second time is smooth)
ctrl + c (issue 5: to quit the app properly)
```
