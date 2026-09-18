# Kworb Navigation Diagram

Full site navigation flow — from the **Landing Page** entry point through **Home**, then out to every section and sub-page.

---

## Site Flow

```mermaid
flowchart TD
    LANDING["index.html\nLanding Page"]

    LANDING --> WELCOME["welcome.html\nWelcome"]
    LANDING --> STATS["stats.html\nVisitor Stats"]
    LANDING --> FAQ["faq.html\nFAQ"]
    LANDING --> PRIVACY["privacy.html\nPrivacy"]
    LANDING --> HOME["home.html\nHome"]

    HOME --> DISCOVER["── DISCOVER ──"]
    HOME --> PLATFORMS["── PLATFORMS ──"]
    HOME --> ARTISTS_G["── ARTISTS ──"]

    DISCOVER --> CHARTS["charts.html\nCharts"]
    DISCOVER --> WORLDWIDE["worldwide.html\nWorldwide"]
    DISCOVER --> TRENDING["trending.html\nTrending"]
    DISCOVER --> RADIO["radio.html\nRadio"]

    PLATFORMS --> SPOTIFY["spotify.html\nSpotify"]
    PLATFORMS --> ITUNES["itunes.html\niTunes / Apple Music"]
    PLATFORMS --> YOUTUBE["youtube.html\nYouTube"]

    ARTISTS_G --> ARTISTS["artists.html\nArtist List"]
    ARTISTS_G --> MORE["more.html\nMore Artists"]
```

---

## Landing Page — Section Map

The landing page is structured into four named content sections, plus the top nav bar.

```mermaid
flowchart TD
    LP["Landing Page\nindex.html"]

    LP --> TOPNAV["Top Nav Bar"]
    LP --> S1["WHAT'S ACTUALLY ON HERE"]
    LP --> S2["WHERE THE NUMBERS COME FROM"]
    LP --> S3["COUNTRIES, RADIO, OLD WEEKS"]
    LP --> S4["A FEW THINGS TO KNOW"]
    LP --> CTA["CTA → Home"]

    TOPNAV --> W["Welcome"]
    TOPNAV --> VS["Visitor Stats"]
    TOPNAV --> F["FAQ"]
    TOPNAV --> P["Privacy"]
    TOPNAV --> H["Home"]

    S1 --> C1["Charts"]
    S1 --> C2["Artist List"]
    S1 --> C3["Spotify"]

    S2 --> P1["Spotify"]
    S2 --> P2["Apple Music"]
    S2 --> P3["iTunes"]
    S2 --> P4["YouTube"]
    S2 --> P5["Shazam"]
    S2 --> P6["Deezer"]

    S3 --> R1["Worldwide\n(iTunes WW)"]
    S3 --> R2["Radio"]
    S3 --> R3["Archives\n(Home)"]

    S4 --> N1["No login"]
    S4 --> N2["Tables, not graphs"]
    S4 --> N3["It stays up."]
```

---

## Full Page Inventory

### Landing (`/`)
| File | Page |
|---|---|
| `index.html` | Landing Page |

### Site Info (`/pages/site/`)
| File | Page |
|---|---|
| `welcome.html` | Welcome |
| `stats.html` | Visitor Stats |
| `faq.html` | FAQ |
| `privacy.html` | Privacy |

### Home (`/pages/`)
| File | Page |
|---|---|
| `home.html` | Home / Dashboard |

### Discover (`/pages/discover/`)
| File | Page |
|---|---|
| `charts.html` | Charts |
| `worldwide.html` | Worldwide (iTunes WW) |
| `trending.html` | Trending |
| `radio.html` | Radio |
| `albums.html` | Albums |
| `apple-songs.html` | Apple Music Songs |
| `apple-albums.html` | Apple Music Albums |
| `apple-eu-songs.html` | Apple Music EU Songs |
| `apple-eu-albums.html` | Apple Music EU Albums |
| `itunes-albums.html` | iTunes Albums |
| `itunes-eu-songs.html` | iTunes EU Songs |
| `itunes-eu-albums.html` | iTunes EU Albums |

### Platforms (`/pages/platforms/`)
| File | Page |
|---|---|
| `spotify.html` | Spotify |
| `itunes.html` | iTunes / Apple Music |
| `youtube.html` | YouTube |
| `youtube-artists.html` | YouTube Artists |
| `youtube-countries.html` | YouTube Countries |
| `youtube-toplists.html` | YouTube Top Lists |
| `itunes-uk.html` | iTunes UK |
| `itunes-au.html` | iTunes AU |
| `itunes-ca.html` | iTunes CA |
| `itunes-de.html` | iTunes DE |
| `itunes-fr.html` | iTunes FR |
| `itunes-jp.html` | iTunes JP |
| `itunes-br.html` | iTunes BR |
| `itunes-mx.html` | iTunes MX |
| `itunes-es.html` | iTunes ES |
| `itunes-it.html` | iTunes IT |
| `itunes-nl.html` | iTunes NL |
| `itunes-be.html` | iTunes BE |
| `itunes-ch.html` | iTunes CH |
| `itunes-ie.html` | iTunes IE |
| `itunes-nz.html` | iTunes NZ |
| `itunes-ru.html` | iTunes RU |
| `itunes-tr.html` | iTunes TR |
| `itunes-za.html` | iTunes ZA |

### Artists (`/pages/artists/`)
| File | Page |
|---|---|
| `artists.html` | Artist List |
| `more.html` | More Artists |
