
Setup
----------------
conda create -n jupyter python=3.11
conda install jupyterlab sympy pandas

Engineer Formatter
-------------------
from matplotlib.ticker import EngFormatter
eng = lambda n: EngFormatter()(n)

Latex
-------------------
from IPython.display import display, Math
display(Math(r'Dims: {}x{}m \\ Area: {}m^2 \\ Volume: {}m^3'.format(a, round(b,2), P, V)))
####
from IPython.display import display, Math
LATEX = lambda s: display(Math(Latex(s)))

Export PDF
------------------
https://miktex.org/download

