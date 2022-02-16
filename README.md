# js_calculator

Current Status as of Feb 16 Wed 2:03am Santiago Time:

Was able to figure out how to run the math.js in my own local console, but not on browser where I need it to run to serve the calculator app

I’ve commented out the first 3 lines of my main.js file where the math.js related functions live

In my projects current state (with those 3 lintes commented out), the calculator works in browser, but relies on the eval() function which I’ve read should never be used for user facing applications since it allows potentially dangerous scripts to be passed through to the user

My goal is to figure out how to get math.js (specifically the evaluate() function) to run in browser, so I can reformat my main.js file to be based on math.evalutate()
