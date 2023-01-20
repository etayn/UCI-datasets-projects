```python
import pandas as pd
```


```python
data = pd.read_csv("data/abalone.data" , sep = "," , header= None)
```


```python
data.columns = ["sex" , "length" , "diameter" , "height" , "whole_weight" , "shucked_weight",
               "viscera_weight" , "shell_weight" , "rings"]
```


```python
data
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>sex</th>
      <th>length</th>
      <th>diameter</th>
      <th>height</th>
      <th>whole_weight</th>
      <th>shucked_weight</th>
      <th>viscera_weight</th>
      <th>shell_weight</th>
      <th>rings</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>M</td>
      <td>0.455</td>
      <td>0.365</td>
      <td>0.095</td>
      <td>0.5140</td>
      <td>0.2245</td>
      <td>0.1010</td>
      <td>0.1500</td>
      <td>15</td>
    </tr>
    <tr>
      <th>1</th>
      <td>M</td>
      <td>0.350</td>
      <td>0.265</td>
      <td>0.090</td>
      <td>0.2255</td>
      <td>0.0995</td>
      <td>0.0485</td>
      <td>0.0700</td>
      <td>7</td>
    </tr>
    <tr>
      <th>2</th>
      <td>F</td>
      <td>0.530</td>
      <td>0.420</td>
      <td>0.135</td>
      <td>0.6770</td>
      <td>0.2565</td>
      <td>0.1415</td>
      <td>0.2100</td>
      <td>9</td>
    </tr>
    <tr>
      <th>3</th>
      <td>M</td>
      <td>0.440</td>
      <td>0.365</td>
      <td>0.125</td>
      <td>0.5160</td>
      <td>0.2155</td>
      <td>0.1140</td>
      <td>0.1550</td>
      <td>10</td>
    </tr>
    <tr>
      <th>4</th>
      <td>I</td>
      <td>0.330</td>
      <td>0.255</td>
      <td>0.080</td>
      <td>0.2050</td>
      <td>0.0895</td>
      <td>0.0395</td>
      <td>0.0550</td>
      <td>7</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>4172</th>
      <td>F</td>
      <td>0.565</td>
      <td>0.450</td>
      <td>0.165</td>
      <td>0.8870</td>
      <td>0.3700</td>
      <td>0.2390</td>
      <td>0.2490</td>
      <td>11</td>
    </tr>
    <tr>
      <th>4173</th>
      <td>M</td>
      <td>0.590</td>
      <td>0.440</td>
      <td>0.135</td>
      <td>0.9660</td>
      <td>0.4390</td>
      <td>0.2145</td>
      <td>0.2605</td>
      <td>10</td>
    </tr>
    <tr>
      <th>4174</th>
      <td>M</td>
      <td>0.600</td>
      <td>0.475</td>
      <td>0.205</td>
      <td>1.1760</td>
      <td>0.5255</td>
      <td>0.2875</td>
      <td>0.3080</td>
      <td>9</td>
    </tr>
    <tr>
      <th>4175</th>
      <td>F</td>
      <td>0.625</td>
      <td>0.485</td>
      <td>0.150</td>
      <td>1.0945</td>
      <td>0.5310</td>
      <td>0.2610</td>
      <td>0.2960</td>
      <td>10</td>
    </tr>
    <tr>
      <th>4176</th>
      <td>M</td>
      <td>0.710</td>
      <td>0.555</td>
      <td>0.195</td>
      <td>1.9485</td>
      <td>0.9455</td>
      <td>0.3765</td>
      <td>0.4950</td>
      <td>12</td>
    </tr>
  </tbody>
</table>
<p>4177 rows × 9 columns</p>
</div>




```python

```
