# postman-api-tests
Repository made for portfolio purposes.
https://books-api.glitch.me/

## Repo Structure
- collections - Test suites grouped into Postman collections of requests.
- envs - Set of variables used for different requests.
- data - Set of data for Data-Driven test.
## Dependencies
1. Installed Postman
2. Installed Newman
3. Installed newman-reporter-htmlextra

## Setup
1. Install all dependencies listed above.
2. Download repo files.
3. Launch Postman
4. Import **collections**, **envs** into new workspace.
5. Select **Base** environment as active environment.
## Running full test
1. Open **Runner** window (Ctrl+Shift+R).
2. Drag and drop **Full test** collection on the runner widow. 
    - Optionally: Select 'save responses' to see response headers and bodies for all requests.
3. Click 'Run full test' button.
