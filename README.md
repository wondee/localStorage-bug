# localStorage-bug
Possible Chrome bug regarding reading localStorage

Run it via:

'''
npm install
node server.js
'''

- Call *http://localhost:8080/read.html* in Tab 1 (Do not close the popup!) 
- Call *http://localhost:8080/write.html* in Tab 2
- Close Popup in Tab 1, see in DevTools that the value did not update properly

stackoverflow question: https://stackoverflow.com/questions/56751883/localstorage-not-updated-during-alert-block

