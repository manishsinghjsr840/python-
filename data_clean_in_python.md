```python
import pandas as pd 
```


```python
df=pd.read_excel(r"C:\Users\Win11\Desktop\Customer Call List.xlsx")
```


```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
    <tr>
      <th>20</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
df=df.drop_duplicates()
```

# For deleteing any colunm we use df.drop_duplicates()


```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.drop(columns="Not_Useful_Column")

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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
    </tr>
  </tbody>
</table>
</div>




```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123/643/9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876|678|3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>NaN</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876|678|3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>N/a</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>NaN</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876|678|3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123/643/9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876|678|3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
# df["Last_Name"]=df["Last_Name"].str.strip("...")
# df["Last_Name"]=df["Last_Name"].str.strip("/")
# df["Last_Name"]=df["Last_Name"].str.strip("_")
```


```python
df["Last_Name"]
```




    0         Baggins
    1           Nadir
    2          /White
    3         Schrute
    4            Snow
    5         Swanson
    6          Winger
    7          Holmes
    8             NaN
    9          Parker
    10         Gamgee
    11      ...Potter
    12         Draper
    13          Knope
    14    Flenderson_
    15        Weasley
    16          Scott
    17           Kent
    18         Braton
    19      Skywalker
    Name: Last_Name, dtype: object




```python
df.loc[:, "Phone_Number"] = df["Phone_Number"].astype(str)
```


```python
df.loc[:,"Phone_Number"]=df["Phone_Number"].str.replace('N/a','')
df.loc[:,"Phone_Number"]=df["Phone_Number"].str.replace('nan','')
```


```python
import re

df.loc[:,"Phone_Number"] = df["Phone_Number"].str.replace('[^a-zA-Z0-9]', '', flags=re.IGNORECASE, regex=True)


```


```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>1235455421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>1236439775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>7066950392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>1235432345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>8766783469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>3047622467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td></td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>8766783469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td></td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>1235455421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td></td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>7066950392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>1235432345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>8766783469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>3047622467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>1235455421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>1236439775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>7066950392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td></td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>8766783469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.loc[:,"Phone_Number"]=df["Phone_Number"].apply(lambda x:x[0:3]+'-'+x[3:6]+'-'+ x[6:10])
```


```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>No</td>
      <td>Yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Walter</td>
      <td>/White</td>
      <td>706-695-0392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Yes</td>
      <td>Y</td>
      <td>True</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Yes</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>--</td>
      <td>1209 South Street</td>
      <td>No</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>--</td>
      <td>123 Middle Earth</td>
      <td>Yes</td>
      <td>NaN</td>
      <td>False</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>--</td>
      <td>612 Shire Lane, Shire</td>
      <td>Yes</td>
      <td>No</td>
      <td>True</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>706-695-0392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Yes</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>No</td>
      <td>N</td>
      <td>False</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Yes</td>
      <td>No</td>
      <td>False</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>706-695-0392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>True</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>--</td>
      <td>N/a</td>
      <td>N/a</td>
      <td>Yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Yes</td>
      <td>N</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.loc["Address"] = df["Address"].astype(str)

df.loc["Address"] = df["Address"].astype(str)


```


```python
df.loc["Address"] = df["Address"].str.replace('nan','')
```


```python
split_data = df["Address"].str.split(',', n=2, expand=True)

df["Street"] = split_data[0]
df["City"] = split_data[1]
df["State"] = split_data[2]




```


```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street</th>
      <th>City</th>
      <th>State</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001.0</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002.0</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>N</td>
      <td>Yes</td>
      <td>0.0</td>
      <td>93 West Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003.0</td>
      <td>Walter</td>
      <td>/White</td>
      <td>706-695-0392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004.0</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Y</td>
      <td>Y</td>
      <td>1.0</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005.0</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006.0</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Y</td>
      <td>Yes</td>
      <td>1.0</td>
      <td>768 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007.0</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>--</td>
      <td>1209 South Street</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008.0</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009.0</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>--</td>
      <td>123 Middle Earth</td>
      <td>Y</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010.0</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011.0</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>--</td>
      <td>612 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012.0</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>706-695-0392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013.0</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Y</td>
      <td>N</td>
      <td>0.0</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014.0</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015.0</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016.0</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>N</td>
      <td>N</td>
      <td>0.0</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017.0</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018.0</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>706-695-0392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019.0</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>--</td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td>1.0</td>
      <td>N/a</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020.0</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Y</td>
      <td>N</td>
      <td>1.0</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
    <tr>
      <th>Address</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>nan</td>
      <td>nan</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Paying Customer</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>nan</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df["Paying Customer"].str.strip()
