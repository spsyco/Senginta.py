<p align="center">
    <img src="Senginta.jpg"></img>
</p>

<p align="center">
    All in one Search Engine Scrapper for used by API or Python Module.
</p>

<p align="center">
    <a href="https://youtu.be/-B3CO467Kzo"> How to use: Video</a>
</p>

**`Documentation`** |
------------------- |
[![Documentation](https://img.shields.io/badge/api-reference-blue.svg)]() |

Senginta is All in one Search Engine Scrapper. With traditional scrapping, 
Senginta can be powerful to get result from any Search Engine, and convert
to Json. Now support only for Google Product Search Engine (GShop, GVideo 
and many too) and Baidu Search Engine.

Senginta was originally developed by me alone. So, if you want to contribute for
support another search engine, let's fork this Repository. 

Senginta provides beta Python.

## Install

```
$ pip install senginta
```

To update senginta to the latest version, add `--upgrade` flag to the above
commands.

#### Try your first Senginta program

```shell
$ python
```

```python
>>> from senginta.static.Google import GSearch
>>> search_spider = GSearch('study from home')
>>> print(search_spider.to_json())
...
...
...
Json Formatting
>>> search_spider.get_all()
...
...
...
Dictionary
```

## Resources

*   https://www.naufalardhani.com/2021/05/senginta-all-in-one-search-engine.html
*   Let's contribute your blog about this module here!

## License

[MIT License](LICENSE)

## WARNING

All intended of use, the responsibility rests with you. So, use wisely!


## Usage
See the below use cases of this awsome library

# GoogleSearch = GSearch('Tokopedia', 1, 3)
# print(GoogleSearch.to_json())

# GoogleBooks = GBooks('Python Programming', 1, 3)
# print(GoogleBooks.to_json())

# GoogleNews = GNews('Idcloudhost', 1, 3) 
# print(GoogleNews.to_json())

# GoogleShops = GShop('Remote TV', 'Rp', 1, 3)
# print(GoogleShops.to_json())

# GoogleVideo = GVideo('Pegipegi', 1, 3)
# print(GoogleVideo.to_json())

# BaiduSearch = BASearch('Gojek', 1, 3)
# print(BaiduSearch.to_json())


###################################################################################
# If when you use Google Scrapper is not give anything, you must try
# manual search with format https://scholar.google.com/scholar?q=KEYWORD&start=0
# and pass the bot manually.
# Usually you got the additional parameter, paste that additional parameter 
# into below.
#GScholar.URL += "ANOTHER_PARAMETER_TO_PASS_BOT_PROTECTOR"
###################################################################################

# GoogleScholar = GScholar('Penggunaan Naive Bayes Classifier', 1, 3)
# print(GoogleScholar.to_json())
