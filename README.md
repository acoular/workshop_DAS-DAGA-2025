# workshop_DAS-DAGA-2025
A collection of jupyter notebooks, presented at the DAS|DAGA 2025 conference.

Installation with conda:

* install `nbclassic` to use the classic notebook interface

```bash
conda install --yes --file requirements.txt --channel acoular
```

Run the notebooks:

```bash
jupyer nbclassic
```


## Notebooks
For css styling, first notebook cell should include

```python
from IPython.core.display import HTML
def css_styling():
    styles = open("./custom.css", "r").read()
    return HTML(styles)
css_styling()
```