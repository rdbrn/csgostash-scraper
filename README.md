
# csgostash-scraper
Scrapes skin data from [CSGOStash](https://csgostash.com/) and saves it in JSON format.

Current Release: [v0.4.1](https://github.com/supr3meofficial/csgostash-scraper/releases/tag/v0.4.1)

What data does it scrape?
--
Cases, Collections and Souvenir Packages and their respective items. \
More to be added.

How does it work?
--
Data is scraped from CSGOStash and is saved onto JSON files and pickle objects. 

Where can I use it?
--
You can use the provided pickles in a Python project by importing the [csgostash_scraper folder](https://github.com/supr3meofficial/csgostash-scraper/tree/master/csgostash_scraper), or you may also use the JSON data for whatever project you would like.

Installation
--
1. **Install Python 3**

This is required to run the scraper.

2. **Set up venv**

Just do `python3 -m venv venv`

3. **Install dependencies**

This is `pip install -U -r requirements.txt`

4. **Run the script**

Use the following syntax `python3 main.py`


What it looks like
--
**Terminal:**
```sh
$ python3 main.py
Retrieving: MAC-10 | Copper Borre
Retrieving: XM1014 | Frost Borre
Retrieving: CZ75-Auto | Emerald Quartz
Retrieving: SCAR-20 | Brass
..
```
**JSON File:**
```json
{
  "name": "CS:GO Weapon Case",
  "image_url": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsRVx4MwFo5_T3eAQ3i6DMIW0X7ojiwoHax6egMOKGxj4G68Nz3-jCp4itjFWx-ktqfSmtcwqVx6sT/256fx256f",
  "content": {
    "Rare Special Items": [
      {
        "name": "★ Gut Knife | Case Hardened",
        "desc": "It has been color case-hardened through the application of wood charcoal at high temperatures.",
        "lore": "A little color never hurt anyone",
        "date_added": "14 August 2013",
        "can_be_souvenir": false,
        "can_be_stattrak": true,
        "wears": {
          "Factory New": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXH5ApeO4YmlhxYQknCRvCo04DEVlxkKgpovbSsLQJf1ObcTjxT09O_mIWPqPv9NLPFqWdQ-sJ0xO-Qod2i2wOy_EdpYW_7LIDBclI6aVHV-Fm_lOe-gJG5vpvKyHYwv3M8pSGKIGsDSZw/512fx384f",
          "Minimal Wear": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXH5ApeO4YmlhxYQknCRvCo04DEVlxkKgpovbSsLQJf1ObcTjxT09O_mIWPqPv9NLPFqWdQ-sJ0xO-Qod2i2wOy_EdpYW_7LIDBclI6aVHV-Fm_lOe-gJG5vpvKyHYwv3M8pSGKIGsDSZw/512fx384f",
          "Field-Tested": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXH5ApeO4YmlhxYQknCRvCo04DEVlxkKgpovbSsLQJf1ObcTjxT09O_mIWPqPrxN7LEm1Rd6dd2j6eUrdzw0Vfg-EY9N236IoSRIFU_YV_RqFi2kOjsg5e1u5XAmnAxsiR3-z-DyDOYcv8_/512fx384f",
          "Well-Worn": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXH5ApeO4YmlhxYQknCRvCo04DEVlxkKgpovbSsLQJf1ObcTjxT09O_mIWPqPrxN7LEm1Rd6dd2j6eUrdzw0Vfg-EY9N236IoSRIFU_YV_RqFi2kOjsg5e1u5XAmnAxsiR3-z-DyDOYcv8_/512fx384f",
          "Battle-Scarred": "https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXH5ApeO4YmlhxYQknCRvCo04DEVlxkKgpovbSsLQJf1ObcTjxT09O_mIWPqP_xMq3IqWdQ-sJ0xLuYrN2s2lXhrUpkMW_zI4WVd1Q8MlzYr1C5l-nqhZC1vZTJzSZj7nQ8pSGKnPOWYls/512fx384f"
        },
        "prices": {
          "StatTrak Factory New": {
            "steam_price": "$541.84",
            "steam_listings": "1",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": ""
          },
          "StatTrak Minimal Wear": {
            "steam_price": "$348.04",
            "steam_listings": "2",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": ""
          },
          "StatTrak Field-Tested": {
            "steam_price": "$271.00",
            "steam_listings": "4",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": ""
          },
          "StatTrak Well-Worn": {
            "steam_price": "$215.98",
            "steam_listings": "4",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": ""
          },
          "StatTrak Battle-Scarred": {
            "steam_price": "$205.81",
            "steam_listings": "3",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": ""
          },
          "Factory New": {
            "steam_price": "$411.41",
            "steam_listings": "2",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": ""
          },
          "Minimal Wear": {
            "steam_price": "$221.98",
            "steam_listings": "17",
            "steam_median_price": "$172.27",
            "steam_volume": "1",
            "bitskins_price": "$195.00"
          },
          "Field-Tested": {
            "steam_price": "$214.73",
            "steam_listings": "12",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": "$182.69"
          },
          "Well-Worn": {
            "steam_price": "$177.75",
            "steam_listings": "5",
            "steam_median_price": "$150.00",
            "steam_volume": "1",
            "bitskins_price": ""
          },
          "Battle-Scarred": {
            "steam_price": "$173.33",
            "steam_listings": "13",
            "steam_median_price": "",
            "steam_volume": "",
            "bitskins_price": "$170.00"
          }
        }
      }
...
```

License
--
Released under the [MIT](LICENSE) license.
