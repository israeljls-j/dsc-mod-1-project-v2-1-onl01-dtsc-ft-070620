
<h1>Table of Contents<span class="tocSkip"></span></h1>
<div class="toc"><ul class="toc-item"><li><span><a href="#-Final-Project-Submission" data-toc-modified-id="-Final-Project-Submission-1"><span class="toc-item-num">1&nbsp;&nbsp;</span> Final Project Submission</a></span></li><li><span><a href="#-Client-Interest-Statement-:" data-toc-modified-id="-Client-Interest-Statement-:-2"><span class="toc-item-num">2&nbsp;&nbsp;</span> Client Interest Statement :</a></span><ul class="toc-item"><li><ul class="toc-item"><li><span><a href="#Client-is-interested-in-going-into-the-movie-making-business-space." data-toc-modified-id="Client-is-interested-in-going-into-the-movie-making-business-space.-2.0.1"><span class="toc-item-num">2.0.1&nbsp;&nbsp;</span>Client is interested in going into the movie-making business space.</a></span></li></ul></li></ul></li><li><span><a href="#-Mission:" data-toc-modified-id="-Mission:-3"><span class="toc-item-num">3&nbsp;&nbsp;</span> Mission:</a></span><ul class="toc-item"><li><ul class="toc-item"><li><span><a href="#Analyze-the-movie-market-to-determine-what-makes-a-great-movie-using-market-data,-web-data-and-financial-information." data-toc-modified-id="Analyze-the-movie-market-to-determine-what-makes-a-great-movie-using-market-data,-web-data-and-financial-information.-3.0.1"><span class="toc-item-num">3.0.1&nbsp;&nbsp;</span>Analyze the movie market to determine what makes a great movie using market data, web data and financial information.</a></span></li><li><span><a href="#1.-Importing-the-required-libraries-for-EDA" data-toc-modified-id="1.-Importing-the-required-libraries-for-EDA-3.0.2"><span class="toc-item-num">3.0.2&nbsp;&nbsp;</span>1. Importing the required libraries for EDA</a></span></li></ul></li></ul></li><li><span><a href="#-Transform-Data" data-toc-modified-id="-Transform-Data-4"><span class="toc-item-num">4&nbsp;&nbsp;</span> Transform Data</a></span><ul class="toc-item"><li><ul class="toc-item"><li><span><a href="#Import-other-files-to-dictionaries" data-toc-modified-id="Import-other-files-to-dictionaries-4.0.1"><span class="toc-item-num">4.0.1&nbsp;&nbsp;</span>Import other files to dictionaries</a></span></li></ul></li></ul></li><li><span><a href="#-Cleaning-the-Data" data-toc-modified-id="-Cleaning-the-Data-5"><span class="toc-item-num">5&nbsp;&nbsp;</span> Cleaning the Data</a></span><ul class="toc-item"><li><span><a href="#All-Files-Review" data-toc-modified-id="All-Files-Review-5.1"><span class="toc-item-num">5.1&nbsp;&nbsp;</span>All Files Review</a></span><ul class="toc-item"><li><span><a href="#1.-check-for-na's" data-toc-modified-id="1.-check-for-na's-5.1.1"><span class="toc-item-num">5.1.1&nbsp;&nbsp;</span>1. check for na's</a></span></li><li><span><a href="#2.-review-shape-of-dfs" data-toc-modified-id="2.-review-shape-of-dfs-5.1.2"><span class="toc-item-num">5.1.2&nbsp;&nbsp;</span>2. review shape of dfs</a></span></li><li><span><a href="#3.-check-for-duplicates" data-toc-modified-id="3.-check-for-duplicates-5.1.3"><span class="toc-item-num">5.1.3&nbsp;&nbsp;</span>3. check for duplicates</a></span></li><li><span><a href="#4.-check-column-consistency" data-toc-modified-id="4.-check-column-consistency-5.1.4"><span class="toc-item-num">5.1.4&nbsp;&nbsp;</span>4. check column consistency</a></span></li><li><span><a href="#NA's-for-all-files" data-toc-modified-id="NA's-for-all-files-5.1.5"><span class="toc-item-num">5.1.5&nbsp;&nbsp;</span>NA's for all files</a></span></li><li><span><a href="#check-shape-of-files" data-toc-modified-id="check-shape-of-files-5.1.6"><span class="toc-item-num">5.1.6&nbsp;&nbsp;</span>check shape of files</a></span></li><li><span><a href="#check-for-duplicates" data-toc-modified-id="check-for-duplicates-5.1.7"><span class="toc-item-num">5.1.7&nbsp;&nbsp;</span>check for duplicates</a></span></li><li><span><a href="#3.-check-for-column-name-consistency" data-toc-modified-id="3.-check-for-column-name-consistency-5.1.8"><span class="toc-item-num">5.1.8&nbsp;&nbsp;</span>3. check for column name consistency</a></span></li></ul></li><li><span><a href="#movies-file" data-toc-modified-id="movies-file-5.2"><span class="toc-item-num">5.2&nbsp;&nbsp;</span>movies file</a></span><ul class="toc-item"><li><span><a href="#1.--check-genre_ids
----2.--primary-key-
----3.--change-datetime" data-toc-modified-id="1.--check-genre_ids
----2.--primary-key-
----3.--change-datetime-5.2.1"><span class="toc-item-num">5.2.1&nbsp;&nbsp;</span>1.  check genre_ids
    2.  primary key 
    3.  change datetime</a></span></li><li><span><a href="#2.-Primary-Key-is-ID" data-toc-modified-id="2.-Primary-Key-is-ID-5.2.2"><span class="toc-item-num">5.2.2&nbsp;&nbsp;</span>2. Primary Key is ID</a></span></li><li><span><a href="#3.-datetime-changed" data-toc-modified-id="3.-datetime-changed-5.2.3"><span class="toc-item-num">5.2.3&nbsp;&nbsp;</span>3. datetime changed</a></span></li></ul></li><li><span><a href="#title_crew-file" data-toc-modified-id="title_crew-file-5.3"><span class="toc-item-num">5.3&nbsp;&nbsp;</span>title_crew file</a></span></li><li><span><a href="#tn_budgets-file" data-toc-modified-id="tn_budgets-file-5.4"><span class="toc-item-num">5.4&nbsp;&nbsp;</span>tn_budgets file</a></span><ul class="toc-item"><li><span><a href="#budgets-file-changes:
