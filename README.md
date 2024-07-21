# appllm_tools

## start a new env
```bash
conda deactivate (exit my old env which is not working when pip install python-fasthtml)

mamba create -n fasthtml "python>=3.10" (issue 1: python=3.9 won't work for fasthtml, it requires python >=3.10)
mamba activate fasthtml
pip install python-fasthtml (it will work now)
mamba deactivate 
```

## run local dev mode

```
git clone git@github.com:AnswerDotAI/fasthtml.git
cd fasthtml
pip install -e . (issue 2: it will require you to update python >= 3.10, run the line below to solve this issue)
mamba install "python>=3.10" ( to upgrade your env with python >= 3.10)
pip install -e . (now, should run without a problem and fasthtml is install properly)
```

## run example app locally

```
cd examples
python basic_app.py (should work now. issue 4: But if you use vpn, then turn it off and refresh the page. The first time starting the app will take a little time, but the second time is smooth)
ctrl + c (issue 5: to quit the app properly)

```