df.loc["Paying Customer"] = df["Paying Customer"].astype(str)


```


```python
df["Paying Customer"]=df["Paying Customer"].str.replace('Yes',"Y")
df["Paying Customer"]=df["Paying Customer"].str.replace("No","N")
```


```python
df
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street</th>
      <th>City</th>
      <th>State</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001.0</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003.0</td>
      <td>Walter</td>
      <td>/White</td>
      <td>706-695-0392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005.0</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007.0</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>--</td>
      <td>1209 South Street</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008.0</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009.0</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>--</td>
      <td>123 Middle Earth</td>
      <td>Y</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010.0</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011.0</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>--</td>
      <td>612 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012.0</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>706-695-0392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013.0</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Y</td>
      <td>N</td>
      <td>0.0</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014.0</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015.0</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016.0</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>N</td>
      <td>N</td>
      <td>0.0</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017.0</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018.0</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>706-695-0392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020.0</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Y</td>
      <td>N</td>
      <td>1.0</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
    <tr>
      <th>Address</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td></td>
      <td></td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Paying Customer</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>nan</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df["Paying Customer"]=df["Paying Customer"].str.replace('N/a','')
df["Paying Customer"]=df["Paying Customer"].str.replace('NaN','')
```


```python
df.fillna("")
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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street</th>
      <th>City</th>
      <th>State</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001.0</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002.0</td>
      <td>Abed</td>
      <td>Nadir</td>
      <td>123-643-9775</td>
      <td>93 West Main Street</td>
      <td>N</td>
      <td>Yes</td>
      <td>0.0</td>
      <td>93 West Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003.0</td>
      <td>Walter</td>
      <td>/White</td>
      <td>706-695-0392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td></td>
      <td>1.0</td>
      <td>298 Drugs Driveway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004.0</td>
      <td>Dwight</td>
      <td>Schrute</td>
      <td>123-543-2345</td>
      <td>980 Paper Avenue, Pennsylvania, 18503</td>
      <td>Y</td>
      <td>Y</td>
      <td>1.0</td>
      <td>980 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>18503</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005.0</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Dragons Road</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006.0</td>
      <td>Ron</td>
      <td>Swanson</td>
      <td>304-762-2467</td>
      <td>768 City Parkway</td>
      <td>Y</td>
      <td>Yes</td>
      <td>1.0</td>
      <td>768 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007.0</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>--</td>
      <td>1209 South Street</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>1209 South Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008.0</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>98 Clue Drive</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009.0</td>
      <td>Gandalf</td>
      <td></td>
      <td>--</td>
      <td>123 Middle Earth</td>
      <td>Y</td>
      <td></td>
      <td>0.0</td>
      <td>123 Middle Earth</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010.0</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td></td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011.0</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>--</td>
      <td>612 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td></td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012.0</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>706-695-0392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td></td>
      <td>1.0</td>
      <td>2394 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013.0</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Y</td>
      <td>N</td>
      <td>0.0</td>
      <td>2039 Main Street</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014.0</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>343 City Parkway</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015.0</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>214 HR Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016.0</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>N</td>
      <td>N</td>
      <td>0.0</td>
      <td>2395 Hogwarts Avenue</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017.0</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td></td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018.0</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>706-695-0392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td></td>
      <td>1.0</td>
      <td>3498 Super Lane</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>18</th>
      <td>1019.0</td>
      <td>Creed</td>
      <td>Braton</td>
      <td>--</td>
      <td>N/a</td>
      <td></td>
      <td>Yes</td>
      <td>1.0</td>
      <td>N/a</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020.0</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Y</td>
      <td>N</td>
      <td>1.0</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td></td>
    </tr>
    <tr>
      <th>Address</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>Paying Customer</th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td>nan</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>




```python
for x in df.index:
    if df.loc[x, "Do_Not_Contact"] == 'Yes':
        df.drop(x, inplace=True)

```


