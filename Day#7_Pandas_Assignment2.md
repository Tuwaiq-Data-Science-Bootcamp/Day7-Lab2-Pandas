# Q1: Import pandas library


```python
# write your code here ^_^
import pandas as pd
```

# Q2: Read instagram_users.csv file


```python
# write your code here ^_^
read = pd.read_csv('instagram_users.csv')
read
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
      <th>pos</th>
      <th>flw</th>
      <th>flg</th>
      <th>bl</th>
      <th>pic</th>
      <th>lin</th>
      <th>cl</th>
      <th>cz</th>
      <th>ni</th>
      <th>erl</th>
      <th>erc</th>
      <th>lt</th>
      <th>hc</th>
      <th>pr</th>
      <th>fo</th>
      <th>cs</th>
      <th>pi</th>
      <th>class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>44</td>
      <td>48</td>
      <td>325</td>
      <td>33</td>
      <td>1</td>
      <td>0</td>
      <td>12</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.111111</td>
      <td>0.094985</td>
      <td>f</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>66</td>
      <td>321</td>
      <td>150</td>
      <td>1</td>
      <td>0</td>
      <td>213</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>14.390000</td>
      <td>1.97</td>
      <td>0.000</td>
      <td>1.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.206826</td>
      <td>230.412857</td>
      <td>f</td>
    </tr>
    <tr>
      <th>2</th>
      <td>33</td>
      <td>970</td>
      <td>308</td>
      <td>101</td>
      <td>1</td>
      <td>1</td>
      <td>436</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>10.100000</td>
      <td>0.30</td>
      <td>0.000</td>
      <td>2.500</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.572174</td>
      <td>43.569939</td>
      <td>f</td>
    </tr>
    <tr>
      <th>3</th>
      <td>70</td>
      <td>86</td>
      <td>360</td>
      <td>14</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1.000000</td>
      <td>0.000</td>
      <td>0.780000</td>
      <td>0.06</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>1.000000</td>
      <td>5.859799</td>
      <td>f</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3</td>
      <td>21</td>
      <td>285</td>
      <td>73</td>
      <td>1</td>
      <td>0</td>
      <td>93</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>14.290000</td>
      <td>0.00</td>
      <td>0.667</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.300494</td>
      <td>0.126019</td>
      <td>f</td>
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
      <th>65321</th>
      <td>13</td>
      <td>145</td>
      <td>642</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>7</td>
      <td>0.461538</td>
      <td>0.000</td>
      <td>14.270000</td>
      <td>0.58</td>
      <td>0.000</td>
      <td>0.077</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.192308</td>
      <td>1745.291260</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65322</th>
      <td>652</td>
      <td>3000</td>
      <td>1300</td>
      <td>146</td>
      <td>1</td>
      <td>1</td>
      <td>384</td>
      <td>0.000000</td>
      <td>0.389</td>
      <td>8.520000</td>
      <td>0.13</td>
      <td>0.000</td>
      <td>1.611</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.169917</td>
      <td>54.629120</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65323</th>
      <td>1500</td>
      <td>3700</td>
      <td>3200</td>
      <td>147</td>
      <td>1</td>
      <td>1</td>
      <td>129</td>
      <td>0.000000</td>
      <td>0.111</td>
      <td>9.390000</td>
      <td>0.31</td>
      <td>0.722</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.058908</td>
      <td>129.802048</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65324</th>
      <td>329</td>
      <td>1500</td>
      <td>1800</td>
      <td>218</td>
      <td>1</td>
      <td>1</td>
      <td>290</td>
      <td>0.055556</td>
      <td>0.000</td>
      <td>6.350000</td>
      <td>0.26</td>
      <td>0.222</td>
      <td>0.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.103174</td>
      <td>53.402840</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65325</th>
      <td>206</td>
      <td>659</td>
      <td>608</td>
      <td>27</td>
      <td>1</td>
      <td>0</td>
      <td>77</td>
      <td>0.000000</td>
      <td>0.333</td>
      <td>25.549999</td>
      <td>0.53</td>
      <td>0.222</td>
      <td>0.222</td>
      <td>0.0</td>
      <td>0.167</td>
      <td>0.017505</td>
      <td>604.981445</td>
      <td>r</td>
    </tr>
  </tbody>
</table>
<p>65326 rows × 18 columns</p>
</div>



# Q3: Print the number of rows and columns contained in the dataset


```python
# write your code here ^_^