" data-toc-modified-id="budgets-file-changes:
-5.4.1"><span class="toc-item-num">5.4.1&nbsp;&nbsp;</span>budgets file changes:
</a></span></li><li><span><a href="#2.-Primary-Key-is-ID" data-toc-modified-id="2.-Primary-Key-is-ID-5.4.2"><span class="toc-item-num">5.4.2&nbsp;&nbsp;</span>2. Primary Key is ID</a></span></li></ul></li><li><span><a href="#title_ratings-File" data-toc-modified-id="title_ratings-File-5.5"><span class="toc-item-num">5.5&nbsp;&nbsp;</span>title_ratings File</a></span><ul class="toc-item"><li><span><a href="#2.-Primary-Key-is-tconst" data-toc-modified-id="2.-Primary-Key-is-tconst-5.5.1"><span class="toc-item-num">5.5.1&nbsp;&nbsp;</span>2. Primary Key is tconst</a></span></li></ul></li><li><span><a href="#name_basics-File" data-toc-modified-id="name_basics-File-5.6"><span class="toc-item-num">5.6&nbsp;&nbsp;</span>name_basics File</a></span><ul class="toc-item"><li><span><a href="#name_basics-file-changes:" data-toc-modified-id="name_basics-file-changes:-5.6.1"><span class="toc-item-num">5.6.1&nbsp;&nbsp;</span>name_basics file changes:</a></span></li><li><span><a href="#1.-delete-birth/death-years" data-toc-modified-id="1.-delete-birth/death-years-5.6.2"><span class="toc-item-num">5.6.2&nbsp;&nbsp;</span>1. delete birth/death years</a></span></li><li><span><a href="#1.-fill-na's" data-toc-modified-id="1.-fill-na's-5.6.3"><span class="toc-item-num">5.6.3&nbsp;&nbsp;</span>1. fill na's</a></span></li><li><span><a href="#2.-Primary-Key-is-nconst" data-toc-modified-id="2.-Primary-Key-is-nconst-5.6.4"><span class="toc-item-num">5.6.4&nbsp;&nbsp;</span>2. Primary Key is nconst</a></span></li></ul></li><li><span><a href="#title_principals-file" data-toc-modified-id="title_principals-file-5.7"><span class="toc-item-num">5.7&nbsp;&nbsp;</span>title_principals file</a></span><ul class="toc-item"><li><span><a href="#title_principals-file-changes:" data-toc-modified-id="title_principals-file-changes:-5.7.1"><span class="toc-item-num">5.7.1&nbsp;&nbsp;</span>title_principals file changes:</a></span></li><li><span><a href="#2.-Primary-Key-is-tconst/nconst" data-toc-modified-id="2.-Primary-Key-is-tconst/nconst-5.7.2"><span class="toc-item-num">5.7.2&nbsp;&nbsp;</span>2. Primary Key is tconst/nconst</a></span></li></ul></li><li><span><a href="#title_akas-file" data-toc-modified-id="title_akas-file-5.8"><span class="toc-item-num">5.8&nbsp;&nbsp;</span>title_akas file</a></span></li><li><span><a href="#bom_movie_gross-file" data-toc-modified-id="bom_movie_gross-file-5.9"><span class="toc-item-num">5.9&nbsp;&nbsp;</span>bom_movie_gross file</a></span></li><li><span><a href="#title_basics" data-toc-modified-id="title_basics-5.10"><span class="toc-item-num">5.10&nbsp;&nbsp;</span>title_basics</a></span></li></ul></li><li><span><a href="#Merging-the-Data" data-toc-modified-id="Merging-the-Data-6"><span class="toc-item-num">6&nbsp;&nbsp;</span>Merging the Data</a></span><ul class="toc-item"><li><span><a href="#Explode-the-list-in-the-tn_budgets-file" data-toc-modified-id="Explode-the-list-in-the-tn_budgets-file-6.1"><span class="toc-item-num">6.1&nbsp;&nbsp;</span>Explode the list in the tn_budgets file</a></span></li><li><span><a href="#Merge-Files" data-toc-modified-id="Merge-Files-6.2"><span class="toc-item-num">6.2&nbsp;&nbsp;</span>Merge Files</a></span></li></ul></li><li><span><a href="#Analysis" data-toc-modified-id="Analysis-7"><span class="toc-item-num">7&nbsp;&nbsp;</span>Analysis</a></span></li><li><span><a href="#Previous-sequel-work" data-toc-modified-id="Previous-sequel-work-8"><span class="toc-item-num">8&nbsp;&nbsp;</span>Previous sequel work</a></span></li></ul></div>


```python

```

<h1> Final Project Submission</h1>
<h4> Student name: Joan Leonard Short</h4>             <h4> Scheduled project review date/time:</h4>       
<h4> Student pace: full time online </h4>             <h4> Blog post URL:  https://israeljls-j.github.io/</h4>




```python

```

<h1> Client Interest Statement :</h1>
<h3>Client is interested in going into the movie-making business space.</h3>

<h1> Mission:</h1> 
<h3>Analyze the movie market to determine what makes a great movie using market data, web data and financial information.</h3> 


```python

```

<H3>1. Importing the required libraries for EDA</H3>


```python
import sqlite3
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
import glob
import os
from os import listdir
from os.path import splitext, basename
from datetime import datetime
import io
import seaborn as sns


```

<h1> Transform Data</h1>


```python
# df = pd.read_csv(/Users/owner/flatiron1/project1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/'tmdb.movies.csv', index_col=None)
# pd.read_csv(io.StringIO(df.to_csv()))
```


```python
filenames = []
df_list = []
path = '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/'
filenames = [(path + filename) for filename in os.listdir(path) if filename.endswith('.csv')]
df_list = [filename.split('.csv') for  filename in filenames]
filenames
```




    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/tmdb.movies.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.crew.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/tn.movie_budgets.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.ratings.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.name.basics.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.principals.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.akas.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/bom.movie_gross.csv',
     '/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.basics.csv']




```python

for item in df_list:
    print(item)
```

    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/tmdb.movies', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.crew', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/tn.movie_budgets', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.ratings', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.name.basics', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.principals', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.akas', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/bom.movie_gross', '']
    ['/Users/owner/flatiron1/myproject1/dsc-mod-1-project-v2-1-onl01-dtsc-ft-070620/zippedData/imdb.title.basics', '']



```python

```


```python
# read in datafiles
df_list = [pd.read_csv(filename, parse_dates= True) for filename in filenames]


```


```python
#create separate dfs
movies = df_list[0]
title_crew = df_list[1]
tn_budgets = df_list[2]
title_ratings = df_list[3]
name_basics = df_list[4]
title_principals = df_list[5]
title_akas = df_list[6]
bom_movie_gross = df_list[7]
title_basics = df_list[8]

```


```python
md = { 'movies' : movies, 'title_crew' : title_crew, 'tn_budgets' : tn_budgets, 'title_ratings' : title_ratings, 'name_basics' : name_basics, 'title_principals' : title_principals,'title_akas' : title_akas, 'bom_movie_gross' : bom_movie_gross, 'title_basics' : title_basics}
md.keys()
```




    dict_keys(['movies', 'title_crew', 'tn_budgets', 'title_ratings', 'name_basics', 'title_principals', 'title_akas', 'bom_movie_gross', 'title_basics'])




```python
md['movies'].columns
```




    Index(['genre_ids', 'id', 'original_language', 'original_title', 'popularity',
           'release_date', 'title', 'vote_average', 'vote_count'],
          dtype='object')




```python
md['title_basics'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 146144 entries, 0 to 146143
    Data columns (total 6 columns):
    tconst             146144 non-null object
    primary_title      146144 non-null object
    original_title     146123 non-null object
    start_year         146144 non-null int64
    runtime_minutes    114405 non-null float64
    genres             140736 non-null object
    dtypes: float64(1), int64(1), object(4)
    memory usage: 6.7+ MB


<h3>Import other files to dictionaries</h3>


```python
genre_ids = {'Action': 28, 'Adventure': 12, 'Animation': 16, 'Comedy': 35, 'Crime': 80, 'Documentary': 99, 'Drama': 18, 'Family': 10751, 'Fantasy': 14, 'History': 36, 'Horror': 27, 'Music': 10402, 'Mystery': 9648, 'Romance': 10749, 'Science_fiction': 878, 'TV_movie': 10770, 'Thriller': 53, 'War': 10752, 'Western': 3}
genre_ids

```




    {'Action': 28,
     'Adventure': 12,
     'Animation': 16,
     'Comedy': 35,
     'Crime': 80,
     'Documentary': 99,
     'Drama': 18,
     'Family': 10751,
     'Fantasy': 14,
     'History': 36,
     'Horror': 27,
     'Music': 10402,
     'Mystery': 9648,
     'Romance': 10749,
     'Science_fiction': 878,
     'TV_movie': 10770,
     'Thriller': 53,
     'War': 10752,
     'Western': 3}



<h1> Cleaning the Data</h1>

<h2>All Files Review</h2>
<h3>1. check for na's</h3>
<h3>2. review shape of dfs</h3>
<h3>3. check for duplicates</h3>
<h3>4. check column consistency</h3>


<h3>NA's for all files</h3>


```python
for key in md:
    a = md[key].isna().sum()
    b = (a[a>0])
    c = key
    print(b, 'FILE', c)
    
