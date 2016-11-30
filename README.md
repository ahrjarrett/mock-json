# module currently broken, isolating to fix it

only dependency is 'dummy-json', but is too bulky; ideally this module will replace dummy-json with a simpler way to mock data.

goal is to use this to master process.argv and make a global command-line tool that either (a) uses yargs to customize mock data, or preferably (b) will simply run through a few questions to initialize the data, viz. `npm init`
