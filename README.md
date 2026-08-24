# 🎵 Billboard to Spotify Time Capsule

An automated Python script that scrapes the **Billboard Hot 100** chart for any historical date and creates a private **Spotify Playlist** featuring those exact top songs.

---

## 🛠️ Features

* **Web Scraping:** Uses `BeautifulSoup4` and `requests` to parse song titles directly from Billboard's chart pages.
* **Spotify Integration:** Connects to the Spotify Web API using `Spotipy` and `OAuth2`.
* **Automatic Search & Playlist Generation:** Finds the track URIs on Spotify for the specific release year and compiles them into a brand-new private playlist on your account.

---

## 📋 Prerequisites

* **Python 3.x** installed on your system.
* A **Spotify Account** (Premium).
* A **Spotify Developer App** to obtain your Client ID and Client Secret.

