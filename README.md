# Fourthbrain

**1: VENV Setup**

`python3 -m venv fourthbrain_venv`

`source fourthbrain_venv/bin/activate`

**2: Use Jupyter Notebook in VSCode & Use venv Python Kernel**

`python3 -m pip install ipykernel`

`python3 -m ipython kernel install --user --name==fourthbrain_venv`

**3: Install Requirements**

`python3 -m pip install -r requirements.txt`

`python3 -m pip install statsmodels `

Note, if you still cant select the venv kernel in your python notebook, try adding the venv path directly to your workspace settigns json: 

`"settings": { "python.pythonPath": "/absolute/path/to/fourthbrain_venv/lib/python3.8"`
