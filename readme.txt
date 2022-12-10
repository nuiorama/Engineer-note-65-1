
Export PDF
------------------
https://miktex.org/download


Latex
-------------------
from IPython.display import display, Math
display(Math(r'Dims: {}x{}m \\ Area: {}m^2 \\ Volume: {}m^3'.format(a, round(b,2), P, V)))
####
from IPython.display import display, Math
LATEX = lambda s: display(Math(Latex(s)))

Engineer Formatter
-------------------
from matplotlib.ticker import EngFormatter
eng = lambda n: EngFormatter()(n)

conda
------------------
conda install -c conda-forge jupyter_contrib_nbextensions 