rows = len(read.axes[0])

cols = len(read.axes[1])
print(rows,cols)
```

    65326 18


# Q4: Print the size of dataset


```python
# write your code here ^_^
s=read.size
s
```




    1175868



# Q5: Print the data type of each column


```python
# write your code here ^_^
read.dtypes
```




    pos        int64
    flw        int64
    flg        int64
    bl         int64
    pic        int64
    lin        int64
    cl         int64
    cz       float64
    ni       float64
    erl      float64
    erc      float64
    lt       float64
    hc       float64
    pr       float64
    fo       float64
    cs       float64
    pi       float64
    class     object
    dtype: object



# Q6: Print the entire dataset
Note: if your dataset contains more than 60 rows, only the first 5 rows and the last 5 rows will be printed.


```python
# write your code here ^_^
display(read)
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
      <th>pos</th>
      <th>flw</th>
      <th>flg</th>
      <th>bl</th>
      <th>pic</th>
      <th>lin</th>
      <th>cl</th>
      <th>cz</th>
      <th>ni</th>
      <th>erl</th>
      <th>erc</th>
      <th>lt</th>
      <th>hc</th>
      <th>pr</th>
      <th>fo</th>
      <th>cs</th>
      <th>pi</th>
      <th>class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>44</td>
      <td>48</td>
      <td>325</td>
      <td>33</td>
      <td>1</td>
      <td>0</td>
      <td>12</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.111111</td>
      <td>0.094985</td>
      <td>f</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>66</td>
      <td>321</td>
      <td>150</td>
      <td>1</td>
      <td>0</td>
      <td>213</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>14.390000</td>
      <td>1.97</td>
      <td>0.000</td>
      <td>1.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.206826</td>
      <td>230.412857</td>
      <td>f</td>
    </tr>
    <tr>
      <th>2</th>
      <td>33</td>
      <td>970</td>
      <td>308</td>
      <td>101</td>
      <td>1</td>
      <td>1</td>
      <td>436</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>10.100000</td>
      <td>0.30</td>
      <td>0.000</td>
      <td>2.500</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.572174</td>
      <td>43.569939</td>
      <td>f</td>
    </tr>
    <tr>
      <th>3</th>
      <td>70</td>
      <td>86</td>
      <td>360</td>
      <td>14</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1.000000</td>
      <td>0.000</td>
      <td>0.780000</td>
      <td>0.06</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>1.000000</td>
      <td>5.859799</td>
      <td>f</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3</td>
      <td>21</td>
      <td>285</td>
      <td>73</td>
      <td>1</td>
      <td>0</td>
      <td>93</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>14.290000</td>
      <td>0.00</td>
      <td>0.667</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.300494</td>
      <td>0.126019</td>
      <td>f</td>
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
      <th>65321</th>
      <td>13</td>
      <td>145</td>
      <td>642</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>7</td>
      <td>0.461538</td>
      <td>0.000</td>
      <td>14.270000</td>
      <td>0.58</td>
      <td>0.000</td>
      <td>0.077</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.192308</td>
      <td>1745.291260</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65322</th>
      <td>652</td>
      <td>3000</td>
      <td>1300</td>
      <td>146</td>
      <td>1</td>
      <td>1</td>
      <td>384</td>
      <td>0.000000</td>
      <td>0.389</td>
      <td>8.520000</td>
      <td>0.13</td>
      <td>0.000</td>
      <td>1.611</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.169917</td>
      <td>54.629120</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65323</th>
      <td>1500</td>
      <td>3700</td>
      <td>3200</td>
      <td>147</td>
      <td>1</td>
      <td>1</td>
      <td>129</td>
      <td>0.000000</td>
      <td>0.111</td>
      <td>9.390000</td>
      <td>0.31</td>
      <td>0.722</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.058908</td>
      <td>129.802048</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65324</th>
      <td>329</td>
      <td>1500</td>
      <td>1800</td>
      <td>218</td>
      <td>1</td>
      <td>1</td>
      <td>290</td>
      <td>0.055556</td>
      <td>0.000</td>
      <td>6.350000</td>
      <td>0.26</td>
      <td>0.222</td>
      <td>0.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.103174</td>
      <td>53.402840</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65325</th>
      <td>206</td>
      <td>659</td>
      <td>608</td>
      <td>27</td>
      <td>1</td>
      <td>0</td>
      <td>77</td>
      <td>0.000000</td>
      <td>0.333</td>
      <td>25.549999</td>
      <td>0.53</td>
      <td>0.222</td>
      <td>0.222</td>
      <td>0.0</td>
      <td>0.167</td>
      <td>0.017505</td>
      <td>604.981445</td>
      <td>r</td>
    </tr>
  </tbody>
