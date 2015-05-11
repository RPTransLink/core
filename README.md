# core
Multi-platform project for Translink Vancouver based on GhoneGap

Currently major asset: src/www/index.html

Workflow: <br />
1. 'cd src' and 'phonegap serve'. PhoneGap should serve the app at port 3000 locally by default.<br />
2. Install PhoneGap Developer App for your phone. Open it and connect it to the local server just set up. The app should be running on your phone. <br />
3. Anytime you made a change to files under src folder, the app on your phone will be refreshed to the latest code so you can test it.<br />
4. You can also connect the local server in latest IE and open console to debug. <br />

Features: <br />
1. Given stop number, return stop estimates: first provide a brief estimates info given the stop number, then one can check into details the estimates of a bus route.

To do list: <br />
1. For feature #1: deal with not wrong stop number; if there is only one bus route, provide detailed info by default; provide bus route name; provide stop name.
