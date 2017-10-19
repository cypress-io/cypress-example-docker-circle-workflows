# cypress-example-docker-circle-workflows [![CircleCI](https://circleci.com/gh/cypress-io/cypress-example-docker-circle-workflows.svg?style=svg)](https://circleci.com/gh/cypress-io/cypress-example-docker-circle-workflows)

[![Greenkeeper badge](https://badges.greenkeeper.io/cypress-io/cypress-example-docker-circle-workflows.svg)](https://greenkeeper.io/)

> Cypress + Docker + CircleCI Workflows = ❤️

You can run multiple Cypress tests in parallel after "building" the code
using CircleCI [Workflows feature](https://circleci.com/docs/2.0/workflows/).
See [circle.yml](circle.yml) in this repo how the dependencies and cached
code is setup among the jobs.

![CircleCI workflow](screenshots/workflow.png)

Note: if you want to see "plain" CircleCI v2 example without workflows,
check out [cypress-example-docker-circle][plain].

[plain]: https://github.com/cypress-io/cypress-example-docker-circle

## Happy testing

If you find problems with Cypress and CI, please

- consult the [documentation](https://on.cypress.io)
- ask in our [Gitter channel](https://gitter.im/cypress-io/cypress)
- find an existing [issue](https://github.com/cypress-io/cypress/issues)
  or open a new one