</table>
<p>65326 rows × 18 columns</p>
</div>


# Q7: Print the first 5 rows


```python
# write your code here ^_^
read.head(5)
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
      <th>pos</th>
      <th>flw</th>
      <th>flg</th>
      <th>bl</th>
      <th>pic</th>
      <th>lin</th>
      <th>cl</th>
      <th>cz</th>
      <th>ni</th>
      <th>erl</th>
      <th>erc</th>
      <th>lt</th>
      <th>hc</th>
      <th>pr</th>
      <th>fo</th>
      <th>cs</th>
      <th>pi</th>
      <th>class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>44</td>
      <td>48</td>
      <td>325</td>
      <td>33</td>
      <td>1</td>
      <td>0</td>
      <td>12</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.111111</td>
      <td>0.094985</td>
      <td>f</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>66</td>
      <td>321</td>
      <td>150</td>
      <td>1</td>
      <td>0</td>
      <td>213</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>14.39</td>
      <td>1.97</td>
      <td>0.000</td>
      <td>1.5</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.206826</td>
      <td>230.412857</td>
      <td>f</td>
    </tr>
    <tr>
      <th>2</th>
      <td>33</td>
      <td>970</td>
      <td>308</td>
      <td>101</td>
      <td>1</td>
      <td>1</td>
      <td>436</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>10.10</td>
      <td>0.30</td>
      <td>0.000</td>
      <td>2.5</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.572174</td>
      <td>43.569939</td>
      <td>f</td>
    </tr>
    <tr>
      <th>3</th>
      <td>70</td>
      <td>86</td>
      <td>360</td>
      <td>14</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.78</td>
      <td>0.06</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>1.000000</td>
      <td>5.859799</td>
      <td>f</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3</td>
      <td>21</td>
      <td>285</td>
      <td>73</td>
      <td>1</td>
      <td>0</td>
      <td>93</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>14.29</td>
      <td>0.00</td>
      <td>0.667</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.300494</td>
      <td>0.126019</td>
      <td>f</td>
    </tr>
  </tbody>
</table>
</div>



# Q8: Print the last 5 rows


```python
# write your code here ^_^
read.tail(5)
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
      <th>pos</th>
      <th>flw</th>
      <th>flg</th>
      <th>bl</th>
      <th>pic</th>
      <th>lin</th>
      <th>cl</th>
      <th>cz</th>
      <th>ni</th>
      <th>erl</th>
      <th>erc</th>
      <th>lt</th>
      <th>hc</th>
      <th>pr</th>
      <th>fo</th>
      <th>cs</th>
      <th>pi</th>
      <th>class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>65321</th>
      <td>13</td>
      <td>145</td>
      <td>642</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>7</td>
      <td>0.461538</td>
      <td>0.000</td>
      <td>14.270000</td>
      <td>0.58</td>
      <td>0.000</td>
      <td>0.077</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.192308</td>
      <td>1745.291260</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65322</th>
      <td>652</td>
      <td>3000</td>
      <td>1300</td>
      <td>146</td>
      <td>1</td>
      <td>1</td>
      <td>384</td>
      <td>0.000000</td>
      <td>0.389</td>
      <td>8.520000</td>
      <td>0.13</td>
      <td>0.000</td>
      <td>1.611</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.169917</td>
      <td>54.629120</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65323</th>
      <td>1500</td>
      <td>3700</td>
      <td>3200</td>
      <td>147</td>
      <td>1</td>
      <td>1</td>
      <td>129</td>
      <td>0.000000</td>
      <td>0.111</td>
      <td>9.390000</td>
      <td>0.31</td>
      <td>0.722</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.058908</td>
      <td>129.802048</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65324</th>
      <td>329</td>
      <td>1500</td>
      <td>1800</td>
      <td>218</td>
      <td>1</td>
      <td>1</td>
      <td>290</td>
      <td>0.055556</td>
      <td>0.000</td>
      <td>6.350000</td>
      <td>0.26</td>
      <td>0.222</td>
      <td>0.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.103174</td>
      <td>53.402840</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65325</th>
      <td>206</td>
      <td>659</td>
      <td>608</td>
      <td>27</td>
      <td>1</td>
      <td>0</td>
      <td>77</td>
      <td>0.000000</td>
      <td>0.333</td>
      <td>25.549999</td>
      <td>0.53</td>
      <td>0.222</td>
      <td>0.222</td>
      <td>0.0</td>
      <td>0.167</td>
      <td>0.017505</td>
      <td>604.981445</td>
      <td>r</td>
    </tr>
  </tbody>
