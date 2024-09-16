- 👋 Hi, I’m @APAULINO123
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
APAULINO123/APAULINO123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
O ERP ORACLE esta integrado po API com o legado ROLDNET.
O ORACLE será descontinuado, uma nova integração do S4HANA por API deve ser desenvolvida para o RODNET.
Devera ocorre o minimo de ajustes no RODNET.
O ORACLE envia uma lista de ordens para roteirização no ROADNET, agora o S$hana devera enviar uma lista de remessa (VBELN) para roteirização.
O ORACLE, de acordo com as estruturar em anexo, enviada audados do transportato para atualização da base de dados de transportadores do ROONET, o S$ deve fazer o mesmo.
Criar uma API de Integração com o ROLDNET, aproveitado e concatenado os dados na API com ocampo do S4hana. 

Método
CreateRoutingSession
SaveLocations
SaveRoutingImportOrders
RetrieveRoutingImportOrdersByCriteria
RetrieveRoutingOrderByIdentity
RetrieveRoutingStopByIdentity
RetrieveRoutingRouteByIdentity

RetrieveRoutingRouteByIdentityResponse
Recuperar resposta de roteamento por identidade de rota


Body

route Identity
regionID: VIGORSP
internalSessionID: 24506
internalRouteID: 1026334
routeNumber: 0
routeID: Não atendido
description: (vazio)
origin (xsi:type="ns1:LocationIdentity")
regionID: (vazio)
locationType: (vazio)
locationID: (vazio)
destination (xsi:type="ns1:LocationIdentity")
regionID: (vazio)
locationType: (vazio)
locationID: (vazio)
helper: false
capacity
size1: 0
size2: 0
size3: 0
maxRunningCapacity
size1: 0
size2: 0
size3: 0
color: 0
distance: 0
startingQuantity
size1: 0
size2: 0
size3: 0
endingQuantity
size1: 0
size2: 0
size3: 0
drivers (xsi:type="ns1:EmployeeIdentity")
regionID: (vazio)
employeeID: (vazio)
drivers (xsi:type="ns1:EmployeeIdentity")
regionID: (vazio)
employeeID: (vazio)
routeEquipment (xsi:type="ns1:RoutingEquipmentIdentity")
regionID: VIGORSP
equipmentTypeID: 3/4
equipmentID: ASALE01
isTypeOnly: false
status: rsActiveRoute
day: dowNone
teamSplit: false
modelID: (vazio)
loadPriority: 0
maximumTime: 0
maximumTravelTime: 0
preferredTime: 0
regularTime: 0
travelTime: 0
serviceTime: 0
totalTime: 0
paidTime: 0
nonPaidTime: 0
goalDistance: -1
breakTime: 0
paidBreakTime: 0
waitTime: 0
paidWaitTime: 0
layoverTime: 0
paidLayoverTime: 0
driverRegularTimeCost: 0
driverOverTimeCost: 0
driverStopCost: 0
driverDistanceCost: 0
driverPieceCost: 0
driverFixedCost: 0
equipmentFixedCost: 0
equipmentDistanceCost: 0
equipmentTimeCost: 0
tollCost: 0
totalCost: 0
flushCost: 0
reloadTime: 0
creationMethod: (vazio)
week: 0
fees: 0
lastStopIsDestination: false
depotServiceTime: 0
originIsDestination: true
calculateReloadTime: false
shuttleTime: 0
shuttleDistance: 0
preRouteTime: 0
postRouteTime: 0
stemDistanceOut: 0
stemDistanceIn: 0
stemTimeOut: 0
stemTimeIn: 0
previousReloadRouteIdentity (xsi:type="ns1:RoutingRouteIdentity")
regionID: VIGORSP
internalSessionID: 24506
internalRouteID: 0
nextReloadRouteIdentity (xsi:type="ns1:RoutingRouteIdentity")
regionID: VIGORSP
internalSessionID: 24506
internalRouteID: 0
startingLoadType: rrtAsNeeded
preferredSkillSet: (vazio)
dispatcherUserIdentity
internalUserID: -1
profit: 0
dockPosition: 0
dockDepartureTime: 1970-01-01T00:00:00.0000000Z
dockLoadTime: 0
startTimeDelay: 0
totalLoadTime: 0
additionalLoadTime: 0
scenarioOverride: (vazio)
actualDriver1Key (xsi:type="ns1:EmployeeIdentity")
regionID: (vazio)
employeeID: (vazio)
actualDriver2Key (xsi:type="ns1:EmployeeIdentity")
regionID: (vazio)
employeeID: (vazio)
actualSizes
size1: 0
size2: 0
size3: 0
actualStops: 0
actualDistance: 0
odometerStart: 0
odometerFinish: 0
actualHelper: 0
comments: (vazio)
actualDriverRegularTimeCost: 0
actualDriverOvertimeCost: 0
actualDriverStopCost: 0
actualDriverDistanceCost: 0
actualDriverPieceCost: 0
actualDriverFixedCost: 0
actualEquipmentFixedCost: 0
actualEquipmentDistanceCost: 0
actualFees: 0
actualServiceTime: 0
actualTravelTime: 0
actualBreakTime: 0
actualPaidBreakTime: 0
actualWaitTime: 0
actualPaidWaitTime: 0
actualLayoverTime: 0
actualPaidLayoverTime: 0
actualPreRouteTime: 0
actualPostRouteTime: 0