```python
df

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
      <th>CustomerID</th>
      <th>First_Name</th>
      <th>Last_Name</th>
      <th>Phone_Number</th>
      <th>Address</th>
      <th>Paying Customer</th>
      <th>Do_Not_Contact</th>
      <th>Not_Useful_Column</th>
      <th>Street</th>
      <th>City</th>
      <th>State</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001.0</td>
      <td>Frodo</td>
      <td>Baggins</td>
      <td>123-545-5421</td>
      <td>123 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003.0</td>
      <td>Walter</td>
      <td>/White</td>
      <td>706-695-0392</td>
      <td>298 Drugs Driveway</td>
      <td>N</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>298 Drugs Driveway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005.0</td>
      <td>Jon</td>
      <td>Snow</td>
      <td>876-678-3469</td>
      <td>123 Dragons Road</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>123 Dragons Road</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>6</th>
      <td>1007.0</td>
      <td>Jeff</td>
      <td>Winger</td>
      <td>--</td>
      <td>1209 South Street</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>1209 South Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1008.0</td>
      <td>Sherlock</td>
      <td>Holmes</td>
      <td>876-678-3469</td>
      <td>98 Clue Drive</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>98 Clue Drive</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>8</th>
      <td>1009.0</td>
      <td>Gandalf</td>
      <td>NaN</td>
      <td>--</td>
      <td>123 Middle Earth</td>
      <td>Y</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>123 Middle Earth</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1010.0</td>
      <td>Peter</td>
      <td>Parker</td>
      <td>123-545-5421</td>
      <td>25th Main Street, New York</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>25th Main Street</td>
      <td>New York</td>
      <td>None</td>
    </tr>
    <tr>
      <th>10</th>
      <td>1011.0</td>
      <td>Samwise</td>
      <td>Gamgee</td>
      <td>--</td>
      <td>612 Shire Lane, Shire</td>
      <td>Y</td>
      <td>No</td>
      <td>1.0</td>
      <td>612 Shire Lane</td>
      <td>Shire</td>
      <td>None</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1012.0</td>
      <td>Harry</td>
      <td>...Potter</td>
      <td>706-695-0392</td>
      <td>2394 Hogwarts Avenue</td>
      <td>Y</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>2394 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>12</th>
      <td>1013.0</td>
      <td>Don</td>
      <td>Draper</td>
      <td>123-543-2345</td>
      <td>2039 Main Street</td>
      <td>Y</td>
      <td>N</td>
      <td>0.0</td>
      <td>2039 Main Street</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>13</th>
      <td>1014.0</td>
      <td>Leslie</td>
      <td>Knope</td>
      <td>876-678-3469</td>
      <td>343 City Parkway</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>343 City Parkway</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1015.0</td>
      <td>Toby</td>
      <td>Flenderson_</td>
      <td>304-762-2467</td>
      <td>214 HR Avenue</td>
      <td>N</td>
      <td>No</td>
      <td>0.0</td>
      <td>214 HR Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>15</th>
      <td>1016.0</td>
      <td>Ron</td>
      <td>Weasley</td>
      <td>123-545-5421</td>
      <td>2395 Hogwarts Avenue</td>
      <td>N</td>
      <td>N</td>
      <td>0.0</td>
      <td>2395 Hogwarts Avenue</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>16</th>
      <td>1017.0</td>
      <td>Michael</td>
      <td>Scott</td>
      <td>123-643-9775</td>
      <td>121 Paper Avenue, Pennsylvania</td>
      <td>Y</td>
      <td>No</td>
      <td>0.0</td>
      <td>121 Paper Avenue</td>
      <td>Pennsylvania</td>
      <td>None</td>
    </tr>
    <tr>
      <th>17</th>
      <td>1018.0</td>
      <td>Clark</td>
      <td>Kent</td>
      <td>706-695-0392</td>
      <td>3498 Super Lane</td>
      <td>Y</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>3498 Super Lane</td>
      <td>None</td>
      <td>None</td>
    </tr>
    <tr>
      <th>19</th>
      <td>1020.0</td>
      <td>Anakin</td>
      <td>Skywalker</td>
      <td>876-678-3469</td>
      <td>910 Tatooine Road, Tatooine</td>
      <td>Y</td>
      <td>N</td>
      <td>1.0</td>
      <td>910 Tatooine Road</td>
      <td>Tatooine</td>
      <td>None</td>
    </tr>
    <tr>
      <th>Address</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td></td>
      <td></td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Paying Customer</th>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>nan</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>


