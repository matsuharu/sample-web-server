# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```
curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
[
  {
    "breeds": [],
    "id": "2nc",
    "url": "https://cdn2.thecatapi.com/images/2nc.jpg",
    "width": 500,
    "height": 333
  },
  {
    "breeds": [],
    "id": "c3q",
    "url": "https://cdn2.thecatapi.com/images/c3q.jpg",
    "width": 500,
    "height": 332
  },
  {
    "breeds": [
      {
        "weight": {
          "imperial": "6 - 10",
          "metric": "3 - 5"
        },
        "id": "hbro",
        "name": "Havana Brown",
        "cfa_url": "http://cfa.org/Breeds/BreedsCJ/HavanaBrown.aspx",
        "vetstreet_url": "http://www.vetstreet.com/cats/havana-brown",
        "vcahospitals_url": "https://vcahospitals.com/know-your-pet/cat-breeds/havana-brown",
        "temperament": "Affectionate, Curious, Demanding, Friendly, Intelligent, Playful",
        "origin": "United Kingdom",
        "country_codes": "GB",
        "country_code": "GB",
        "description": "The Havana Brown is human oriented, playful, and curious. She has a strong desire to spend time with her people and involve herself in everything they do. Being naturally inquisitive, the Havana Brown reaches out with a paw to touch and feel when investigating curiosities in its environment. They are truly sensitive by nature and frequently gently touch their human companions as if they are extending a paw of friendship.",
        "life_span": "10 - 15",
        "indoor": 0,
        "lap": 1,
        "alt_names": "Havana, HB",
        "adaptability": 5,
        "affection_level": 5,
        "child_friendly": 4,
        "dog_friendly": 5,
        "energy_level": 3,
        "grooming": 1,
        "health_issues": 1,
        "intelligence": 5,
        "shedding_level": 3,
        "social_needs": 5,
        "stranger_friendly": 3,
        "vocalisation": 1,
        "experimental": 0,
        "hairless": 0,
        "natural": 0,
        "rare": 0,
        "rex": 0,
        "suppressed_tail": 0,
        "short_legs": 0,
        "wikipedia_url": "https://en.wikipedia.org/wiki/Havana_Brown",
        "hypoallergenic": 0
      }
    ],
    "id": "bGUQ04k2E",
    "url": "https://cdn2.thecatapi.com/images/bGUQ04k2E.jpg",
    "width": 2592,
    "height": 1936
  }
]

```
