# workshop_DAS-DAGA-2025
A collection of jupyter notebooks, presented at the DAS|DAGA 2025 conference.

Installation with conda:

* install `nbclassic` to use the classic notebook interface

```bash
conda install --yes --file requirements.txt --channel acoular
```

Run the notebooks:

```bash
jupyter nbclassic
```

## Directory Structure

Time data should be stored in a directory: `/data`. For images/figures use the `/img` directory.
Jupyter notebooks should be stored in the top level directory with the naming sheme: `<presentation_title_with_underscores_and_without_'Acoular Workshop:>.ipynb`. E.g. for the presentation `Acoular Workshop: Getting Started with Acoular` the name of the notebook should be `Getting_Started_with_Acoular.ipynb`.

## Notebooks
For css styling, first notebook cell should include

```python
from IPython.core.display import HTML
def css_styling():
    styles = open("./custom.css", "r").read()
    return HTML(styles)
css_styling()
```

