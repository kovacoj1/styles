# Publication-Ready Plotting Styles

High-quality settings for plots and figures.

- [`python`]()
```python
import matplotlib.pyplot as plt
%matplotlib inline

%config InlineBackend.figure_formats = ['svg', 'pdf']
plt.style.use('../.aux/presentation.mplstyle')
```

- [`matlab`]()
```matlab
run('./style.m');
```
