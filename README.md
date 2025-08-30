# Yelp dataset

## business units
- "city" : "Santa Barbara" 인 business 만 남기고 모두 삭제한다.
- "categories" : /Restaurants/ 만 남기고 모두 삭제한다.

## [hybrid query](https://qdrant.tech/documentation/concepts/hybrid-queries/)
- [BAAI/bge-m3](https://huggingface.co/BAAI/bge-m3)
    - Multi-Functionality(dense retrieval, sparse retrieval, multi-vector(colbert))
    - Multi-Linguality
    - Multi-Granularity(8192 tokens)


## conda install
- [FlagEmbedding](https://github.com/FlagOpen/FlagEmbedding)
```
conda install pytorch::pytorch
conda install conda-forge::flagembedding
```




```
Alcohol: ['beer_and_wine', 'none', 'full_bar']
NoiseLevel: ['quiet', 'very_loud', 'average', 'loud']
RestaurantsAttire: ['dressy', 'formal', 'casual']


WiFi: ['True', 'False']
Smoking:  ['True', 'False']
BYOBCorkage:  ['True', 'False']
DogsAllowed: ['True', 'False']
WheelchairAccessible: ['False', 'True']
HasTV: ['True', 'False']
HappyHour: ['False', 'True']
BYOB: ['True', 'False']
BikeParking: ['True', 'False']
AcceptsInsurance: ['False']
GoodForKids: ['True', 'False']
BusinessAcceptsBitcoin: ['False', 'True']
Caters: ['False', 'True']
CoatCheck: ['True', 'False']
BusinessAcceptsCreditCards: ['True', 'False']
GoodForDancing: ['True', 'False']
Corkage: ['True', 'False']
RestaurantsTableService: ['True', 'False']
ByAppointmentOnly: ['True', 'False']


RestaurantsReservations: ['True', 'False']
DriveThru: ['False', 'True']
RestaurantsDelivery: ['False', 'True']
OutdoorSeating: ['True', 'False']
RestaurantsGoodForGroups: ['False', 'True']
RestaurantsTakeOut: ['True', 'False']

Ambience: casual, upscale, divey, touristy, hipster, classy, trendy, intimate, romantic
GoodForMeal: dessert, dinner, lunch, latenight, breakfast, brunch
Music: background_music, karaoke, jukebox, live, dj, no_music, video
BestNights: sunday, monday, tuesday, wednesday, thursday, friday, saturday
BusinessParking: validated, garage, street, lot, valet
```