</table>
</div>



# Q9: Print the total number of null values


```python
# write your code here ^_^
read.isna().sum().sum()
```




    0



# Q10: Print the rows that has duplicate values


```python
# write your code here ^_^
duplicate = read[read.duplicated()]

duplicate
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
      <th>pos</th>
      <th>flw</th>
      <th>flg</th>
      <th>bl</th>
      <th>pic</th>
      <th>lin</th>
      <th>cl</th>
      <th>cz</th>
      <th>ni</th>
      <th>erl</th>
      <th>erc</th>
      <th>lt</th>
      <th>hc</th>
      <th>pr</th>
      <th>fo</th>
      <th>cs</th>
      <th>pi</th>
      <th>class</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>4118</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>-1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>4165</th>
      <td>0</td>
      <td>30</td>
      <td>149</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>5812</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>-1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>6500</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>-1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>8134</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>-1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>f</td>
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
      <th>32745</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>-1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>32747</th>
      <td>0</td>
      <td>34</td>
      <td>7500</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>32748</th>
      <td>0</td>
      <td>77</td>
      <td>7400</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>32749</th>
      <td>0</td>
      <td>70</td>
      <td>7300</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
    <tr>
      <th>32764</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>-1</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>f</td>
    </tr>
  </tbody>
</table>
<p>1082 rows × 18 columns</p>
</div>



# Q11: Remove all duplicate values 


```python
# write your code here ^_^
read=read.drop_duplicates()
```

# Q12: Print the number of rows and columns contained in the dataset after removing the duplicate values


```python
# write your code here ^_^
rows = len(read.axes[0])

