# Yelp dataset

## business units
- "city" : "Santa Barbara" 인 business 만 남기고 모두 삭제한다. 3829개가 남았다.
- "categories" : /Restaurants/ 만 남기고 모두 삭제한다. 766개 남았다.

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
AgesAllowed: ['allages', '21plus']
RestaurantsPriceRange2: ['2', '1', '4', 'None', '3']
Alcohol: ['beer_and_wine', 'none', 'full_bar']
WiFi: ['free', 'None', 'no', 'paid']
Smoking: ['no', 'outdoor', 'None']
NoiseLevel: ['quiet', 'very_loud', 'average', 'loud']
BYOBCorkage: ['yes_free', 'no', 'yes_corkage']
RestaurantsAttire: ['dressy', 'formal', 'casual']


Ambience: casual, upscale, divey, touristy, hipster, classy, trendy, intimate, romantic
GoodForMeal: dessert, dinner, lunch, latenight, breakfast, brunch
Music: background_music, karaoke, jukebox, live, dj, no_music, video
BestNights: sunday, monday, tuesday, wednesday, thursday, friday, saturday
BusinessParking: validated, garage, street, lot, valet


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


```