# How to start
- Please open the website from homepage.html only

# When issues occur
- If pages such as the categorypage and productpage does not load properly,
- Check if it is CORS error in the console and the issue lies with itemsData.js
- If so, do the following depending on the browser
- Firefox:
	1. Open Firefox and type "about:config" in the address bar.
	2. Click on the "I accept the risk!" button.
	3. In the search bar, type "security.fileuri.strict_origin_policy" and set the value to false by double-clicking on it.

- Chrome:
	1. Open the Command Prompt on Windows
	2. Enter either:
		- chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security
		- start chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security
	3. This will open an insecure instance of your chrome browser (you do not need to change anything in your other Chrome browser which is secured
	4. Copy the file path of the homepage into the address (e.g.: file:///C:/Users/User/Documents/5CS020-Assignment-Task2-2018015-Kehan/homepage.html)
	5. The application should work properly now

- Please undo all the changes you have done to your browser after checking the application as your browser/device will become vulnerable to threats
- I cannot solve such issues as they are related to the backend and not the frontend