cols = len(read.axes[1])
print(rows,cols)
```

    64244 18


# Q13: Rename all dataset's columns

|  Column name  |  New column name  |  Description  |
| ----- | -------- | ------- |
| pos    | Num_posts        | Number of total posts that the user has ever posted   |
| flg    | Num_following    | Number of following                                   |
| flr    | Num_followers    | Number of followers                                   |
| bl     | Biography_length | Length (number of characters) of the user's biography |
| pic    | Picture_availability | Value 0 if the user has no profile picture, or 1 if has |
| lin    | Link_availability| Value 0 if the user has no external URL, or 1 if has |
| cl     | Average_caption_length | The average number of character of captions in media |
| cz     | Caption_zero     | Percentage (0.0 to 1.0) of captions that has almost zero (<=3) length |
| ni     | Non_image_percentage | Percentage (0.0 to 1.0) of non-image media. There are three types of media on an Instagram post, i.e. image, video, carousel
| erl    | Engagement_rate_like | Engagement rate (ER) is commonly defined as (num likes) divide by (num media) divide by (num followers)
| erc    | Engagement_rate_comment | Similar to ER like, but it is for comments |
| lt     | Location_tag_percentage | Percentage (0.0 to 1.0) of posts tagged with location |
| hc     | Average hashtag count   | Average number of hashtags used in a post |
| pr     | Promotional keywords | Average use of promotional keywords in hashtag, i.e. regrann, contest, repost, giveaway, mention, share, give away, quiz |
| fo     | Followers keywords | Average use of followers hunter keywords in hashtag, i.e. follow, like, folback, follback, f4f|
| cs     | Cosine similarity  | Average cosine similarity of between all pair of two posts a user has |
| pi     | Post interval      | Average interval between posts (in hours) |
| class  | real_fake          | r (real/authentic user), f (fake user/bought followers) |


```python
# write your code here ^_^
read=read.rename(columns={"pos": "Num_post",
                     "flg": "Num_following",
                    "flr": "Num_followers",
                     "bl": "Biography_length",
                     "pic": "Picture_availability",
                     "lin": "Link_availability",
                     "cl": "Average_caption_length",
                     "cz": "Caption_zero",
                      
                     "ni": "Non_image_percentage",
                     "erl": "Engagement_rate_like",
                          
                     "erc": "Engagement_rate_comment",
                     "lt": "Location_tag_percentage",
                    
                      "hc": "Average_hashtag_count ",
                     "pr": "Promotional",
                          
                      "fo": "Followers",
                     "cs": "Cosine",
                          
                     "pi": "Post_interval ",
                     "class": "real_fake"
                    })
