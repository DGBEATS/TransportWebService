To properly access the endpoints, you are required to have the NaPTAN database inside the 'data' file of zip folder. This can easily be...
accessed and downloaded via gov.uk: https://beta-naptan.dft.gov.uk.

To call the different endpoints, here are the links:
1) To run the server - Just run the program as normal
2) To test the the root to make sure it's working - http://localhost:8088/test
3) To test the counting of local stops - http://localhost:8088/stopcount?locality=Manchester+City+Centre (Manchester city center can be
replace with any other locality found in the database)

4) To test the calling of the location of the stop and the specific type of transport there - http://localhost:8088/stops?locality=Manchester+City+Centre&type=MET
(Manchester City center can be replace with any other locality found in the database)
(MET can be replaced with any other transport type found in the database e.g. BUS or FER)

5) NOTE: THIS LAST ENDPOINT IS INCOMPLETE
  -To test the exact location of the stop by latitude and logitude of the stop in addition to the type of transport - 
	http://localhost:8088/nearest?latitude=X&longitude=-Y&type=FER
	
	Where X = (a specific latitude)
	Where Y = (a specific longitude)
	(The Kyle of Lochalsh in Scotland)
