# Ubuntu Plot Fix

Ubuntu needs to be properly configured to allow `matplotlib` plot windows.  
An alternative is to use `plt.savefig` to write the plot to a `png` file. 

## btap Example
```python
def figNum():
    figNum.counter += 1
    return "{0:02d}".format(figNum.counter)
figNum.counter = 0
FIGPREFIX = 'ch01_fig'

import matplotlib
from matplotlib import pyplot as plt

plot_params = {'figure.figsize': (8, 6),
               'axes.labelsize': 'small',
               'axes.titlesize': 'small',
               'xtick.labelsize': 'small',
               'ytick.labelsize':'small',
               'figure.dpi': 100}
# adjust matplotlib defaults
matplotlib.rcParams.update(plot_params)

plt.tight_layout()
plt.savefig('{}{}_value_distribution_box.png'.format(FIGPREFIX, figNum()))
```
>Note:
> * `def figNum()` avoids hard coding figure numbers
> * `FIGPREFIX` provides a standard prefix to the file name
> * `plot_params` provides standard settings for `matplotlib`
> * `plt.tight_layout()` expands the margin to include all text

## References
* [matplotlib.rcsetup](https://matplotlib.org/stable/api/rcsetup_api.html#module-matplotlib.rcsetup)