read
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
      <th>Num_post</th>
      <th>flw</th>
      <th>Num_following</th>
      <th>Biography_length</th>
      <th>Picture_availability</th>
      <th>Link_availability</th>
      <th>Average_caption_length</th>
      <th>Caption_zero</th>
      <th>Non_image_percentage</th>
      <th>Engagement_rate_like</th>
      <th>Engagement_rate_comment</th>
      <th>Location_tag_percentage</th>
      <th>Average_hashtag_count</th>
      <th>Promotional</th>
      <th>Followers</th>
      <th>Cosine</th>
      <th>Post_interval</th>
      <th>real_fake</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>44</td>
      <td>48</td>
      <td>325</td>
      <td>33</td>
      <td>1</td>
      <td>0</td>
      <td>12</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.111111</td>
      <td>0.094985</td>
      <td>f</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>66</td>
      <td>321</td>
      <td>150</td>
      <td>1</td>
      <td>0</td>
      <td>213</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>14.390000</td>
      <td>1.97</td>
      <td>0.000</td>
      <td>1.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.206826</td>
      <td>230.412857</td>
      <td>f</td>
    </tr>
    <tr>
      <th>2</th>
      <td>33</td>
      <td>970</td>
      <td>308</td>
      <td>101</td>
      <td>1</td>
      <td>1</td>
      <td>436</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>10.100000</td>
      <td>0.30</td>
      <td>0.000</td>
      <td>2.500</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.572174</td>
      <td>43.569939</td>
      <td>f</td>
    </tr>
    <tr>
      <th>3</th>
      <td>70</td>
      <td>86</td>
      <td>360</td>
      <td>14</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1.000000</td>
      <td>0.000</td>
      <td>0.780000</td>
      <td>0.06</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>1.000000</td>
      <td>5.859799</td>
      <td>f</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3</td>
      <td>21</td>
      <td>285</td>
      <td>73</td>
      <td>1</td>
      <td>0</td>
      <td>93</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>14.290000</td>
      <td>0.00</td>
      <td>0.667</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.300494</td>
      <td>0.126019</td>
      <td>f</td>
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
      <th>65321</th>
      <td>13</td>
      <td>145</td>
      <td>642</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>7</td>
      <td>0.461538</td>
      <td>0.000</td>
      <td>14.270000</td>
      <td>0.58</td>
      <td>0.000</td>
      <td>0.077</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.192308</td>
      <td>1745.291260</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65322</th>
      <td>652</td>
      <td>3000</td>
      <td>1300</td>
      <td>146</td>
      <td>1</td>
      <td>1</td>
      <td>384</td>
      <td>0.000000</td>
      <td>0.389</td>
      <td>8.520000</td>
      <td>0.13</td>
      <td>0.000</td>
      <td>1.611</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.169917</td>
      <td>54.629120</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65323</th>
      <td>1500</td>
      <td>3700</td>
      <td>3200</td>
      <td>147</td>
      <td>1</td>
      <td>1</td>
      <td>129</td>
      <td>0.000000</td>
      <td>0.111</td>
      <td>9.390000</td>
      <td>0.31</td>
      <td>0.722</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.058908</td>
      <td>129.802048</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65324</th>
      <td>329</td>
      <td>1500</td>
      <td>1800</td>
      <td>218</td>
      <td>1</td>
      <td>1</td>
      <td>290</td>
      <td>0.055556</td>
      <td>0.000</td>
      <td>6.350000</td>
      <td>0.26</td>
      <td>0.222</td>
      <td>0.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.103174</td>
      <td>53.402840</td>
      <td>r</td>
    </tr>
    <tr>
      <th>65325</th>
      <td>206</td>
      <td>659</td>
      <td>608</td>
      <td>27</td>
      <td>1</td>
      <td>0</td>
      <td>77</td>
      <td>0.000000</td>
      <td>0.333</td>
      <td>25.549999</td>
      <td>0.53</td>
      <td>0.222</td>
      <td>0.222</td>
      <td>0.0</td>
      <td>0.167</td>
      <td>0.017505</td>
      <td>604.981445</td>
      <td>r</td>
    </tr>
  </tbody>
</table>
<p>64244 rows × 18 columns</p>
</div>



# Q14: Change the class's values to real and fake