RetrieveRoutingRouteByIdentity
Recuperar rota de roteamento por identidade

Body

identity
regionID: VIGORSP
internalSessionID: 24506
internalRouteID: 1026334
options
applyRoadnetAnywhereSyncRules: false
level: (vazio)
retrieveActivities: false
retrieveEquipment: true
retrieveActive: false
retrieveBuilt: false
retrievePublished: false
tzOptions
embeddedInTimestamp: true
optionType: tzoGMT
timeZone: tmzBrasilia

RetrieveRoutingStopByIdentit

Recuperar parada de roteamento por identidade

Body

RetrieveRoutingStopByIdentity
identity
regionID: VIGORSP
internalSessionID: 24506
internalStopID: 7009913
options
applyRoadnetAnywhereSyncRules: false
level: (vazio)
retrieveActivities: false
retrieveEquipment: true
retrieveActive: false
retrieveBuilt: false
retrievePublished: false
tzOptions
embeddedInTimestamp: true
optionType: tzoGMT
timeZone: tmzBrasilia


RetrieveRoutingStopByIdentityResponse
Recuperar parada de roteamento por resposta de identidade

Body

RetrieveRoutingStopByIdentityResponse
stop
routeIdentity (xsi:type="ns1:RoutingRouteIdentity")
regionID: VIGORSP
internalSessionID: 24506
internalRouteID: 1026334
stopIdentity (xsi:type="ns1:RoutingStopIdentity")
regionID: VIGORSP
internalSessionID: 24506
internalStopID: 7009913
locationIdentity (xsi:type="ns1:LocationIdentity")
regionID: VIGORSP
locationType: SIT
locationID: 292079710001
tripNumber: 0
sequenceNumber: 1
stopIx: 0
serviceTime: 0
serviceTimeFixedPortion: 0
serviceTimeVariablePortion: 0
travelTime: 0
distance: 0
deliveryCost: -1
stopType: stpStop
standardFragmentNumber: 0
locationName: (vazio)
storeNumber: (vazio)
contact: (vazio)
address
line1: (vazio)
line2: (vazio)
crossStreet: (vazio)
region1: (vazio)
region2: (vazio)
region3: (vazio)
postalCode: (vazio)
country: (vazio)
phoneNumber: (vazio)
deliveryDays: (vazio)
internalDeliveryDays: (vazio)
latitude: 0
longitude: 0
buildingDeliverySequence: 0
timeZone: tmzBrasilia
sessionDate: 2024-07-05
sessionDescription: Sessao API
routeID: Não atendido
routeDescription: (vazio)
routeStatus: rsActiveRoute
driver1Identity (xsi:type="ns1:EmployeeIdentity")
regionID: (vazio)
employeeID: (vazio)
driver1Name: (vazio)
driver2Identity (xsi:type="ns1:EmployeeIdentity")
regionID: (vazio)
employeeID: (vazio)
driver2Name: (vazio)
deliveryQuantity
size1: 15.42
size2: 451.5
size3: 0
pickupQuantity
size1: 0
size2: 0
size3: 0
actualsExist: false
actualSequenceNumber: 0
actualServiceTime: 0
actualTravelTime: 0
actualDistance: 0
actualQuantity
size1: 0
size2: 0
size3: 0
layoverDepartureType: dtFixedDuration
layoverDuration: 0

