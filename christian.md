

```python
init_notebook_mode(connected=True)
from plotly import __version__
from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot

print(__version__)
```


<script>requirejs.config({paths: { 'plotly': ['https://cdn.plot.ly/plotly-latest.min']},});if(!window.Plotly) {{require(['plotly'],function(plotly) {window.Plotly=plotly;});}}</script>


    1.12.9



```python
from plotly.graph_objs import Bar, Scatter, Figure, Layout

plot([Scatter(x=[1, 2, 3], y=[3, 1, 6])])
```




    'file:///Users/christianweber/github/notebooks/temp-plot.html'




```python
import plotly.plotly as py

trace = Bar(x = [1, 2, 3], y = [4, 5, 6])
data = [trace]

iplot(data)
```


<div id="c4c34437-21db-456d-8988-00cef3c465b7" style="height: 525px; width: 100%;" class="plotly-graph-div"></div><script type="text/javascript">require(["plotly"], function(Plotly) { window.PLOTLYENV=window.PLOTLYENV || {};window.PLOTLYENV.BASE_URL="https://plot.ly";Plotly.newPlot("c4c34437-21db-456d-8988-00cef3c465b7", [{"x": [1, 2, 3], "type": "bar", "y": [4, 5, 6]}], {}, {"linkText": "Export to plot.ly", "showLink": true})});</script>



```python


```


```python

```
