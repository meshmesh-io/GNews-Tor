# GNews-Tor

GNews-Tor is a lightweight Python package providing an API to search for articles on Google News. This version is tailored for use with Tor, enhancing privacy and efficiency in collecting articles as IP bans are circumvented. It's a Tor-compatible version of [GNews](https://github.com/ranahaani/GNews).

## Forked From

This project is a fork from [GNews](https://github.com/ranahaani/GNews).

## Installation

1. Install Tor:
    - [Follow these instructions to install Tor.](https://2019.www.torproject.org/docs/documentation.html.en#Documentation)
    
2. Install GNews-Tor:
    ```bash
    pip install git+https://github.com/themetalleg/GNews-Tor.git
    ```

## Usage

```python
from GNews import GNews

google_news = GNews()
google_news.proxy = 'socks5h://localhost:9050'

# Now you can use the GNews API to search for articles
articles = google_news.get_articles('Python programming')
```

For more information visit the original project [GNews](https://github.com/ranahaani/GNews).
