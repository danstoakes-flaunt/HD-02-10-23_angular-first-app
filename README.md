# HD-02-10-23_angular-first-app

This is a tutorial Angular project that was completed on the 2nd October 2023 as part of Hack Day.

## What it does

The db.json file simulates an API endpoint that feeds property information into the application. These properties can be viewed and filtered via the frontend, with an optional form to submit, too.

## How to run

Clone the repository and run `npm install`. Once all the packages are installed, run `npm install -g json-server` to install the required package for API simulation. To get the API to feed data into the application, run `json-server --watch db.json`. Once the simulated API endpoint is working, run `ng serve` and the application should be viewable on [http://localhost:4200/](localhost:4200). 