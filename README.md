Jouw Weerbericht

Deze app, zo simpel als hij is, leerde mij veel nieuws. 


Het idee was om een webapplicatie te maken die aan de gebruiker vraagt of hij zijn locatie wil delen. Bij toestemming bezorgt de applicatie hem het actuele weerbericht van de locatie waarin de gebruiker zich op dat moment bevint.

Extra functionaliteit is dat de gebruiker kan kiezen voor de temperatuur in celcius of in fahrenheit en dat, afhankelijk van het weertype, steeds een ander weersymbooltje wordt weergegeven.


------- Geolocation.getCurrentPosition() method -------

Om toegang te vragen tot de locatie van de gebruiker leerde ik de 'Geolocation.getCurrentPosition() method' te gebruiken.

------ Api's ------

Om de gebruiker vervolgens toegang te geven tot weerdata van zijn locatie, maakte ik gebruik van de API van openweathermap.org. Belangrijk voor mij was om het verzoek tot json data in vanilla js te doen en geen gebruik te maken van jquery of andere libary's. Ik gebruikte hiervoor 'Fetch'. Daarmee leerde ik ineens promises te gebruiken: 

fetch(apiRequest).then(function(res) {
                return res.json();
            }).then(function(json) { 
            ////code
            } 


