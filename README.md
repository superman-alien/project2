# project2


MVP: AMAP is an electronic map service platform in China, the product aims to give all uses locations they want and the route to the destination. Also, there are also other platform like the platform for taxi calling, which needs locations of both passengers and destinations. At this time API is used to transfer data of locations to the other applications.

Modular Design: In our product, the users give instructions of what information of locations they want and what they want to do with these locations. Our product will get the locations’ data first and then processed to the data that can be transferred to the users. Lots of information can be calculated like how many buses are near the station that the user stand in. Also, government can use this to help with traffic jam and environment protection.

Users: Everyone who use AMAP to do navigation, Other APPs who need location information service, Government.

User Stories: 1. When people want to find the route to a specific destination, they can use this to search the best one. 2. When taxi driver wants to know where to pick up the passenger or what’s the most efficient way to pick up multi passengers in one trip, they can use this to find out. 3. When government wants to find where has traffic jam, they can get information from the map and then change the traffic control signals. 3. When someone wants to know how long he has to wait for the bus come, he can use this to check.


API
lbs.amap.com

This project is based on a map service company in China. The API platform is supported by Alibaba company.

About this API there are many kinds of common festures, for example:
PointCloudLayer - https://lbs.amap.com/api/loca-api/demos/point_cloud/storm_water
ScatterPointLayer
RoundPointLayer
IconLayer
LineLayer
LinkLayer
PolygonLayer
HeatmapLayer
GridLayer
HexagonLayer
DistrictLayer
CountourLayer
LabelsLayer
