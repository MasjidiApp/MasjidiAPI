# Masjidi API

This is an attempt to have first open API platform for Salah and Iqama time. The goal of this API is to expose core services required to build Salah and Iqamah applications across various different platfoms. Ummah Services provides implementation of the API along with hosting services. For more information please send open an Issue on GitHub

Some of the core features the API will offer are:

# Prayer Times
1) Core prayer times calculations based on universally accepted calculation methods. 
2) Defaults configuration per country for calcuations that match with the locals.
3) Ability to provide custom configuration options


# Masjid Listing
1) Crowd sourced Masjid Listing across the world with some manual review to keep listing clean
2) Crowd source updates to the masjid as they change address, contact information.
3) Great API surface to get lists based on user location

# Masjid Iqama

Iqama is the time when salah starts at the masjid. The rules on this varry across the world and hence we support various different models.

1) Ability to publish and fetch Iqama times for Masjids.
2) Iqama times can be crowded sourced or managed by masjid administrators. 
3) Iqama times can be sourced from




* Manual entry
* Calcualted (some minutes after salah starts, change every day with salah time changes)
* Rule based (x minutes after changing only on certain days of the week etc. Refer to exmples to see some samples of the different rules)
* Import from a Google Spreadsheet


# Masjid Details
  Masjid details supported today are:
  Name, Address, Long/Lat, TimeZone, Phone Number, Email, Website. Twitter Handle, Facebook page. Hijri method. Salah Configuration details. 

  Up coming details for masjid not supported yet:
 - [ ]  Events
 - [ ]  Programs/Classes
 - [ ]  Media (Audio/Video), Live stream
 - [ ]  Annoucements
 - [ ]  Ratings
 - [ ]  Donations/Payments

# Hijri Date
Hijri dates are challenging because each community/family follows a different method. Our objective is to be support some widely accepted methods and let Individuals/Masjids pick which method they follow. API will provide details on the source, method and if the date is calculated or predicted. 

# Authentication/Authorization
All Masjidi APIs will be protected using an Authentication Token to be used to identify the called. Updates to data (referred as admin functions), will requier authorization to the object being updated.

# API Browser and Console
Masjidi API is available at following URL:

https://apidocs.masjidiapp.com/

Please feel free to playaround using the API Console. If you have any comments or suggestions, please open a PR(for proposed changes) or Issue on GitHub. 

# Conclusion 
Our goal is to make this API be a comprehensive set of APIs need to build common use-cases. Please reach out to us if you any additional requests. You can contact us by opening an issue on GitHub
