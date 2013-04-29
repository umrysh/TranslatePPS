TranslatePPS.py
==============

Translate English PowerPoint presentations to another language on Linux.

I needed a way to translate a folder full of pps files into Spanish so I pieced together this script. It utilizes Libreoffice and the Bing Translate API because I'm cheap and it's free :)

Enjoy!


Registering your application
----------------------------

In order to use the Bing translate API you must first register your application and update the
`translator = Translator('<Your Client ID>', '<Your Client Secret>')`
line in `TranslatePPS.py`

To register your application with Azure DataMarket, visit https://datamarket.azure.com/developer/applications/. 

>If you do not yet have a developer account or haven't yet signed up for Bing Translate go here first: [https://datamarket.azure.com/dataset/1899a118-d202-492c-aa16-ba21c33c06cb](https://datamarket.azure.com/dataset/1899a118-d202-492c-aa16-ba21c33c06cb). 

Click on “Register”. In the
“Register your application” dialog box, you can define your own
Client ID and Name. The redirect URI is not used for the Microsoft
Translator API. However, the redirect URI field is a mandatory field,
and you must provide a URI to obtain the access code. A description is
optional.

Contributing
------------

Feel free to fork and send [pull requests](http://help.github.com/fork-a-repo/).  Contributions welcome.

Credit
------------

[Microsoft-Translator-Python-API](https://github.com/openlabs/Microsoft-Translator-Python-API)

NOTE: I had to modify the script to work with Python 3

License
-------

Microsoft-Translator-Python-API is released under the [Openlabs](https://github.com/openlabs/Microsoft-Translator-Python-API/blob/master/LICENSE) LICENSE.

This rest is open source software released under the GNU GENERAL PUBLIC LICENSE V3.
