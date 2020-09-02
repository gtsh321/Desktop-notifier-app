1.	Introduction

A desktop notifier is a simple application which produces a notification message in form of a pop-up message on desktop.

The term desktop notifications refer to a graphical control element that communicates certain events to the user without forcing them to react to this notification immediately. In other words, it is a simple application which produces a notification message in form of a pop-up message on desktop.


There are many reasons that a computer may want to notify you of things not directly related to what you are doing right now. Software updates may be available; you may have received a new instant message; your 300-page print job may have finally finished; you may have only ten minutes of battery left. Sometimes these events need a response or at least acknowledgement, or don’t need to be read immediately, in which case they should be presented in an alert box or some other window.

2. Functionality

 In this project, we able to create a python application i,e a desktop notififier app which track COVID 19 LIVE DATA of our country INDIA on our PC.


The data taken by this application is from the website:- "https://www.worldometers.info/coronavirus/country/india/"   through requests module methods which is then scrapped and parsed by beautifulsoup module , later a GUI is made with the help of TKINTER module and a notification is created through plyer module and lastly to make to create threads so that both applications(GUI +NOTIFIC.) get stop when we don’t require them any more.

