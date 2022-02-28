# pl3

- [X] [Read: ArcGIS Enterprice ](https://enterprise.arcgis.com/en/get-started/latest/windows/what-is-arcgis-enterprise-.htm) 
- [ ] [Review: Clients for ArcGIS Enterprise](https://enterprise.arcgis.com/en/get-started/latest/windows/portal-clients.htm)
- [ ] [Review: ArcGIS Server](https://enterprise.arcgis.com/en/server/latest/get-started/windows/what-is-arcgis-for-server-.htm)
    - [ ] [what you can actually do with ArcGIS Server by itself withou federating](https://enterprise.arcgis.com/en/server/latest/get-started/windows/what-s-included-with-arcgis-server.htm)
    - [ ] [Read:  ArcGIS Server 10.9](https://www.esri.com/arcgis-blog/products/arcgis-enterprise/announcements/removal-of-arcmap-based-runtime-from-arcgis-enterprise/)
- [ ] [Review: REST API]( https://developers.arcgis.com/rest/services-reference/get-started-with-the-services-directory.htm)
    - [ ] [Complete the following ESRI class Introduction to the ArcGIS for Server REST API](https://www.esri.com/training/catalog/57630436851d31e02a43f16a/)
    - [X] <b>Submit:</b> [Esri Transcript](https://followthepowells.github.io/pl3/Janelli_Powell_Transcript_02272022.pdf)
    - [ ] [Review: Output formats that are possible using the REST API](https://developers.arcgis.com/rest/services-reference/output-formats.htm)
- [ ] [Read: ArcGIS Server 101](https://www.esri.com/about/newsroom/arcuser/arcgis-for-server-101/)
- [X] [Confirm you can Login to AWS](https://console.aws.amazon.com/console/home?region=us-east-1)
- [ ] [Publish the Canada Service to the Luna server (During your lab)](https://www.youtube.com/watch?v=nIRlZN9ECwY)

- [X] <b>Submit:</b> Be prepared to detail the best practice of using 6443 only to publish and administer map services and TCP 443 for using the published services. 
- [X] Demo: Please be prepared to demonstrate this process with only your own notes or ArcGIS official documentation for help. https://luna.flemingcollege.ca/arcgis/rest/services/biggerbrains61/CanadaJPowell/MapServer/0

- [X] [Adding ArcGIS Server(Luna) map Services to ArcGIS Online](https://luna.flemingcollege.ca/arcgis/rest/services/biggerbrains61/CanadaJPowell/MapServer/0)
- [X] Create: To add the service to a map in ArcGIS Online, you must first make an ArcGIS Online Item to reference the service from the Luna server at Fleming.
- [X] [Reference: Review the documentation about using ArcGIS Server services in ArcGIS Online](https://doc.arcgis.com/en/arcgis-online/reference/arcgis-server-services.htm)
- [ ] Question: Why did you have to add ADROOT\ to the login information when adding the luna layer reference to ArcGIS Online? Did your map projection change? What is the initial map extent? What properties from your originally published map carry forward? Explore the service from this context in ArcGIS Online and what can be done in the new ArcGIS Online map viewer (do not use the classic version) to enhance your map. Change (override) its cartography to display the best way possible for a map showing Canada and its provinces. Do not hesitate to re-publish the map service in ArcGIS Pro to make improvements.
- [X] <b>Submit:</b> Your published map service, its AGOL item and Web Map (using the modern one, not the classic version) will be submitted as part of your next practical lab. This practical lab activity is the focus for the required pass to earn the credit in this course.
    - [X] [My Canada Feature Layer in AGOL](https://fleming.maps.arcgis.com/home/item.html?id=0f4680a3e79245d29e74ee00c55c0c12)
    - [X] [My Canada Web Map in AGOL](https://fleming.maps.arcgis.com/apps/mapviewer/index.html?webmap=deb744e58345401c99628212bb46bb81)
- [ ] Create: In ArcGIS Pro, create a new map and add the REST endpoint URL for the map service from ArcGIS Online into ArcGIS Pro directly. Using ArcGIS Pro's interface, you can try browsing your "items" in your ArcGIS Online account and add the item that way, or just type the REST URL into ArcGIS Pro. One references directly to Luna, the other goes to ArcGIS Online first then it goes back to Luna.
- [ ] Explore and <b>Submit:</b> what cartographic options are available to override the map service cartography and save a newly-styled map in the ArcGIS Pro Project to 

Bonus (Optional)
- [ ] Create an application using your Luna Canada Map Service
- [ ] <b>Submit:</b>: This item will be a significant bonus if completed as part of your next Practical Lab. Be creative and create a "polished" application showing the provinces of Canada. Before doing this, be sure you understand how to publish data to ArcGIS Server clearly as that is the most important item to complete for this checklist. 

- [ ] Read: Feature Service (FeatureServer) vs Map Service (MapServer)
- [ ] [Read more](https://enterprise.arcgis.com/en/server/latest/publish-services/windows/what-is-a-feature-service-.htm)
- [ ] [Read more about Map Service]( https://enterprise.arcgis.com/en/server/latest/publish-services/windows/what-is-a-map-service.htm)
