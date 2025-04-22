### Morzil

Visual your Physical Security Posture at any time, with capabilities to plugin AI enhancements to analyze Door Forced Opens, Tailgating, Invalid Access Granted and so on..
Morzil aims to be the one stop solution for:
1. Access Control Integrations
2. Video Management Systems (VMS) Integrations
3. Visualizations of all kinds of physical security assets
4. Integration with third party products for an Eagle-Eye coverage

## Project Strcture
The project contains:
1. a react based frontend running as the renderer process `app/src/renderer`
2. the main process running as the backbone `app/src/main`

## Running Locally
1. Navigate to the app folder from the repo root
```
cd app
```
2. In the app directory, install dependencies
```
npm install
```
3. In the app directory, run the electron main process + the renderer process
```
npm run start
```

## Build and Dev Scripts
Navigate to `app/package.json` to see a list of all build/dev/test scripts being used in Morzil. `npm` and `yarn` both work fine, feel free to choose whatever. 

