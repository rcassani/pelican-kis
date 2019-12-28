# pelican-kis
Port to Pelican of the [Keep It Simple](https://www.styleshout.com/free-templates/keep-it-simple/) website template developed [StyleShout](https://www.styleshout.com/).

This theme is ready to support:
* [Disqus](https://disqus.com/) comments, [tipue_search](https://tipue.com/search/) ([Pelican plugin required](https://github.com/getpelican/pelican-plugins/tree/master/tipue_search)), [Google analytics](https://analytics.google.com/analytics/web/),  and [Pygments](https://pygments.org/).

A live demo can be found in: [www.castoriscausa.com](www.castoriscausa.com)

Screenshots:
![index](https://user-images.githubusercontent.com/8238803/71545235-d83ca200-2956-11ea-86c5-cb8b115f036a.png)

![category](https://user-images.githubusercontent.com/8238803/71545237-dd015600-2956-11ea-9368-369ec4598758.png)

![article](https://user-images.githubusercontent.com/8238803/71545240-decb1980-2956-11ea-8fbb-f4f92f96b3df.png)


Some of the configurations include:
```python
# Subtitle string
SITESUBTITLE = u'Catchy phrase'

# CC Licensing from: https://github.com/hlapp/cc-tools
CC_LICENSE = "CC-BY-NC-SA"

# Show metadata in Article and Index(es)
SHOW_ARTICLE_TAGS = True
SHOW_ARTICLE_AUTHOR = True
SHOW_ARTICLE_CATEGORY = True
SHOW_ARTICLE_DATEMODIFIED = True

# Show elements in Menu bar
SHOW_PAGES_ON_MENU = True
SHOW_CATEGORIES_ON_MENU = True

# Show elements in Side bar
SHOW_SEARCH_ON_SIDEBAR = True
SHOW_CATEGORIES_ON_SIDEBAR = True
SHOW_TEXT_ON_SIDEBAR = True
SIDEBAR_TITLE_TEXT = u'Hello'
SIDEBAR_TEXT = u'A brief text that will appear in de siderbar, this can be anything'
SHOW_TAGS_ON_SIDEBAR = True

# Custum CSS
CUSTOM_CSS = 'custom.css'
```
*Note:* Consider a Custum CSS to fine tune the aesthetics
