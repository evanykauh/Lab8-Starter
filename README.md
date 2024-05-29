# Lab8-Starter

### Name: Evan Kauh

### URL:
https://evanykauh.github.io/Lab8-Starter/

### How are graceful degradation and service workers related?
Graceful degradation is a technique used in web apps to ensure that the page remains functional even if some components fail. Service workers, which run in the background on a separate thread, play a key role in this process. They store call requests and their respective responses locally. If a call is made later without internet access, the service worker can still provide the stored response, enabling the app to function offline. By handling failed requests, such as when the user is offline, service workers help implement graceful degradation, maintaining the program's functionality even during network failures.