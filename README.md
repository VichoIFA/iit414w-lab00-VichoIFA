# Vicente Ignacio Fuentes Arriagada - VichoIFA - IIT414W - 3/11/2026

**System info**

CachyOS Linux 6.19.6-2-cachyos - Python 3.13.11 - pip 25.3

**Setup instructions**

1) Create a Python virtual enviroment:

```bash
python -m venv venv
```

2) Activate virtual enviroment:

```bash
source venv/bin/activate
```

3) Install all the packages listed in 'requirements.txt'

```bash
pip install -r requirements.txt
```

4) Execute the jupyter notebook selecting the kernel of virtual enviroment on the IDE

**How to excecute notebooks**

When the kernel is selected, press the 'play' button of each cell or excecute:

```bash
jupyter lab
```

**Problems encountered**

1) The aplication 'Konsole' of CachyOS does not work to activate the virtual enviroment, and i lost a lot of time to find it

2) To excecute a jupyter notebook with a custom kernel it was necessary to install the package ipykernel

  (f) Expected outputs: Brief description of what a successful run looks like (e.g., "setup_check.ipynb prints a 6-row package table and 'All checks passed ✓'").