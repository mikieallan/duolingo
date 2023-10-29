### Duolingo API

I found that the Duolingo API has a bunch of additional explanation, that is not available on the web nor the app. So, this notebook helps pull it.

To use, fork repo and create a `env.py` file. In there, initialize the following four variables:
- MY_USERNAME
- MY_JWT
- MY_LANG_SHORT
- MY_LANG_LONG

This uses the [Unofficial Duoilngo API github repo](https://github.com/KartikTalwar/Duolingo/blob/master/duolingo.py)

Install dependencies:
- $ pip install duolingo-api
- $ pip install ipython
- $ pip install requests

Go through the notebook and see the HTML text of explanation come up! I copied into Notion to make easier to collapse and quickly review. 