RetrieveRoutingOrderByIdentity
Recuperar ordem de roteamento por identidade

Body

RetrieveRoutingOrderByIdentity
identity
regionID: VIGORSP
internalSessionID: 24506
internalOrderID: 7564037
options
applyRoadnetAnywhereSyncRules: false
level: (vazio)
retrieveActivities: false
retrieveEquipment: true
retrieveActive: true
retrieveBuilt: true
retrievePublished: true
tzOptions
embeddedInTimestamp: true
optionType: tzoGMT
timeZone: tmzBrasilia

RetrieveRoutingOrderByIdentityResponse
Recuperar ordem de roteamento por resposta de identidade
Body

RetrieveRoutingOrderByIdentityResponse
order
stopIdentity (xsi:type="ns1:RoutingStopIdentity")
regionID: VIGORSP
internalSessionID: 24506
internalStopID: 7009913
orderIdentity (xsi:type="ns1:RoutingOrderIdentity")
regionID: VIGORSP
internalSessionID: 24506
internalOrderID: 7564037
orderNumber: 1836107R
quantities (xsi:type="ns1:CategoryQuantities")
size1: 15.42
size2: 451.5
size3: 0
subtotalCategory1
size1: 0
size2: 0
size3: 0
subtotalCategory2
size1: 0
size2: 0
size3: 0
subtotalCategory3
size1: 0
size2: 0
size3: 0
additionalServiceTime: 0
takenBy: (vazio)
printed: false
userDefinedFields
field1: SEGSP05
field2: 19/12/2023
field3: 29/12/2023
field4: (vazio)
field5: (vazio)
field6: (vazio)
dailyIncrease
size1: 0
size2: 0
size3: 0
beginDate: 2024-07-04
endDate: 2024-07-04
urgency: 38
dependency: 0
selector: (vazio)
orderType: rotOrder
originalPlanType: rptPlanned
lastPlanType: rptPlanned
triggerType: rttNone
orderSource: rosImported
voidOrder: false
uploadSelector: (vazio)
preferredOrigin (xsi:type="ns1:LocationIdentity")
regionID: VIGORSP
locationType: (vazio)
locationID: (vazio)
preferredMRSDepot (xsi:type="ns1:LocationIdentity")
regionID: VIGORSP
locationType: (vazio)
locationID: (vazio)
forceBulkServiceTime: false
dailyUrgencyIncrease: 0
beginQuantity
size1: 15.42
size2: 451.5
size3: 0
beginUrgency: 38
specialInstructions: (vazio)
netRevenue: 0
duplicateOrder: false


SaveRoutingImportOrders
Salvar pedidos de importação de roteiro

Body