```python
# write your code here ^_^
#read.dtypes
#read = read.astype({"real_fake": str})
#read.dtypes
read.loc[read["real_fake"] == "f", "real_fake"] = "Fake"
read.loc[read["real_fake"] == "r", "real_fake"] = "Real"
read
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
      <th>Num_post</th>
      <th>flw</th>
      <th>Num_following</th>
      <th>Biography_length</th>
      <th>Picture_availability</th>
      <th>Link_availability</th>
      <th>Average_caption_length</th>
      <th>Caption_zero</th>
      <th>Non_image_percentage</th>
      <th>Engagement_rate_like</th>
      <th>Engagement_rate_comment</th>
      <th>Location_tag_percentage</th>
      <th>Average_hashtag_count</th>
      <th>Promotional</th>
      <th>Followers</th>
      <th>Cosine</th>
      <th>Post_interval</th>
      <th>real_fake</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>44</td>
      <td>48</td>
      <td>325</td>
      <td>33</td>
      <td>1</td>
      <td>0</td>
      <td>12</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.111111</td>
      <td>0.094985</td>
      <td>Fake</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10</td>
      <td>66</td>
      <td>321</td>
      <td>150</td>
      <td>1</td>
      <td>0</td>
      <td>213</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>14.390000</td>
      <td>1.97</td>
      <td>0.000</td>
      <td>1.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.206826</td>
      <td>230.412857</td>
      <td>Fake</td>
    </tr>
    <tr>
      <th>2</th>
      <td>33</td>
      <td>970</td>
      <td>308</td>
      <td>101</td>
      <td>1</td>
      <td>1</td>
      <td>436</td>
      <td>0.000000</td>
      <td>1.000</td>
      <td>10.100000</td>
      <td>0.30</td>
      <td>0.000</td>
      <td>2.500</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.572174</td>
      <td>43.569939</td>
      <td>Fake</td>
    </tr>
    <tr>
      <th>3</th>
      <td>70</td>
      <td>86</td>
      <td>360</td>
      <td>14</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1.000000</td>
      <td>0.000</td>
      <td>0.780000</td>
      <td>0.06</td>
      <td>0.000</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>1.000000</td>
      <td>5.859799</td>
      <td>Fake</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3</td>
      <td>21</td>
      <td>285</td>
      <td>73</td>
      <td>1</td>
      <td>0</td>
      <td>93</td>
      <td>0.000000</td>
      <td>0.000</td>
      <td>14.290000</td>
      <td>0.00</td>
      <td>0.667</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.300494</td>
      <td>0.126019</td>
      <td>Fake</td>
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
      <th>65321</th>
      <td>13</td>
      <td>145</td>
      <td>642</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>7</td>
      <td>0.461538</td>
      <td>0.000</td>
      <td>14.270000</td>
      <td>0.58</td>
      <td>0.000</td>
      <td>0.077</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.192308</td>
      <td>1745.291260</td>
      <td>Real</td>
    </tr>
    <tr>
      <th>65322</th>
      <td>652</td>
      <td>3000</td>
      <td>1300</td>
      <td>146</td>
      <td>1</td>
      <td>1</td>
      <td>384</td>
      <td>0.000000</td>
      <td>0.389</td>
      <td>8.520000</td>
      <td>0.13</td>
      <td>0.000</td>
      <td>1.611</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.169917</td>
      <td>54.629120</td>
      <td>Real</td>
    </tr>
    <tr>
      <th>65323</th>
      <td>1500</td>
      <td>3700</td>
      <td>3200</td>
      <td>147</td>
      <td>1</td>
      <td>1</td>
      <td>129</td>
      <td>0.000000</td>
      <td>0.111</td>
      <td>9.390000</td>
      <td>0.31</td>
      <td>0.722</td>
      <td>0.000</td>
      <td>0.0</td>
      <td>0.056</td>
      <td>0.058908</td>
      <td>129.802048</td>
      <td>Real</td>
    </tr>
    <tr>
      <th>65324</th>
      <td>329</td>
      <td>1500</td>
      <td>1800</td>
      <td>218</td>
      <td>1</td>
      <td>1</td>
      <td>290</td>
      <td>0.055556</td>
      <td>0.000</td>
      <td>6.350000</td>
      <td>0.26</td>
      <td>0.222</td>
      <td>0.500</td>
      <td>0.0</td>
      <td>0.000</td>
      <td>0.103174</td>
      <td>53.402840</td>
      <td>Real</td>
    </tr>
    <tr>
      <th>65325</th>
      <td>206</td>
      <td>659</td>
      <td>608</td>
      <td>27</td>
      <td>1</td>
      <td>0</td>
      <td>77</td>
      <td>0.000000</td>
      <td>0.333</td>
      <td>25.549999</td>
      <td>0.53</td>
      <td>0.222</td>
      <td>0.222</td>
      <td>0.0</td>
      <td>0.167</td>
      <td>0.017505</td>
      <td>604.981445</td>
      <td>Real</td>
    </tr>
  </tbody>
</table>
<p>64244 rows × 18 columns</p>
</div>



# Q15: Print the total number of each fake accounts and real accounts 


```python
# write your code here ^_^
group = read[['Num_post', 'real_fake']].groupby('real_fake').count()
group
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
      <th>Num_post</th>
    </tr>
    <tr>
      <th>real_fake</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Fake</th>
      <td>31784</td>
    </tr>
    <tr>
      <th>Real</th>
      <td>32460</td>
    </tr>
  </tbody>
