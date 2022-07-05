
# Draw From Text API

**Draw From Text (DFT)** is a free service to generate images from the description text you set .

# How to use Draw From Text API?

| Query | Definition |
|--|--|
| text | name or description of the image you want to draw|

GET https://api.pawan.krd/drawfromtext?text=door

**Response**
You will get json response like this:

    {
      "state": true,
      "text": "door",
      "images": [
        "https://api.pawan.krd/dftimage?id=68c7992e",
        "https://api.pawan.krd/dftimage?id=9211dc0c",
        "https://api.pawan.krd/dftimage?id=90dc1690",
        "https://api.pawan.krd/dftimage?id=36b9b959",
        "https://api.pawan.krd/dftimage?id=0e5920d1",
        "https://api.pawan.krd/dftimage?id=144a2bbb",
        "https://api.pawan.krd/dftimage?id=0cb9124b",
        "https://api.pawan.krd/dftimage?id=b72a9bc1",
        "https://api.pawan.krd/dftimage?id=fb96b4e1"
      ]
    }


#### * It may need 3-5 minutes to generate 9 images
#### * We're using external services
