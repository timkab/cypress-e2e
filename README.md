# WIP

[Buld status]

http://<jenkinsroot>/path/to/job/badge/icon?... (for jobs)
http://<jenkinsroot>/path/to/job/<buildNumber>/badge/icon?... (for builds)

## Cypress run scripts

$npm run <>

cy:open - "TZ=UTC cypress open"
cy:run - "TZ=UTC cypress run"
cy:all - "TZ=UTC cypress run --spec \"**/*.features\""
cy:each - "TZ=UTC cypress run --spec \"**/*.feature\""
cy:run IntroPage/Landing.feature - "./node_modules/.bin/cypress-tags run -g 'cypress/tests/introPage/Landing.feature'"