</table>
</div>



# Q16: Print the count, mean, std, min, 25%, 50%, 75% and the max for each column


```python
# write your code here ^_^
read.describe()

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
      <th>Num_post</th>
      <th>flw</th>
      <th>Num_following</th>
      <th>Biography_length</th>
      <th>Picture_availability</th>
      <th>Link_availability</th>
      <th>Average_caption_length</th>
      <th>Caption_zero</th>
      <th>Non_image_percentage</th>
      <th>Engagement_rate_like</th>
      <th>Engagement_rate_comment</th>
      <th>Location_tag_percentage</th>
      <th>Average_hashtag_count</th>
      <th>Promotional</th>
      <th>Followers</th>
      <th>Cosine</th>
      <th>Post_interval</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>64244.000000</td>
      <td>6.424400e+04</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
      <td>64244.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>179.545047</td>
      <td>1.202470e+03</td>
      <td>2297.041732</td>
      <td>58.464464</td>
      <td>0.959140</td>
      <td>0.286673</td>
      <td>138.822131</td>
      <td>0.254160</td>
      <td>0.196484</td>
      <td>19.469109</td>
      <td>1.158611</td>
      <td>0.212395</td>
      <td>0.516348</td>
      <td>0.033296</td>
      <td>0.053727</td>
      <td>0.289861</td>
      <td>504.836848</td>
    </tr>
    <tr>
      <th>std</th>
      <td>729.171634</td>
      <td>2.188954e+04</td>
      <td>2572.939318</td>
      <td>64.228211</td>
      <td>0.197967</td>
      <td>0.452211</td>
      <td>216.786922</td>
      <td>0.339104</td>
      <td>0.253804</td>
      <td>122.036954</td>
      <td>5.857458</td>
      <td>0.301645</td>
      <td>1.164729</td>
      <td>0.222799</td>
      <td>0.523365</td>
      <td>0.341986</td>
      <td>950.611615</td>
    </tr>
    <tr>
      <th>min</th>
      <td>0.000000</td>
      <td>0.000000e+00</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>-1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>6.000000</td>
      <td>1.310000e+02</td>
      <td>403.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>9.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>3.000000</td>
      <td>0.090000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.032954</td>
      <td>29.064719</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>31.000000</td>
      <td>3.480000e+02</td>
      <td>997.000000</td>
      <td>34.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>48.000000</td>
      <td>0.055556</td>
      <td>0.083000</td>
      <td>9.690000</td>
      <td>0.460000</td>
      <td>0.000000</td>
      <td>0.111000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.133135</td>
      <td>190.369553</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>127.000000</td>
      <td>8.300000e+02</td>
      <td>3500.000000</td>
      <td>111.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>174.000000</td>
      <td>0.444444</td>
      <td>0.333000</td>
      <td>18.860001</td>
      <td>1.060000</td>
      <td>0.357000</td>
      <td>0.611000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.431373</td>
      <td>591.858658</td>
    </tr>
    <tr>
      <th>max</th>
      <td>76200.000000</td>
      <td>3.900000e+06</td>
      <td>8800.000000</td>
      <td>555.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>3644.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>26650.000000</td>
      <td>1009.090027</td>
      <td>1.000000</td>
      <td>30.000000</td>
      <td>20.000000</td>
      <td>58.000000</td>
      <td>1.000000</td>
      <td>26786.134766</td>
    </tr>
  </tbody>
</table>
</div>




```python

```
