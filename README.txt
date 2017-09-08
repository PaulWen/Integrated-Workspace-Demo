#############
# Aufsetzen #
#############
1) im Intranet der IBM sein
2) folgende Chrome-Extension installieren: https://chrome.google.com/webstore/detail/ignore-x-frame-headers/gleekbfjekiniecknbkamfmkohkpodhe
    --> dient dem umgehen der "X-Frame-Options: SAMEORIGIN"
3) ggf. für die Wetter Informationen die URL anpassen, sodass sie gültige Login Daten von einem aktiven Weather Company Bluemix Servcie enthät
    --> https://console.bluemix.net/catalog/services/weather-company-data?env_id=ibm%3Ayp%3Aus-south&taxonomyNavigation=cf-apps
4) index.html in Chrome öffnen


###################################
# Weather Company Bluemix Service #
###################################
API ausprobieren: https://twcservice.eu-gb.mybluemix.net/rest-api/

Standortdaten für Hamburg:
	latitude: 53.55
	longitude: 10
	placeId: 9d2ff37ed48c454be93093fa196d7ee25f641c80f721a952c0ee78839a831eee

Beispiel: Wetterbericht für die nächsten 48h in Hamburg
    --> https://twcservice.eu-gb.mybluemix.net/api/weather/v1/geocode/53.55/10/forecast/hourly/48hour.json?language=de-DE&units=m