## Guide for setting up codespace

1. Create new repo and name it
2. I used a template vs-code-setup (can clone this from my [github](https://github.com/stevecrawshaw/vs-code-setup))
3. install uv from the terminal with 'curl -LsSf https://astral.sh/uv/install.sh | sh'
4. Install the Python and Jupyter extensions
5. Test a script with jupyter code fences #%%
6. If the `.venv` isn't found (e.g. can't resolve polars import), hover over the underlined word, select Quick Fix, Select a Different Interpreter, and select the one that starts `.venv..`
7. Now imports should be resolvable and you can start to code