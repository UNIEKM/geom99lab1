# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?avoid=highways&destination=place_id:ChIJUzqZj0oNhlQRSzlBeYd5v-0&mode=bicycling&origin=place_id:ChIJSxASt5l1hlQRJ8Ti_bDBmpE&waypoints=place_id:ChIJwW3HeIZzhlQRVxJgWI8VjAg|place_id:ChIJb2gVVzZzhlQRW6FKTfIcqMY&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE

```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJSxASt5l1hlQRJ8Ti_bDBmpE",
         "types" : [ "street_address" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJwW3HeIZzhlQRVxJgWI8VjAg",
         "types" : [ "establishment", "park", "point_of_interest", "tourist_attraction" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJb2gVVzZzhlQRW6FKTfIcqMY",
         "types" : [ "establishment", "point_of_interest" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJUzqZj0oNhlQRSzlBeYd5v-0",
         "types" : [ "establishment", "natural_feature" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 49.2634327,
               "lng" : -123.1188458
            },
            "southwest" : {
               "lat" : 49.2210315,
               "lng" : -123.2614876
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "2.6 km",
                  "value" : 2556
               },
               "duration" : {
                  "text" : "11 mins",
                  "value" : 682
               },
               "end_address" : "VanDusen Botanical Garden, 5251 Oak St, Vancouver, BC V6M 4H1, Canada",
               "end_location" : {
                  "lat" : 49.2379515,
                  "lng" : -123.1287762
               },
               "start_address" : "7059 Ash Cres, Vancouver, BC V6P 3K6, Canada",
               "start_location" : {
                  "lat" : 49.2210315,
                  "lng" : -123.1189343
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "87 m",
                        "value" : 87
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 22
                     },
                     "end_location" : {
                        "lat" : 49.22180909999999,
                        "lng" : -123.1188458
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e on \u003cb\u003eAsh Cres\u003c/b\u003e toward \u003cb\u003eW 54th Ave\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003ePartial restricted usage road\u003c/div\u003e",
                     "polyline" : {
                        "points" : "mnlkHhtmnV_@GOCM?SAiAA"
                     },
                     "start_location" : {
                        "lat" : 49.2210315,
                        "lng" : -123.1189343
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 130
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 26
                     },
                     "end_location" : {
                        "lat" : 49.22176690000001,
                        "lng" : -123.1206277
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eW 54th Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "islkHxsmnV?N?`C?hA@b@@f@@Z@^"
                     },
                     "start_location" : {
                        "lat" : 49.22180909999999,
                        "lng" : -123.1188458
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.5 km",
                        "value" : 505
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 156
                     },
                     "end_location" : {
                        "lat" : 49.2262943,
                        "lng" : -123.1208571
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTisdall St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "aslkH|~mnVUAS?S@Q@K?C@SBQBk@Li@J[FOBK@I@IBS@i@BwDGwAAyAAuAAaBC"
                     },
                     "start_location" : {
                        "lat" : 49.22176690000001,
                        "lng" : -123.1206277
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "67 m",
                        "value" : 67
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 47
                     },
                     "end_location" : {
                        "lat" : 49.2263264,
                        "lng" : -123.1217734
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eW 49th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHeather Bikeway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "iomkHj`nnVCdACnB"
                     },
                     "start_location" : {
                        "lat" : 49.2262943,
                        "lng" : -123.1208571
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 308
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 58
                     },
                     "end_location" : {
                        "lat" : 49.22909689999999,
                        "lng" : -123.1216773
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHeather Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eTisdall St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qomkH`fnnVyBCeACw@?s@AA?iDEo@AY?G?"
                     },
                     "start_location" : {
                        "lat" : 49.2263264,
                        "lng" : -123.1217734
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 126
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 23
                     },
                     "end_location" : {
                        "lat" : 49.2291537,
                        "lng" : -123.1234161
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eW 46th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eHeather Bikeway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "{`nkHnennVCfC?NAl@CtC"
                     },
                     "start_location" : {
                        "lat" : 49.22909689999999,
                        "lng" : -123.1216773
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 578
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 161
                     },
                     "end_location" : {
                        "lat" : 49.2342991,
                        "lng" : -123.1238481
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eHeather Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eWillow St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "eankHjpnnVq@Ca@Aa@AY?c@AQAc@Ac@AO@M?M@MBMBIDa@Ni@Rk@TSHUFIBI@UDS@_@@m@@{A?uAAwACUAwAA"
                     },
                     "start_location" : {
                        "lat" : 49.2291537,
                        "lng" : -123.1234161
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 406
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 70
                     },
                     "end_location" : {
                        "lat" : 49.2375421,
                        "lng" : -123.1244281
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "kaokH`snnVCdBAR?FEFE@cBCo@AS?{BCgACc@Ao@A_BCuAA"
                     },
                     "start_location" : {
                        "lat" : 49.2342991,
                        "lng" : -123.1238481
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.3 km",
                        "value" : 319
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 115
                     },
                     "end_location" : {
                        "lat" : 49.237685,
                        "lng" : -123.1288108
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRidgeway Bikeway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "suokHtvnnVAr@CrBGrFCpCGxCAlC?T"
                     },
                     "start_location" : {
                        "lat" : 49.2375421,
                        "lng" : -123.1244281
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "30 m",
                        "value" : 30
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 4
                     },
                     "end_location" : {
                        "lat" : 49.2379515,
                        "lng" : -123.1287762
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ovokH`ronVa@AI?IC"
                     },
                     "start_location" : {
                        "lat" : 49.237685,
                        "lng" : -123.1288108
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "6.7 km",
                  "value" : 6715
               },
               "duration" : {
                  "text" : "24 mins",
                  "value" : 1439
               },
               "end_address" : "4300 SW Marine Dr, Vancouver, BC V6N 4A6, Canada",
               "end_location" : {
                  "lat" : 49.2329192,
                  "lng" : -123.2092684
               },
               "start_address" : "VanDusen Botanical Garden, 5251 Oak St, Vancouver, BC V6M 4H1, Canada",
               "start_location" : {
                  "lat" : 49.2379515,
                  "lng" : -123.1287762
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 212
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 49.23774539999999,
                        "lng" : -123.1304083
                     },
                     "html_instructions" : "Head \u003cb\u003enorth\u003c/b\u003e toward \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRidgeway Bikeway\u003c/b\u003e",
                     "polyline" : {
                        "points" : "exokHzqonVCAKAEAGBEDEHAFA@ALAP?XCvA?BAp@?@?b@?JAb@Ab@@B@B@?DDL?F?BA@A@ABGBOBEBAD?@?`@B"
                     },
                     "start_location" : {
                        "lat" : 49.2379515,
                        "lng" : -123.1287762
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 1000
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 253
                     },
                     "end_location" : {
                        "lat" : 49.2381289,
                        "lng" : -123.1441644
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRidgeway Bikeway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "}vokH`|onVKfKExDIpG?TInFClBClBGzGAd@CzCA|@AlCCtEAP?nAClGAvC"
                     },
                     "start_location" : {
                        "lat" : 49.23774539999999,
                        "lng" : -123.1304083
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1133
                     },
                     "duration" : {
                        "text" : "4 mins",
                        "value" : 234
                     },
                     "end_location" : {
                        "lat" : 49.238368,
                        "lng" : -123.15969
                     },
                     "html_instructions" : "At the roundabout, continue straight to stay on \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eRidgeway Bikeway\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eContinue to follow W 37th Ave/\u003cwbr/\u003eMidtown Bikeway\u003c/div\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "iyokH~qrnV?@A?A??@A??@A??@?@A@?@?@?@?@?@?@?@@??@?@@??@@@@??@@?CdDCjH?~@AlJ?n@KvG?dAAv@?t@AlBAzDAnC?dDAv@?f@Ap@?^?^AbCCdDC`HCbG"
                     },
                     "start_location" : {
                        "lat" : 49.2381289,
                        "lng" : -123.1441644
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 442
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 115
                     },
                     "end_location" : {
                        "lat" : 49.2384739,
                        "lng" : -123.165657
                     },
                     "html_instructions" : "At the roundabout, continue straight to stay on \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "yzokH`sunVA?A?A@A??@A??@?@A??@?@?@?@A??@?@?@@??@?@?@?@@??@@@@@@??@@?@?AlB?vCAv@CfF?jBAjB?t@?BCnBEzE"
                     },
                     "start_location" : {
                        "lat" : 49.238368,
                        "lng" : -123.15969
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.9 km",
                        "value" : 949
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 198
                     },
                     "end_location" : {
                        "lat" : 49.2385883,
                        "lng" : -123.1786178
                     },
                     "html_instructions" : "At the roundabout, continue straight to stay on \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "m{okHjxvnVA?A?A??@A??@A@?@A@?@?@?@?@?@?@?@?@?@@??@?@@??@@??@@??@@?@?Ch@ApD?t@Av@?rBAxE@t@?pB?r@?t@AdD?v@?tGAfD?~E?v@?bB?PAfC?t@AxE?VAbAEp@"
                     },
                     "start_location" : {
                        "lat" : 49.2384739,
                        "lng" : -123.165657
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 248
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 54
                     },
                     "end_location" : {
                        "lat" : 49.2385493,
                        "lng" : -123.1819888
                     },
                     "html_instructions" : "At the roundabout, continue straight to stay on \u003cb\u003eW 37th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "e|okHjiynVA??@A@?@?@A??@?@?@?@?@?@?@?@?@?@@@?@@@Fv@?zG@jH"
                     },
                     "start_location" : {
                        "lat" : 49.2385883,
                        "lng" : -123.1786178
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 235
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 28
                     },
                     "end_location" : {
                        "lat" : 49.23643879999999,
                        "lng" : -123.1820258
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCollingwood St\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "}{okHl~ynVhABnA@vA@n@?b@AH@F@t@AV?"
                     },
                     "start_location" : {
                        "lat" : 49.2385493,
                        "lng" : -123.1819888
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.1 km",
                        "value" : 1076
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 186
                     },
                     "end_location" : {
                        "lat" : 49.23649529999999,
                        "lng" : -123.1968477
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW 39th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eMidtown Bikeway\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wnokHt~ynV?lB?lB?bD?v@?t@?`D?rC?zC?fDApA?b@?bD?hB?n@?|E?lB?t@?hBCdDApB?jACfP"
                     },
                     "start_location" : {
                        "lat" : 49.23643879999999,
                        "lng" : -123.1820258
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 163
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 49.2350618,
                        "lng" : -123.1970691
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eCamosun St\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "cookHh{|nVxAClAAJ?J?RDLBFDVLDBVN"
                     },
                     "start_location" : {
                        "lat" : 49.23649529999999,
                        "lng" : -123.1968477
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 654
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 162
                     },
                     "end_location" : {
                        "lat" : 49.2373348,
                        "lng" : -123.2053716
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eSW Marine Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cfokHt||nVYlAYxAQ~@Q`AMt@Mn@_@zBw@jEk@bDI^?D{@xEi@zCSfAY~Ag@|CCHCR"
                     },
                     "start_location" : {
                        "lat" : 49.2350618,
                        "lng" : -123.1970691
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 603
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 148
                     },
                     "end_location" : {
                        "lat" : 49.2329192,
                        "lng" : -123.2092684
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eKullahun Dr\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "itokHpp~nVTX`@t@fAjBdBzC~CpFDFDDFFFHHFJHBBFBJD|A`@`@PHDRJXPDDJFRNPN@?RNJFFDVFB@\\FH?F?FAFCHEJIFG?ADEFM"
                     },
                     "start_location" : {
                        "lat" : 49.2373348,
                        "lng" : -123.2053716
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "7.0 km",
                  "value" : 6977
               },
               "duration" : {
                  "text" : "30 mins",
                  "value" : 1819
               },
               "end_address" : "Wreck Beach, SW Marine Dr, Vancouver, BC V6T 1Z4, Canada",
               "end_location" : {
                  "lat" : 49.2621998,
                  "lng" : -123.2614741
               },
               "start_address" : "4300 SW Marine Dr, Vancouver, BC V6N 4A6, Canada",
               "start_location" : {
                  "lat" : 49.2329192,
                  "lng" : -123.2092684
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 424
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 74
                     },
                     "end_location" : {
                        "lat" : 49.2361825,
                        "lng" : -123.207087
                     },
                     "html_instructions" : "Head \u003cb\u003enorthwest\u003c/b\u003e on \u003cb\u003eKullahun Dr\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wxnkH|h_oVGLED?@GFKHIDGBG@G?I?]GCAWGGEKGSOA?QOSOKGEEYQSKIEa@Q}Aa@KEGCCCKIIGGIGGEEEG_DqF"
                     },
                     "start_location" : {
                        "lat" : 49.2329192,
                        "lng" : -123.2092684
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 195
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 41
                     },
                     "end_location" : {
                        "lat" : 49.2372936,
                        "lng" : -123.2052194
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eKullahun Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cmokHh{~nVBKDI?C@EAGAEIOCIEGEIc@u@}@_Be@}@k@o@WW"
                     },
                     "start_location" : {
                        "lat" : 49.2361825,
                        "lng" : -123.207087
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "2.4 km",
                        "value" : 2396
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 460
                     },
                     "end_location" : {
                        "lat" : 49.24572329999999,
                        "lng" : -123.2349232
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eSW Marine Dr\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "atokHro~nVCHCRg@lCQ`Aq@`Ek@~CKp@EPCN[xB?@Mv@M`AADK~@M|@K~@Gp@ALIv@Gr@ANALIhAM~AG~@?JIfAEx@OzBANO`CEx@Ep@ADIrAI|ACT?LC\\GfAG|@IjAMrBYvEEh@M~AOdBGn@Gn@OzASbBQlAc@zCSpAUrAc@tBUdAI`@Kd@KX[vAAFUz@[jAERGPK^IZ_@nAu@`Ca@dAe@lAiAnCeAdC]t@gA|BOXA@o@vAKT}@rB[r@q@|A_@z@Ud@mBdEGP"
                     },
                     "start_location" : {
                        "lat" : 49.2372936,
                        "lng" : -123.2052194
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "72 m",
                        "value" : 72
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 15
                     },
                     "end_location" : {
                        "lat" : 49.2461767,
                        "lng" : -123.235562
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "whqkHfidoVK@GBC@CBIHINO\\O\\ENEL"
                     },
                     "start_location" : {
                        "lat" : 49.24572329999999,
                        "lng" : -123.2349232
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.3 km",
                        "value" : 1332
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 320
                     },
                     "end_location" : {
                        "lat" : 49.2537402,
                        "lng" : -123.241987
                     },
                     "html_instructions" : "Slight \u003cb\u003eright\u003c/b\u003e",
                     "maneuver" : "turn-slight-right",
                     "polyline" : {
                        "points" : "skqkHfmdoVKLINABMZWr@Un@?@Sl@O^EJe@tAWn@O^e@`Ai@jAu@zAe@bAGNw@|AGLq@vAq@tAm@rAm@nAa@z@c@z@CFQ^S`@[p@IP]t@]x@[p@[p@MTUf@[n@Sd@KRc@|@IPw@lAGJCDC@GFIDC?E?IAKCKEIIGKIQKSEMCKQm@IYCKCIOq@YqAg@qBKc@EOy@cDIYEMKOA?ECIEKIEECGCC?AAAA??@A@?@AB?@?@A@CB"
                     },
                     "start_location" : {
                        "lat" : 49.2461767,
                        "lng" : -123.235562
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "64 m",
                        "value" : 64
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 42
                     },
                     "end_location" : {
                        "lat" : 49.2539901,
                        "lng" : -123.2412243
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eW 16th Ave\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "{zrkHlueoVOYCEGMCICEAECIAMAM?MCa@"
                     },
                     "start_location" : {
                        "lat" : 49.2537402,
                        "lng" : -123.241987
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "1.0 km",
                        "value" : 965
                     },
                     "duration" : {
                        "text" : "3 mins",
                        "value" : 198
                     },
                     "end_location" : {
                        "lat" : 49.2613543,
                        "lng" : -123.2469745
                     },
                     "html_instructions" : "At the roundabout, take the \u003cb\u003e3rd\u003c/b\u003e exit onto \u003cb\u003eE Mall N\u003c/b\u003e",
                     "maneuver" : "roundabout-right",
                     "polyline" : {
                        "points" : "m|rkHrpeoV?C@E?C?C?A?E?EAC?EACAEACACACCCAAAAA?ECCACAC?A?C@C?C@A@C@ABC@ABABABADADADAB?F?DEFEHIHOLOLA@KFUJ[PSJUP_Ap@{@l@eCfB]XyC`Cy@n@oBzA_@ZMHcBpAaAr@_DxBOLQTEDGJMVYr@CBIFEBIFYTOJE@cAr@OH"
                     },
                     "start_location" : {
                        "lat" : 49.2539901,
                        "lng" : -123.2412243
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.4 km",
                        "value" : 382
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 49
                     },
                     "end_location" : {
                        "lat" : 49.2597232,
                        "lng" : -123.2515988
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAgronomy Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mjtkHptfoVhAxEbAtD@HDLDNNn@HVNt@J`@\\lAH\\BDH\\\\xA^zA"
                     },
                     "start_location" : {
                        "lat" : 49.2613543,
                        "lng" : -123.2469745
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 127
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 20
                     },
                     "end_location" : {
                        "lat" : 49.2606468,
                        "lng" : -123.2526138
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eWest Mall\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "g`tkHnqgoVGDCBQLWRA@KHIHCDCBEHIJm@z@MPKLKJ"
                     },
                     "start_location" : {
                        "lat" : 49.2597232,
                        "lng" : -123.2515988
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 217
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 31
                     },
                     "end_location" : {
                        "lat" : 49.2596916,
                        "lng" : -123.2552142
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eAgronomy Rd\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "aftkHxwgoVl@zBd@jB`BjGHR"
                     },
                     "start_location" : {
                        "lat" : 49.2606468,
                        "lng" : -123.2526138
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.6 km",
                        "value" : 555
                     },
                     "duration" : {
                        "text" : "2 mins",
                        "value" : 108
                     },
                     "end_location" : {
                        "lat" : 49.2634327,
                        "lng" : -123.2592465
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eNW Marine Dr\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a`tkH`hhoVMPO\\M\\M^Md@ENKj@G\\Qx@K`@EPGNENILGLGJIJIHKHGDYLOFUHMBGBMFGBC@MLORUd@IPINGNMPIJGFIHGDIBK@I@KAWEk@OYGIAO?QDUJKFKJMNGHABEFIRIRIRCH"
                     },
                     "start_location" : {
                        "lat" : 49.2596916,
                        "lng" : -123.2552142
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 241
                     },
                     "duration" : {
                        "text" : "8 mins",
                        "value" : 453
                     },
                     "end_location" : {
                        "lat" : 49.2622653,
                        "lng" : -123.2614892
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eTrail 6\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eTake the stairs\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "mwtkHhaioV^^?@FDFFFHDBDENODE@??ABCFFRJBVDZ?@@F?L@F?HDH?@@DDRFT?@BJDZD@?@?@@F@HDNBL?@DNBRBJ@@@D@NDJBJ?@?DFP@H@N"
                     },
                     "start_location" : {
                        "lat" : 49.2634327,
                        "lng" : -123.2592465
                     },
                     "travel_mode" : "BICYCLING"
                  },
                  {
                     "distance" : {
                        "text" : "7 m",
                        "value" : 7
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 8
                     },
                     "end_location" : {
                        "lat" : 49.2621998,
                        "lng" : -123.2614741
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eForeshore Trail\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eWalk your bicycle\u003c/div\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the right\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "eptkHhoioVLC"
                     },
                     "start_location" : {
                        "lat" : 49.2622653,
                        "lng" : -123.2614892
                     },
                     "travel_mode" : "BICYCLING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "mnlkHhtmnVo@Ka@AiAA?N?jEFfCoA@u@HaCd@s@Hi@BwDGqDCwDEGtDkHIuFGG?CfCA|@CtCq@CcACsBEs@?[@[Fk@T_Cz@}@LmABqDAmBEwAACdBAZKHcHI{FKuAAAr@KfJKjHAbDk@AMEQCMHK`@GjFCfABFFDT?JMFUHAb@BQ`QWdSQjQIrLGvNC@ADALDHB@GpMAlLKfIC`HEhPOh^E@CBCNDJDBEdPApGKjIA?A@CDANFJ@@@?EzEAlB?tNAfICh_@ApFAbAEp@A?AB?@AD?H@H@@Fv@?zG@jHhABfDBrAAPBlAA?vL?fOAf\\EvLCrRfDEV?`@H|@f@s@fDc@`CsBlLqFd[G\\v@nArI`O^^NLRH|A`@`@P\\P~@n@r@f@^L`@HP?NE\\YLSU\\UNODQ?a@I_@M_@Ws@g@}@i@a@Q}Aa@SIa@_@MMeDyFJ_@Qg@mBgDe@}@k@o@WWCHk@`DcAbGaArFw@tFg@bEi@rGgAzPi@dJg@dI_@`G]dEs@~GiAzHyApHW~@]~A_AlDkBlGqCbHcBzDwAvC{BbFcCrFuBvESDGDSXk@xAU\\O^aArCsApDuChGmB~D{GpN{DnIqApCm@nA_AxAGFQLI?UEUOQ]Qa@Uy@a@aBsAwFcA}DQ]]SQUCJABCBOYKSGOIk@Ay@Cc@OYOGM@KHILMj@o@n@_Af@i@\\{B~AcD`CsEpDaGrEaFlDa@b@MPg@jA]VsBvAOHhAxEdA~Dd@dBZvAf@jBjAxEu@j@[ZaAtAY^KJl@zBfCvJHRMP]z@[dAk@rC_@rAc@r@URa@Re@PUFUJQNe@x@S`@U`@QRQNUDI@c@GeAWYAg@PWR]d@a@dAn@n@LL\\[BEZRHr@B^FZPv@DZD@?BLn@Hd@Hb@HXJp@LC"
         },
         "summary" : "Heather Bikeway",
         "warnings" : [
            "Bicycling directions are in beta. Use caution – This route may contain streets that aren't suited for bicycling."
         ],
         "waypoint_order" : [ 0, 1 ]
      }
   ],
   "status" : "OK"
}
```

##LINKS to display PlaceIDS
Start Point: https://www.google.com/maps/place/?q=place_id:ChIJSxASt5l1hlQRJ8Ti_bDBmpE
First Waypoint: https://www.google.com/maps/place/?q=place_id:ChIJwW3HeIZzhlQRVxJgWI8VjAg
Second Waypoint: https://www.google.com/maps/place/?q=place_id:ChIJb2gVVzZzhlQRW6FKTfIcqMY
End Point: https://www.google.com/maps/place/?q=place_id:ChIJUzqZj0oNhlQRSzlBeYd5v-0 
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