```

    Series([], dtype: int64) FILE movies
    directors     5727
    writers      35883
    dtype: int64 FILE title_crew
    Series([], dtype: int64) FILE tn_budgets
    Series([], dtype: int64) FILE title_ratings
    birth_year            523912
    death_year            599865
    primary_profession     51340
    known_for_titles       30204
    dtype: int64 FILE name_basics
    job           850502
    characters    634826
    dtype: int64 FILE title_principals
    region                53293
    language             289988
    types                163256
    attributes           316778
    is_original_title        25
    dtype: int64 FILE title_akas
    studio               5
    domestic_gross      28
    foreign_gross     1350
    dtype: int64 FILE bom_movie_gross
    original_title        21
    runtime_minutes    31739
    genres              5408
    dtype: int64 FILE title_basics



```python
#will not use job or characters
sns.heatmap(md['title_principals'].isnull(), cbar=False)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1af7765828>




![png](output_24_1.png)



```python

```


```python
#will not use job, characters
sns.heatmap(md['name_basics'].isnull(), cbar=False)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1a741fcb00>




![png](output_26_1.png)



```python
#will not use birth/death years
sns.heatmap(md['name_basics'].isnull(), cbar=False)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1a34e19c50>




![png](output_27_1.png)



```python
# will not use language or attributes.  Look at types and region for fills
sns.heatmap(md['title_akas'].isnull(), cbar=False)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1a34e1d278>




![png](output_28_1.png)



```python
for key in md:
    print(key, '   ',md[key].shape)


```

    movies     (26517, 9)
    title_crew     (146144, 3)
    tn_budgets     (5782, 6)
    title_ratings     (73856, 3)
    name_basics     (606648, 6)
    title_principals     (1028186, 6)
    title_akas     (331703, 8)
    bom_movie_gross     (3387, 5)
    title_basics     (146144, 6)


<h3>check for duplicates</h3>


```python
for key in md:
    a = md[key].duplicated().sum()
    b = (a[a>0], key)
    print(a, 'FILE:', b, )
#     a = md[item].duplicated()
# print(a[a])
```

    1020 FILE: (array([1020]), 'movies')
    0 FILE: (array([], dtype=int64), 'title_crew')
    0 FILE: (array([], dtype=int64), 'tn_budgets')
    0 FILE: (array([], dtype=int64), 'title_ratings')
    0 FILE: (array([], dtype=int64), 'name_basics')
    0 FILE: (array([], dtype=int64), 'title_principals')
    0 FILE: (array([], dtype=int64), 'title_akas')
    0 FILE: (array([], dtype=int64), 'bom_movie_gross')
    0 FILE: (array([], dtype=int64), 'title_basics')


<h3>3. check for column name consistency</h3>


```python

for key in md:
    columns = (md[key].columns)
    print(key, columns)
```

    movies Index(['genre_ids', 'id', 'original_language', 'original_title', 'popularity',
           'release_date', 'title', 'vote_average', 'vote_count'],
          dtype='object')
    title_crew Index(['tconst', 'directors', 'writers'], dtype='object')
    tn_budgets Index(['id', 'release_date', 'movie', 'production_budget', 'domestic_gross',
           'worldwide_gross'],
          dtype='object')
    title_ratings Index(['tconst', 'averagerating', 'numvotes'], dtype='object')
    name_basics Index(['nconst', 'primary_name', 'birth_year', 'death_year',
           'primary_profession', 'known_for_titles'],
          dtype='object')
    title_principals Index(['tconst', 'ordering', 'nconst', 'category', 'job', 'characters'], dtype='object')
    title_akas Index(['title_id', 'ordering', 'title', 'region', 'language', 'types',
           'attributes', 'is_original_title'],
          dtype='object')
    bom_movie_gross Index(['title', 'studio', 'domestic_gross', 'foreign_gross', 'year'], dtype='object')
    title_basics Index(['tconst', 'primary_title', 'original_title', 'start_year',
           'runtime_minutes', 'genres'],
          dtype='object')



```python

md['title_ratings'].columns     
md['title_ratings'].columns = ['tconst', 'average_rating', 'num_votes']
md['title_ratings'].columns

    
    
```




    Index(['tconst', 'average_rating', 'num_votes'], dtype='object')






```python
md['movies'].head(2)
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
      <th>genre_ids</th>
      <th>id</th>
      <th>original_language</th>
      <th>original_title</th>
      <th>popularity</th>
      <th>release_date</th>
      <th>title</th>
      <th>vote_average</th>
      <th>vote_count</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>[12, 14, 10751]</td>
      <td>12444</td>
      <td>en</td>
      <td>Harry Potter and the Deathly Hallows: Part 1</td>
      <td>33.533</td>
      <td>2010-11-19</td>
      <td>Harry Potter and the Deathly Hallows: Part 1</td>
      <td>7.7</td>
      <td>10788</td>
    </tr>
    <tr>
      <td>1</td>
      <td>[14, 12, 16, 10751]</td>
      <td>10191</td>
      <td>en</td>
      <td>How to Train Your Dragon</td>
      <td>28.734</td>
      <td>2010-03-26</td>
      <td>How to Train Your Dragon</td>
      <td>7.7</td>
      <td>7610</td>
    </tr>
  </tbody>
</table>
</div>



<h2>movies file</h2>


```python

```

<h3>1.  check genre_ids
    2.  primary key 
    3.  change datetime</h3>



```python


```


```python
#validate the genre numbers from an external file
count=0
for item in md['movies']['genre_ids']:
    for num in item:
        if num not in genre_ids:
            pass
        else:
            count +=1
count
```




    0



<h3>2. Primary Key is ID</h3>


```python
md['movies'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 26517 entries, 0 to 26516
    Data columns (total 9 columns):
    genre_ids            26517 non-null object
    id                   26517 non-null int64
    original_language    26517 non-null object
    original_title       26517 non-null object
    popularity           26517 non-null float64
    release_date         26517 non-null object
    title                26517 non-null object
    vote_average         26517 non-null float64
    vote_count           26517 non-null int64
    dtypes: float64(2), int64(2), object(5)
    memory usage: 1.8+ MB



```python
md['movies']['genre_ids'][0]
```




    '[12, 14, 10751]'



<h3>3. datetime changed</h3>


```python

