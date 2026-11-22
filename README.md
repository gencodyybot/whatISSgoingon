# whatISSgoingon?

A real-time International Space Station (ISS) orbital companion designed to combat astronaut isolation and nostalgia during long-duration spaceflight. By tracking the ISS in real time and streaming live local radio, weather, imagery, and cultural snapshots from the region directly below, **whatISSgoingon?** keeps crews connected to Earth.

> Inspired by the [Canadian Space Agency's Astronaut Mental Health & Isolation Toolkit](https://www.asc-csa.gc.ca/eng/youth-educators/toolkits/mental-health-and-isolation/how-astronauts-take-care-of-their-mental-health-in-space.asp).

---

## Features

* **Live ISS Telemetry:** Tracks real-time latitude, longitude, and timezone overhead.
* **Ground Radio & Seamless Failover:** Streams live local radio stations from the country below, automatically switching to ambient/lounge audio when flying over oceans or experiencing signal drops.
* **Real-Time Ground Weather:** Displays live temperature, wind speed, and weather conditions.
* **Country & Cultural Context:** Surfaces country facts, flags, capitals, languages, local imagery, and adaptive UI color theming based on the region below.

---

## Tech Stack & APIs

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS, JavaScript
* **APIs & Libraries:**
  * [Where The ISS At](https://wheretheiss.at/) - Live ISS coordinates & timezone
  * [Radio Browser API](https://www.radio-browser.info/) - Live local radio streams
  * [Open-Meteo API](https://open-meteo.com/) - Live ground weather data
  * [REST Countries API](https://restcountries.com/) - Country facts, flags, capitals & languages
  * [Wikipedia REST API](https://www.mediawiki.org/wiki/API:REST_API) / Unsplash - Regional photos & descriptions

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/gencodyybot/mecprogramming.git