SaveRoutingImportOrders
regionId: VIGORSP
orders
orderNumber: 1836107R
internalOrderID: 1836107
sessionIdentity
regionID: VIGORSP
internalSessionID: 24506
quantities
size1: 00000015.420
size2: 00000451.500
pickup: false
deliveryDate: 2023-12-28
locationIdentity
regionID: VIGORSP
locationType: SIT
locationID: 292079710001
isVoid: false
userDefinedFields
field1: SEGSP05
field2: 19/12/2023
field3: 29/12/2023
beginDate: 2024-07-04
endDate: 2024-07-04
urgency: 38
tzOptions
embeddedInTimestamp: true
optionType: tzoGMT
timeZone: tmzBrasilia


Estrutura Principal
Salvar roteamento de pedidos de importação Resposta: (vazio)

xmlns:SOAP-ENV="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:SOAP-ENC="http://www.w3.org/soap/encoding/"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:ns1="http://www.roadnet.com/RTS/TransportationSuite/TransportationWebService"

Body

SaveRoutingImportOrdersResponse: (vazio)

RetrieveRoutingImportOrdersByCriteria
Retrieve Routing Import Orders By Criteria

Body

RetrieveRoutingImportOrdersByCriteria
criteria
sessionID: 24506
regionID: VIGORSP
orderNumber: 1836107R
tzOptions
embeddedInTimestamp: true
optionType: tzoGMT
timeZone: tmzBrasilia


RetrieveRoutingImportOrdersByCriteriaResponse
Recuperar pedidos de importação de roteamento por resposta de critério

Body

RetrieveRoutingImportOrdersByCriteriaResponse
orders
orderNumber: 1836107R
internalOrderID: 7564037
sessionIdentity (xsi:type="ns1:RoutingSessionIdentity")
regionID: VIGORSP
internalSessionID: 24506
quantities (xsi:type="ns1:CategoryQuantities")
size1: 15.42
size2: 451.5
size3: 0
subtotalCategory1
size1: 0
size2: 0
size3: 0
subtotalCategory2
size1: 0
size2: 0
size3: 0
subtotalCategory3
size1: 0
size2: 0
size3: 0
specialInstructions: (vazio)
preferredRouteIDOverride: (vazio)
additionalServiceTime: 0
pickup: false
deliveryDate: 2024-07-05
locationIdentity (xsi:type="ns1:LocationIdentity")
regionID: VIGORSP
locationType: SIT
locationID: 292079710001
takenBy: (vazio)
orderSelector: (vazio)
isVoid: false
forceBulkServiceTime: false
userDefinedFields
field1: SEGSP05
field2: 19/12/2023
field3: 29/12/2023
field4: (vazio)
field5: (vazio)
field6: (vazio)
dailyQuantityIncrease
size1: 0
size2: 0
size3: 0
beginDate: 2024-07-04
endDate: 2024-07-04
urgency: 38
dependency: 0
dailyUrgencyIncrease: 0
preferredOriginIdentity (xsi:type="ns1:LocationIdentity")
regionID: VIGORSP
locationType: (vazio)
locationID: (vazio)
preferredMRSDepotIdentity (xsi:type="ns1:LocationIdentity")
regionID: VIGORSP
locationType: (vazio)
locationID: (vazio)
netRevenue: 0



SaveLocationsResponse: (vazio)
Salvar locais Resposta: (vazio)

Envelope
xmlns:SOAP-ENV="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:SOAP-ENC="http://www.w3.org/soap/encoding/"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:ns1="http://www.roadnet.com/RTS/TransportationSuite/TransportationWebService"

Header

Header: (vazio)

Body

SaveLocationsResponse: (vazio)


SaveLocations
Salvar locais

Body

SaveLocations
locations
locationIdentity
regionID: VIGORSP
locationType: SIT
locationID: 475084111609
description: COMPANHIA BRASILEIRA DE DISTRIBUICAO
address
line1: AV S P 2601 LOTE 6 A 9 PT AREA A
line2: (vazio)
region1: MONGAGUA
region2: JARDIM MARINA
region3: SP
postalCode: 11730000
country: BR
deliveryDays: 36































































