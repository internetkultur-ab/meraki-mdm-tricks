# meraki-mdm-tricks
Här publicerar jag små hacks jag gjort i Meraki MDM.


## En liten webapp för förtroendevaldas iPads
webapp-support-och-emeetings

Denna skickar jag ut som ett Web Clip till iPads för förtroendevalda. Jag har skrivit den i PHP bara för att det var det jag råkade kunna bäst. Det är bara _GET-variablerna som är i PHP så du kan enkelt skriva om dem till något annat. 

Demo av webbappen finns här:
https://youtu.be/mOrIh5NRSlw

För att webbappen ska få tag i variablerna från Meraki måste du pusha ut den genom en särskild profil, webclip-fv-support.mobileconfig. Ändra till rätt URL på rad 3205. 

I Meraki trycker du "Add profile" och väljer "Upload custom Apple profile" för att ladda upp profilen.
