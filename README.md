Install extension: https://chrome.google.com/webstore/detail/eeifaoomkminpbeebjdmdojbhmagnncl

This extension gives basic support for launching ClickOnce applications from Chrome.  It includes a mime type mapper that will correctly launch x-ms-applications when a link to a .application is clicked.  

To fully conform to the ClickOnce spec the user agent of the browser should advertise the version of the .NET Framework that is installed on the machine.  Since changing the user agent from a plugin or extension is not yet available in Chrome this is not implemented.  If you want to make full use of ClickOnce you can manually change your shortcut to chrome to include the command line argument "--user-agent="Mozilla/5.0 (Windows; U; Windows NT 6.1; en-US) AppleWebKit/534.3 (KHTML, like Gecko) Chrome/6.0.472.55 Safari/534.3 .NET CLR 3.5.30729; .NET4.0E"  (Change this string to reflect your version of Chrome and the installed version(s) of the .NET Framework).

For more information about ClickOnce technology see:
http://msdn.microsoft.com/en-us/library/t71a733d(VS.80).aspx
http://en.wikipedia.org/wiki/ClickOnce

For information on how to detect if ClickOnce for Google Chrome™ is installed on the users computer:
https://github.com/clickoncechrome/clickoncechrome/wiki/Detecting

Google Chrome is a trademark of Google Inc. Use of this trademark is subject to Google Permissions.

