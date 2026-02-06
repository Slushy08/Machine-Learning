# API Query Building Assignment
---

## USGS Earthquake Queries

### Query 1: [Describe what you're searching for]
**URL:**
```
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&minmagnitude=6.&orderby=magnitude&limit=15&endtime=2026-2-5
```

**Parameters used:**
- `format`: [explanation]
- `magnitude limit`: [limit of 15]
- `endtime`: [recent as of yesterdays date]

**Result:** found about 8 high level earthquakes

---

### Query 2: [Describe what you're searching for]
**URL:**
```
https://openlibrary.org/search.json?author=tatsuki+fujimoto&limit=15&title=fire+punch
```

**Parameters used:**
- `format`: [explanation]
- `athur`: [search by famous author tatsuki fujimoto]
- `title`: [a niche but good series fire punch]

**Result:** found 8 volumes

---

### Query 3: [Describe what you're searching for]
**URL:**
```
https://openlibrary.org/search.json?author=takeru+hokazono&limit=5&title=kagurabachi&language=eng
```

**Parameters used:**
- `format`: [explanation]
- `author`: [search by recent popular author takeru hokazono]
- `title`: [a book title by the name of kagurabachi]

**Result:** found 2 volumes

---

## Open Library Queries

### Query 4: [Describe what you're searching for]
**URL:**
```
https://openlibrary.org/search.json?author=akira+toriyama&limit=200
```

**Parameters used:**
- `author`: [search by famous author akira toriyama]
- `limit`: [limits the books to 200]

**Result:** found QUITE alot, most notable being dragon ball


### Query 5: [Describe what you're searching for]
**URL:**
```
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=2024-01-01&endtime=2026-01-01&limit=4
```

**Parameters used:**
- `starttime`: [start at 2024]
- `endtime`: [end at 2026]

**Result:** all under 2.0 magnitude
### Query 6: [Describe what you're searching for]
**URL:**
```
https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&minmagnitude=4.0&maxmagnitude=6.0&orderby=magnitude&limit=10
```

**Parameters used:**
- `minmagnitude`: [min of 4]
- `maxmagnitude`: [max magnitude of 10]

**Result:** alot of which is over 5