pd.to_datetime(md['movies']['release_date'])
```




    0       2010-11-19
    1       2010-03-26
    2       2010-05-07
    3       1995-11-22
    4       2010-07-16
               ...    
    26512   2018-10-13
    26513   2018-05-01
    26514   2018-10-01
    26515   2018-06-22
    26516   2018-10-05
    Name: release_date, Length: 26517, dtype: datetime64[ns]




```python
md['movies'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 26517 entries, 0 to 26516
    Data columns (total 9 columns):
    genre_ids            26517 non-null object
    id                   26517 non-null int64
    original_language    26517 non-null object
    original_title       26517 non-null object
    popularity           26517 non-null float64
    release_date         26517 non-null object
    title                26517 non-null object
    vote_average         26517 non-null float64
    vote_count           26517 non-null int64
    dtypes: float64(2), int64(2), object(5)
    memory usage: 1.8+ MB


<h2>title_crew file</h2>


```python
#no cleaning of this file
md['title_crew'].head(2)
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
      <th>tconst</th>
      <th>directors</th>
      <th>writers</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>tt0285252</td>
      <td>nm0899854</td>
      <td>nm0899854</td>
    </tr>
    <tr>
      <td>1</td>
      <td>tt0438973</td>
      <td>NaN</td>
      <td>nm0175726,nm1802864</td>
    </tr>
  </tbody>
</table>
</div>




```python
md['title_crew'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 146144 entries, 0 to 146143
    Data columns (total 3 columns):
    tconst       146144 non-null object
    directors    140417 non-null object
    writers      110261 non-null object
    dtypes: object(3)
    memory usage: 3.3+ MB



```python

```

<h2>tn_budgets file</h2>

<h3>budgets file changes:</h4>


<h4>1.  check dtypes, change dtypes for prod/dom/gros
    2.  primary key 3. release_date</h4>

|<h4>1. change dtypes to 'int'</h4>


```python
md['tn_budgets']['production_budget'] = md['tn_budgets']['production_budget'].str.replace('$', "").str.replace(',', '')
md['tn_budgets']['domestic_gross'] = md['tn_budgets']['domestic_gross'].str.replace('$', "").str.replace(',', '')
md['tn_budgets']['worldwide_gross'] = md['tn_budgets']['worldwide_gross'].str.replace('$', "").str.replace(',', '')
```


```python
tn_budgets.head()
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
      <th>id</th>
      <th>release_date</th>
      <th>movie</th>
      <th>production_budget</th>
      <th>domestic_gross</th>
      <th>worldwide_gross</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>Dec 18, 2009</td>
      <td>Avatar</td>
      <td>425000000</td>
      <td>760507625</td>
      <td>2776345279</td>
    </tr>
    <tr>
      <td>1</td>
      <td>2</td>
      <td>May 20, 2011</td>
      <td>Pirates of the Caribbean: On Stranger Tides</td>
      <td>410600000</td>
      <td>241063875</td>
      <td>1045663875</td>
    </tr>
    <tr>
      <td>2</td>
      <td>3</td>
      <td>Jun 7, 2019</td>
      <td>Dark Phoenix</td>
      <td>350000000</td>
      <td>42762350</td>
      <td>149762350</td>
    </tr>
    <tr>
      <td>3</td>
      <td>4</td>
      <td>May 1, 2015</td>
      <td>Avengers: Age of Ultron</td>
      <td>330600000</td>
      <td>459005868</td>
      <td>1403013963</td>
    </tr>
    <tr>
      <td>4</td>
      <td>5</td>
      <td>Dec 15, 2017</td>
      <td>Star Wars Ep. VIII: The Last Jedi</td>
      <td>317000000</td>
      <td>620181382</td>
      <td>1316721747</td>
    </tr>
  </tbody>
</table>
</div>




```python
md['tn_budgets']['production_budget'] = md['tn_budgets']['production_budget'].astype('int')
md['tn_budgets']['domestic_gross'] = md['tn_budgets']['domestic_gross'].astype('int')
md['tn_budgets']['worldwide_gross'] = md['tn_budgets']['worldwide_gross'].astype('int')

```


```python
md['tn_budgets']['worldwide_gross']
```




    0       2776345279
    1       1045663875
    2        149762350
    3       1403013963
    4       1316721747
               ...    
    5777             0
    5778        240495
    5779          1338
    5780             0
    5781        181041
    Name: worldwide_gross, Length: 5782, dtype: int64




```python


```

<h3>2. Primary Key is ID</h3>


```python
file = []
for item in md:
    file.append('id')
pd.to_datetime(md['tn_budgets']['release_date'])
```




    0      2009-12-18
    1      2011-05-20
    2      2019-06-07
    3      2015-05-01
    4      2017-12-15
              ...    
    5777   2018-12-31
    5778   1999-04-02
    5779   2005-07-13
    5780   2015-09-29
    5781   2005-08-05
    Name: release_date, Length: 5782, dtype: datetime64[ns]



<h2>title_ratings File</h2>


```python
md['title_ratings'].head(2)
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
      <th>tconst</th>
      <th>average_rating</th>
      <th>num_votes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>tt10356526</td>
      <td>8.3</td>
      <td>31</td>
    </tr>
    <tr>
      <td>1</td>
      <td>tt10384606</td>
      <td>8.9</td>
      <td>559</td>
    </tr>
  </tbody>
</table>
</div>



<h3>2. Primary Key is tconst</h3>


```python
md['title_ratings'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 73856 entries, 0 to 73855
    Data columns (total 3 columns):
    tconst            73856 non-null object
    average_rating    73856 non-null float64
    num_votes         73856 non-null int64
    dtypes: float64(1), int64(1), object(1)
    memory usage: 1.7+ MB


<h2>name_basics File</h2>


```python
md['name_basics'].head(2)
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
      <th>nconst</th>
      <th>primary_name</th>
      <th>birth_year</th>
      <th>death_year</th>
      <th>primary_profession</th>
      <th>known_for_titles</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>nm0061671</td>
      <td>Mary Ellen Bauder</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>miscellaneous,production_manager,producer</td>
      <td>tt0837562,tt2398241,tt0844471,tt0118553</td>
    </tr>
    <tr>
      <td>1</td>
      <td>nm0061865</td>
      <td>Joseph Bauer</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>composer,music_department,sound_department</td>
      <td>tt0896534,tt6791238,tt0287072,tt1682940</td>
    </tr>
  </tbody>
</table>
</div>



<h3>name_basics file changes:</h3>
<h4>1.  delete birth/death years,
    2.  fill na's 
    3.  primary key


```python

```

<h3>1. delete birth/death years</h3>


```python
md['name_basics'].drop(['birth_year'], axis=1, inplace=True)
md['name_basics'].drop(['death_year'], axis = 1, inplace=True)
```

<h3>1. fill na's</h3>


```python
#md['name_basics']['primary_profession'][md['name_basics']['primary_profession'].isna()]
# for item in md['name_basics']['primary_profession']:
#     item.fillna('Unknown', inplace=True)
md['name_basics']['primary_profession'].fillna('Unknown', inplace=True)
md['name_basics']['known_for_titles'].fillna('Unknown', inplace=True)
md['name_basics'].info()




```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 606648 entries, 0 to 606647
    Data columns (total 4 columns):
    nconst                606648 non-null object
    primary_name          606648 non-null object
    primary_profession    606648 non-null object
    known_for_titles      606648 non-null object
    dtypes: object(4)
    memory usage: 18.5+ MB



```python
md['name_basics'].head(2)
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
      <th>nconst</th>
      <th>primary_name</th>
      <th>primary_profession</th>
      <th>known_for_titles</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>nm0061671</td>
      <td>Mary Ellen Bauder</td>
      <td>miscellaneous,production_manager,producer</td>
      <td>tt0837562,tt2398241,tt0844471,tt0118553</td>
    </tr>
    <tr>
      <td>1</td>
      <td>nm0061865</td>
      <td>Joseph Bauer</td>
      <td>composer,music_department,sound_department</td>
      <td>tt0896534,tt6791238,tt0287072,tt1682940</td>
    </tr>
  </tbody>
</table>
</div>




```python
md['name_basics'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 606648 entries, 0 to 606647
    Data columns (total 4 columns):
    nconst                606648 non-null object
    primary_name          606648 non-null object
    primary_profession    606648 non-null object
    known_for_titles      606648 non-null object
    dtypes: object(4)
    memory usage: 18.5+ MB


<h3>2. Primary Key is nconst</h3>


```python

```

<h2>title_principals file</h2>


```python
md['title_principals'].head(2)
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
      <th>tconst</th>
      <th>ordering</th>
      <th>nconst</th>
      <th>category</th>
      <th>job</th>
      <th>characters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>tt0111414</td>
      <td>1</td>
      <td>nm0246005</td>
      <td>actor</td>
      <td>NaN</td>
      <td>["The Man"]</td>
    </tr>
    <tr>
      <td>1</td>
      <td>tt0111414</td>
      <td>2</td>
      <td>nm0398271</td>
      <td>director</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
md['title_principals'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 1028186 entries, 0 to 1028185
    Data columns (total 6 columns):
    tconst        1028186 non-null object
    ordering      1028186 non-null int64
    nconst        1028186 non-null object
    category      1028186 non-null object
    job           177684 non-null object
    characters    393360 non-null object
    dtypes: int64(1), object(5)
    memory usage: 47.1+ MB


<h3>title_principals file changes:</h3>
<h4>1.  delete job, characters</h4>
<h4>2.  primary key</h4>


```python
md['title_principals'] = md['title_principals'].drop(['job'], axis=1)
md['title_principals'] = md['title_principals'].drop(['characters'], axis = 1)
```


```python
md['title_principals'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 1028186 entries, 0 to 1028185
    Data columns (total 4 columns):
    tconst      1028186 non-null object
    ordering    1028186 non-null int64
    nconst      1028186 non-null object
    category    1028186 non-null object
    dtypes: int64(1), object(3)
    memory usage: 31.4+ MB


<h3>2. Primary Key is tconst/nconst</h3>

<h2>title_akas file</h2>


```python
md['title_akas'].head(2)
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
      <th>title_id</th>
      <th>ordering</th>
      <th>title</th>
      <th>region</th>
      <th>language</th>
      <th>types</th>
      <th>attributes</th>
      <th>is_original_title</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>tt0369610</td>
      <td>10</td>
      <td>Джурасик свят</td>
      <td>BG</td>
      <td>bg</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
    </tr>
    <tr>
      <td>1</td>
      <td>tt0369610</td>
      <td>11</td>
      <td>Jurashikku warudo</td>
      <td>JP</td>
      <td>NaN</td>
      <td>imdbDisplay</td>
      <td>NaN</td>
      <td>0.0</td>
    </tr>
  </tbody>
</table>
</div>




```python
md['title_akas'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 331703 entries, 0 to 331702
    Data columns (total 8 columns):
    title_id             331703 non-null object
    ordering             331703 non-null int64
    title                331703 non-null object
    region               278410 non-null object
    language             41715 non-null object
    types                168447 non-null object
    attributes           14925 non-null object
    is_original_title    331678 non-null float64
    dtypes: float64(1), int64(1), object(6)
    memory usage: 20.2+ MB



```python
md['title_akas'].drop(['attributes'], axis=1, inplace=True)
md['title_akas'].drop(['language'], axis=1, inplace=True)

```


```python
md['title_akas'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 331703 entries, 0 to 331702
    Data columns (total 6 columns):
    title_id             331703 non-null object
    ordering             331703 non-null int64
    title                331703 non-null object
    region               278410 non-null object
    types                168447 non-null object
    is_original_title    331678 non-null float64
    dtypes: float64(1), int64(1), object(4)
    memory usage: 15.2+ MB



<h2>bom_movie_gross file</h2>


```python
md['bom_movie_gross'].head(2)
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
      <th>title</th>
      <th>studio</th>
      <th>domestic_gross</th>
      <th>foreign_gross</th>
      <th>year</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>Toy Story 3</td>
      <td>BV</td>
      <td>415000000.0</td>
      <td>652000000</td>
      <td>2010</td>
    </tr>
    <tr>
      <td>1</td>
      <td>Alice in Wonderland (2010)</td>
      <td>BV</td>
      <td>334200000.0</td>
      <td>691300000</td>
      <td>2010</td>
    </tr>
  </tbody>
</table>
</div>



<h2>title_basics</h2>


```python
md['title_basics'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 146144 entries, 0 to 146143
    Data columns (total 6 columns):
    tconst             146144 non-null object
    primary_title      146144 non-null object
    original_title     146123 non-null object
    start_year         146144 non-null int64
    runtime_minutes    114405 non-null float64
    genres             140736 non-null object
    dtypes: float64(1), int64(1), object(4)
    memory usage: 6.7+ MB



```python
md['title_basics'].head(2)
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
      <th>tconst</th>
      <th>primary_title</th>
      <th>original_title</th>
      <th>start_year</th>
      <th>runtime_minutes</th>
      <th>genres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>tt0063540</td>
      <td>Sunghursh</td>
      <td>Sunghursh</td>
      <td>2013</td>
      <td>175.0</td>
      <td>Action,Crime,Drama</td>
    </tr>
    <tr>
      <td>1</td>
      <td>tt0066787</td>
      <td>One Day Before the Rainy Season</td>
      <td>Ashad Ka Ek Din</td>
      <td>2019</td>
      <td>114.0</td>
      <td>Biography,Drama</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


```python

```


```python

```

<h1>Merging the Data</h1>




```python
md['tn_budgets'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 5782 entries, 0 to 5781
    Data columns (total 6 columns):
    id                   5782 non-null int64
    release_date         5782 non-null object
    movie                5782 non-null object
    production_budget    5782 non-null int64
    domestic_gross       5782 non-null int64
    worldwide_gross      5782 non-null int64
    dtypes: int64(4), object(2)
    memory usage: 271.2+ KB


## Explode the list in the tn_budgets file##


```python
pd.options.display.max_rows = 500
```


```python
md['movies']['genre_ids'][0]
```




    '[12, 14, 10751]'




```python
md['movies'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 26517 entries, 0 to 26516
    Data columns (total 9 columns):
    genre_ids            26517 non-null object
    id                   26517 non-null int64
    original_language    26517 non-null object
    original_title       26517 non-null object
    popularity           26517 non-null float64
    release_date         26517 non-null object
    title                26517 non-null object
    vote_average         26517 non-null float64
    vote_count           26517 non-null int64
    dtypes: float64(2), int64(2), object(5)
    memory usage: 1.8+ MB



```python
md['movies'].info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 26517 entries, 0 to 26516
    Data columns (total 9 columns):
    genre_ids            26517 non-null object
    id                   26517 non-null int64
    original_language    26517 non-null object
    original_title       26517 non-null object
    popularity           26517 non-null float64
    release_date         26517 non-null object
    title                26517 non-null object
    vote_average         26517 non-null float64
    vote_count           26517 non-null int64
    dtypes: float64(2), int64(2), object(5)
    memory usage: 1.8+ MB


<h2>Merge Files</h2>


```python
tn_budgets = md['tn_budgets']
movies = md['movies']
title_crew = md['title_crew']
title_ratings = md['title_ratings']
```


```python
tn_budgets.head()
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
      <th>id</th>
      <th>release_date</th>
      <th>movie</th>
      <th>production_budget</th>
      <th>domestic_gross</th>
      <th>worldwide_gross</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>1</td>
      <td>Dec 18, 2009</td>
      <td>Avatar</td>
      <td>425000000</td>
      <td>760507625</td>
      <td>2776345279</td>
    </tr>
    <tr>
      <td>1</td>
      <td>2</td>
      <td>May 20, 2011</td>
      <td>Pirates of the Caribbean: On Stranger Tides</td>
      <td>410600000</td>
      <td>241063875</td>
      <td>1045663875</td>
    </tr>
    <tr>
      <td>2</td>
      <td>3</td>
      <td>Jun 7, 2019</td>
      <td>Dark Phoenix</td>
      <td>350000000</td>
      <td>42762350</td>
      <td>149762350</td>
    </tr>
    <tr>
      <td>3</td>
      <td>4</td>
      <td>May 1, 2015</td>
      <td>Avengers: Age of Ultron</td>
      <td>330600000</td>
      <td>459005868</td>
      <td>1403013963</td>
    </tr>
    <tr>
      <td>4</td>
      <td>5</td>
      <td>Dec 15, 2017</td>
      <td>Star Wars Ep. VIII: The Last Jedi</td>
      <td>317000000</td>
      <td>620181382</td>
      <td>1316721747</td>
    </tr>
  </tbody>
</table>
</div>




```python
df = md['movies'].merge(md['tn_budgets'], how='inner', left_on='original_title', right_on='movie')
df.head(2)
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
      <th>genre_ids</th>
      <th>id_x</th>
      <th>original_language</th>
      <th>original_title</th>
      <th>popularity</th>
      <th>release_date_x</th>
      <th>title</th>
      <th>vote_average</th>
      <th>vote_count</th>
      <th>id_y</th>
      <th>release_date_y</th>
      <th>movie</th>
      <th>production_budget</th>
      <th>domestic_gross</th>
      <th>worldwide_gross</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>[14, 12, 16, 10751]</td>
      <td>10191</td>
      <td>en</td>
      <td>How to Train Your Dragon</td>
      <td>28.734</td>
      <td>2010-03-26</td>
      <td>How to Train Your Dragon</td>
      <td>7.7</td>
      <td>7610</td>
      <td>30</td>
      <td>Mar 26, 2010</td>
      <td>How to Train Your Dragon</td>
      <td>165000000</td>
      <td>217581232</td>
      <td>494870992</td>
    </tr>
    <tr>
      <td>1</td>
      <td>[12, 28, 878]</td>
      <td>10138</td>
      <td>en</td>
      <td>Iron Man 2</td>
      <td>28.515</td>
      <td>2010-05-07</td>
      <td>Iron Man 2</td>
      <td>6.8</td>
      <td>12368</td>
      <td>15</td>
      <td>May 7, 2010</td>
      <td>Iron Man 2</td>
      <td>170000000</td>
      <td>312433331</td>
      <td>621156389</td>
    </tr>
  </tbody>
</table>
</div>




```python

df['foreign_gross'] = df['worldwide_gross'] - df['domestic_gross']  
```


```python
md['bom_movie_gross'].info()
#df1.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 3387 entries, 0 to 3386
    Data columns (total 5 columns):
    title             3387 non-null object
    studio            3382 non-null object
    domestic_gross    3359 non-null float64
    foreign_gross     2037 non-null object
    year              3387 non-null int64
    dtypes: float64(1), int64(1), object(3)
    memory usage: 132.4+ KB



```python
df1 = pd.DataFrame()
df1 = md['title_crew']
df1 = df1.merge(md['title_ratings'], how='inner', left_on='tconst', right_on='tconst')
df1 = df1.merge(md['title_principals'], how='inner', left_on='tconst', right_on='tconst')
df1 = df1.merge(md['name_basics'], how='inner', left_on='nconst', right_on='nconst')



```


```python
df1 = df1.merge(md['title_basics'], how = 'left', left_on='tconst', right_on='tconst')
#df1 = df1.merge(md['bom_movie_gross'], how='left', left_on='domestic_gross', right_on='domestic_gross')
#df.merge(df1, how='left',left_on='domestic_gross', right_on='domestic_gross')
```


```python
df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    Int64Index: 2316 entries, 0 to 2315
    Data columns (total 16 columns):
    genre_ids            2316 non-null object
    id_x                 2316 non-null int64
    original_language    2316 non-null object
    original_title       2316 non-null object
    popularity           2316 non-null float64
    release_date_x       2316 non-null object
    title                2316 non-null object
    vote_average         2316 non-null float64
    vote_count           2316 non-null int64
    id_y                 2316 non-null int64
    release_date_y       2316 non-null object
    movie                2316 non-null object
    production_budget    2316 non-null int64
    domestic_gross       2316 non-null int64
    worldwide_gross      2316 non-null int64
    foreign_gross        2316 non-null int64
    dtypes: float64(2), int64(7), object(7)
    memory usage: 307.6+ KB



```python
df1.info()
```

    <class 'pandas.core.frame.DataFrame'>
    Int64Index: 629598 entries, 0 to 629597
    Data columns (total 16 columns):
    tconst                629598 non-null object
    directors             626086 non-null object
    writers               558824 non-null object
    average_rating        629598 non-null float64
    num_votes             629598 non-null int64
    ordering              629598 non-null int64
    nconst                629598 non-null object
    category              629598 non-null object
    primary_name          629598 non-null object
    primary_profession    629598 non-null object
    known_for_titles      629598 non-null object
    primary_title         629598 non-null object
    original_title        629598 non-null object
    start_year            629598 non-null int64
    runtime_minutes       567677 non-null float64
    genres                624458 non-null object
    dtypes: float64(2), int64(3), object(11)
    memory usage: 81.7+ MB



```python

```


```python
sns.heatmap(df.isnull(), cbar=False)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1aac4d1dd8>




![png](output_118_1.png)



```python
sns.heatmap(df1.isnull(), cbar=False)
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1af7764c88>




![png](output_119_1.png)




<h1>Analysis<h1>


```python
df.columns
```




    Index(['genre_ids', 'id_x', 'original_language', 'original_title',
           'popularity', 'release_date_x', 'title', 'vote_average', 'vote_count',
           'id_y', 'release_date_y', 'movie', 'production_budget',
           'domestic_gross', 'worldwide_gross', 'foreign_gross'],
          dtype='object')




```python
import plotly.express as px

```


```python
#plt.hexbin(df['original_title'], df['domestic_gross'], gridsize=(150,150) )
#plt.show()

```


```python
#hue="worldwide_gross",
```


```python
g = sns.lmplot(y='domestic_gross', x='worldwide_gross', height=5, data=df)
```


![png](output_125_0.png)



```python
# Two ratings outliers - delete rows
df['popularity'].sort_values( ascending=False)
df.drop([1171], inplace=True)
df.drop([2182], inplace=True)
df.head(2)
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
      <th>genre_ids</th>
      <th>id_x</th>
      <th>original_language</th>
      <th>original_title</th>
      <th>popularity</th>
      <th>release_date_x</th>
      <th>title</th>
      <th>vote_average</th>
      <th>vote_count</th>
      <th>id_y</th>
      <th>release_date_y</th>
      <th>movie</th>
      <th>production_budget</th>
      <th>domestic_gross</th>
      <th>worldwide_gross</th>
      <th>foreign_gross</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>[14, 12, 16, 10751]</td>
      <td>10191</td>
      <td>en</td>
      <td>How to Train Your Dragon</td>
      <td>28.734</td>
      <td>2010-03-26</td>
      <td>How to Train Your Dragon</td>
      <td>7.7</td>
      <td>7610</td>
      <td>30</td>
      <td>Mar 26, 2010</td>
      <td>How to Train Your Dragon</td>
      <td>165000000</td>
      <td>217581232</td>
      <td>494870992</td>
      <td>277289760</td>
    </tr>
    <tr>
      <td>1</td>
      <td>[12, 28, 878]</td>
      <td>10138</td>
      <td>en</td>
      <td>Iron Man 2</td>
      <td>28.515</td>
      <td>2010-05-07</td>
      <td>Iron Man 2</td>
      <td>6.8</td>
      <td>12368</td>
      <td>15</td>
      <td>May 7, 2010</td>
      <td>Iron Man 2</td>
      <td>170000000</td>
      <td>312433331</td>
      <td>621156389</td>
      <td>308723058</td>
    </tr>
  </tbody>
</table>
</div>




```python
#Avatar an outlier for worldwide gross - drop
df.sort_values(['worldwide_gross'], ascending=False)
df.drop([6], inplace=True)
df.head(7)
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
      <th>genre_ids</th>
      <th>id_x</th>
      <th>original_language</th>
      <th>original_title</th>
      <th>popularity</th>
      <th>release_date_x</th>
      <th>title</th>
      <th>vote_average</th>
      <th>vote_count</th>
      <th>id_y</th>
      <th>release_date_y</th>
      <th>movie</th>
      <th>production_budget</th>
      <th>domestic_gross</th>
      <th>worldwide_gross</th>
      <th>foreign_gross</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0</td>
      <td>[14, 12, 16, 10751]</td>
      <td>10191</td>
      <td>en</td>
      <td>How to Train Your Dragon</td>
      <td>28.734</td>
      <td>2010-03-26</td>
      <td>How to Train Your Dragon</td>
      <td>7.7</td>
      <td>7610</td>
      <td>30</td>
      <td>Mar 26, 2010</td>
      <td>How to Train Your Dragon</td>
      <td>165000000</td>
      <td>217581232</td>
      <td>494870992</td>
      <td>277289760</td>
    </tr>
    <tr>
      <td>1</td>
      <td>[12, 28, 878]</td>
      <td>10138</td>
      <td>en</td>
      <td>Iron Man 2</td>
      <td>28.515</td>
      <td>2010-05-07</td>
      <td>Iron Man 2</td>
      <td>6.8</td>
      <td>12368</td>
      <td>15</td>
      <td>May 7, 2010</td>
      <td>Iron Man 2</td>
      <td>170000000</td>
      <td>312433331</td>
      <td>621156389</td>
      <td>308723058</td>
    </tr>
    <tr>
      <td>2</td>
      <td>[16, 35, 10751]</td>
      <td>862</td>
      <td>en</td>
      <td>Toy Story</td>
      <td>28.005</td>
      <td>1995-11-22</td>
      <td>Toy Story</td>
      <td>7.9</td>
      <td>10174</td>
      <td>37</td>
      <td>Nov 22, 1995</td>
      <td>Toy Story</td>
      <td>30000000</td>
      <td>191796233</td>
      <td>364545516</td>
      <td>172749283</td>
    </tr>
    <tr>
      <td>3</td>
      <td>[16, 35, 10751]</td>
      <td>862</td>
      <td>en</td>
      <td>Toy Story</td>
      <td>28.005</td>
      <td>1995-11-22</td>
      <td>Toy Story</td>
      <td>7.9</td>
      <td>10174</td>
      <td>37</td>
      <td>Nov 22, 1995</td>
      <td>Toy Story</td>
      <td>30000000</td>
      <td>191796233</td>
      <td>364545516</td>
      <td>172749283</td>
    </tr>
    <tr>
      <td>4</td>
      <td>[28, 878, 12]</td>
      <td>27205</td>
      <td>en</td>
      <td>Inception</td>
      <td>27.920</td>
      <td>2010-07-16</td>
      <td>Inception</td>
      <td>8.3</td>
      <td>22186</td>
      <td>38</td>
      <td>Jul 16, 2010</td>
      <td>Inception</td>
      <td>160000000</td>
      <td>292576195</td>
      <td>835524642</td>
      <td>542948447</td>
    </tr>
    <tr>
      <td>5</td>
      <td>[12, 14, 10751]</td>
      <td>32657</td>
      <td>en</td>
      <td>Percy Jackson &amp; the Olympians: The Lightning T...</td>
      <td>26.691</td>
      <td>2010-02-11</td>
      <td>Percy Jackson &amp; the Olympians: The Lightning T...</td>
      <td>6.1</td>
      <td>4229</td>
      <td>17</td>
      <td>Feb 12, 2010</td>
      <td>Percy Jackson &amp; the Olympians: The Lightning T...</td>
      <td>95000000</td>
      <td>88768303</td>
      <td>223050874</td>
      <td>134282571</td>
    </tr>
    <tr>
      <td>7</td>
      <td>[16, 10751, 35]</td>
      <td>10193</td>
      <td>en</td>
      <td>Toy Story 3</td>
      <td>24.445</td>
      <td>2010-06-17</td>
      <td>Toy Story 3</td>
      <td>7.7</td>
      <td>8340</td>
      <td>47</td>
      <td>Jun 18, 2010</td>
      <td>Toy Story 3</td>
      <td>200000000</td>
      <td>415004880</td>
      <td>1068879522</td>
      <td>653874642</td>
    </tr>
  </tbody>
</table>
</div>




```python
g = sns.lmplot(y='domestic_gross', x='worldwide_gross', height=5, data=df)
```


![png](output_128_0.png)



```python
df['count_films'] = np.arange(len(df['id_x']+1))
df['count_films']

```




    0          0
    1          1
    2          2
    3          3
    4          4
            ... 
    2311    2308
    2312    2309
    2313    2310
    2314    2311
    2315    2312
    Name: count_films, Length: 2313, dtype: int64




```python
shape_df = df.shape
shape_df1 = df1.shape
print(shape_df, shape_df1)
#df_genre=df.groupby(by = ['genre_ids']).count()
#l.set_index(pd.Index(len(l)-1), inplace=True)
#l['genre_ids']
# l.head(2)
# l.index
```

    (2313, 17) (629598, 16)



```python

# df['worldwide_net'] = df['worldwide_gross'] - df['production_budget']
# df['foreign_production'] = pd.DataFrame()
# for item in df['foreign_gross' > 0:
#         df['foreign_production'] += item
#df.dtypes
#mpl.pyplot.hist(df['domestic_gross'], bins = 20)
# length = np.arange(1, len(df-1))
# length
#x
# y = df['domestic_gross']
# g = sns.lmplot(y, x, height=5, data=df)
```


```python
df = df.sort_values('worldwide_gross', ascending = True)
# zero_sales = df[df['worldwide_gross'] == 0]
# zero_sales.head()
# zero_sales.info()
df
#df.head()
# # for item in df['original_title']:
# #     if item in zero_sales['original_title']:
# #         item.drop()
# #df.shape


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
      <th>genre_ids</th>
      <th>id_x</th>
      <th>original_language</th>
      <th>original_title</th>
      <th>popularity</th>
      <th>release_date_x</th>
      <th>title</th>
      <th>vote_average</th>
      <th>vote_count</th>
      <th>id_y</th>
      <th>release_date_y</th>
      <th>movie</th>
      <th>production_budget</th>
      <th>domestic_gross</th>
      <th>worldwide_gross</th>
      <th>foreign_gross</th>
      <th>count_films</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1157</td>
      <td>[]</td>
      <td>334130</td>
      <td>en</td>
      <td>Open Secret</td>
      <td>0.600</td>
      <td>2013-11-03</td>
      <td>Open Secret</td>
      <td>7.0</td>
      <td>1</td>
      <td>97</td>
      <td>Mar 25, 2015</td>
      <td>Open Secret</td>
      <td>100000</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1156</td>
    </tr>
    <tr>
      <td>1645</td>
      <td>[28]</td>
      <td>326284</td>
      <td>en</td>
      <td>Pound of Flesh</td>
      <td>6.921</td>
      <td>2015-05-07</td>
      <td>Pound of Flesh</td>
      <td>5.4</td>
      <td>95</td>
      <td>76</td>
      <td>May 15, 2015</td>
      <td>Pound of Flesh</td>
      <td>7500000</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1643</td>
    </tr>
    <tr>
      <td>1108</td>
      <td>[99]</td>
      <td>250902</td>
      <td>en</td>
      <td>The Image Revolution</td>
      <td>1.313</td>
      <td>2013-11-21</td>
      <td>The Image Revolution</td>
      <td>6.3</td>
      <td>4</td>
      <td>26</td>
      <td>Dec 31, 2014</td>
      <td>The Image Revolution</td>
      <td>50000</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1107</td>
    </tr>
    <tr>
      <td>1109</td>
      <td>[99]</td>
      <td>250902</td>
      <td>en</td>
      <td>The Image Revolution</td>
      <td>1.313</td>
      <td>2013-11-21</td>
      <td>The Image Revolution</td>
      <td>6.3</td>
      <td>4</td>
      <td>26</td>
      <td>Dec 31, 2014</td>
      <td>The Image Revolution</td>
      <td>50000</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1108</td>
    </tr>
    <tr>
      <td>1639</td>
      <td>[28, 27, 53]</td>
      <td>244316</td>
      <td>en</td>
      <td>Into the Grizzly Maze</td>
      <td>7.133</td>
      <td>2015-06-26</td>
      <td>Into the Grizzly Maze</td>
      <td>5.3</td>
      <td>121</td>
      <td>47</td>
      <td>May 19, 2015</td>
      <td>Into the Grizzly Maze</td>
      <td>10000000</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1637</td>
    </tr>
    <tr>
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
      <td>567</td>
      <td>[28, 16]</td>
      <td>86841</td>
      <td>en</td>
      <td>Black Panther</td>
      <td>2.058</td>
      <td>2011-01-18</td>
      <td>Black Panther</td>
      <td>5.1</td>
      <td>11</td>
      <td>42</td>
      <td>Feb 16, 2018</td>
      <td>Black Panther</td>
      <td>200000000</td>
      <td>700059566</td>
      <td>1348258224</td>
      <td>648198658</td>
      <td>566</td>
    </tr>
    <tr>
      <td>1461</td>
      <td>[28, 12, 878]</td>
      <td>99861</td>
      <td>en</td>
      <td>Avengers: Age of Ultron</td>
      <td>44.383</td>
      <td>2015-05-01</td>
      <td>Avengers: Age of Ultron</td>
      <td>7.3</td>
      <td>13457</td>
      <td>4</td>
      <td>May 1, 2015</td>
      <td>Avengers: Age of Ultron</td>
      <td>330600000</td>
      <td>459005868</td>
      <td>1403013963</td>
      <td>944008095</td>
      <td>1459</td>
    </tr>
    <tr>
      <td>632</td>
      <td>[878, 28, 12]</td>
      <td>24428</td>
      <td>en</td>
      <td>The Avengers</td>
      <td>50.289</td>
      <td>2012-05-04</td>
      <td>The Avengers</td>
      <td>7.6</td>
      <td>19673</td>
      <td>27</td>
      <td>May 4, 2012</td>
      <td>The Avengers</td>
      <td>225000000</td>
      <td>623279547</td>
      <td>1517935897</td>
      <td>894656350</td>
      <td>631</td>
    </tr>
    <tr>
      <td>1483</td>
      <td>[28, 80, 53]</td>
      <td>168259</td>
      <td>en</td>
      <td>Furious 7</td>
      <td>20.396</td>
      <td>2015-04-03</td>
      <td>Furious 7</td>
      <td>7.3</td>
      <td>6538</td>
      <td>67</td>
      <td>Apr 3, 2015</td>
      <td>Furious 7</td>
      <td>190000000</td>
      <td>353007020</td>
      <td>1518722794</td>
      <td>1165715774</td>
      <td>1481</td>
    </tr>
    <tr>
      <td>1478</td>
      <td>[28, 12, 878, 53]</td>
      <td>135397</td>
      <td>en</td>
      <td>Jurassic World</td>
      <td>20.709</td>
      <td>2015-06-12</td>
      <td>Jurassic World</td>
      <td>6.6</td>
      <td>14056</td>
      <td>34</td>
      <td>Jun 12, 2015</td>
      <td>Jurassic World</td>
      <td>215000000</td>
      <td>652270625</td>
      <td>1648854864</td>
      <td>996584239</td>
      <td>1476</td>
    </tr>
  </tbody>
</table>
<p>2313 rows × 17 columns</p>
</div>




```python

g = sns.scatterplot(y=df['worldwide_gross'], x=df['original_title'], data=df)
```


![png](output_133_0.png)



```python
# df_ww == df['worldwide_gross'] > 75000000
# df_ww
```


```python
#g = sns.lmplot(x='original_title', y='worldwide_gross', height=5, data=df)
```


```python

```


```python
# imdb_tbasics['genres'] = imdb_tbasics['genres'].str.split(',')
# 7:51
# imdb_tbasics = imdb_tbasics.explode('genres')
#md['title_basics'].columns
df_explode = pd.Dataframe()
#df['genre_ids'] = df['genre_ids'].str.split(',')
df_explode = df.explode('genre_ids')
df_explode
```


```python
# imdb_tbasics['genres'] = imdb_tbasics['genres'].str.split(',')
# 7:51
# imdb_tbasics = imdb_tbasics.explode('genres')
#md['title_basics'].columns
# md['movies']['genre_ids'] = md['movies']['genre_ids'].str.split(',')
# df_explode = md['movies'].explode('genre_ids')
```


```python
#g = sns.lmplot(x='average_ratings', y='worldwide_gross', height=5, data=df)
```


```python

```


```python

```

<h1>Previous sequel work<h1>


```python
import sqlite3 
conn = sqlite3.connect('data.db')
cur = conn.cursor()
```


```python
cur.execute("""DROP TABLE movies""")
cur.execute("""CREATE TABLE movies (
                                id INTEGER PRIMARY KEY,
                                original_language TEXT,
                                original_title TEXT,
                                popularity REAL,
                                release_date TEXT,
                                title TEXT,
                                vote_average REAL,
                                vote_count INTEGER) """) 
```


```python

```


```python
cur.execute("""CREATE TABLE tn_budgets (
                                id INTEGER PRIMARY KEY,
                                release_date TEXT,
                                movie TEXT,
                                production_budget INTEGER,
                                domestic_gross INTEGER,
                                worldwide_gross INTEGER) """) 
```


```python
2cur.execute('''INSERT INTO movies (id, original_language, original_title, popularity, release_date, title, vote_average, vote_count) 
                  VALUES (1244, 'en', 'Harry Potter and the Deathly Hallows: Part 1', 33.533, '2010-11-19', 'Harry Potter and the Deathly Hallows: Part 1', 7.7, 10788);
            ''')
cur.fetchall()
```


```python
cur.execute('''INSERT INTO tn_budgets (id, release_date, movie, production_budget, domestic_gross, worldwide_gross) 
                  VALUES (1, 'Dec 18, 2009', 'Avatar', 425000000, 760507625, 2776345279);
            ''')
cur.fetchall()
```


```python
md['tn_budgets'].head(2)
```


```python
md['tn_budgets'].info()
```




```python
# import tmdbsimple as tmdb
# tmdb.API_KEY = '34fc89c1301220090458386f243b4ab0'
# movie = tmdb.Movies()
# response = movie.info()
# movie.title
# movie.budget
# response = movie.releases()
# for c in movie.countries:
#     if c['iso_3166_1'] == 'US':
#         print(c['certification'])


#movie = tmdbMovies()
```


```python
#movies = md['movies']
#tn_budgets = md['tn_budgets']
```


```python
from pandasql import sqldf
pysqldf = lambda q: sqldf(q, globals())

```


```python
cur.execute("""  SELECT *
         FROM tn_budgets""") 
cur.fetchall()
cur.description
```


```python
md['movies']['release_date']
```


```python

```


```python
md['movies'].head(2)
```
