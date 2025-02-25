# Backend Boilerplate NestJS

A backbone for your coding challenge.

## Contents

- [Backend service](app) - a NestJS service with a `/ping` endpoint. Extend with your code.
- [API test suite](cypress/integration/backend.spec.js) - a Cypress test suite. Extend with your tests.
- [Pipeline](.github/workflows/tests.yml) - a test Runner that executes the Cypress tests on push to a branch other than `master`/`main`.

## Getting started

1. Make sure npm & node are configured on your local env. You can download those distributions for your platform [here](https://nodejs.org/en/download/).

2. Build your app.

```bash
npm install
npm run build
```

3. Start your app.

```bash
npm install
npm run start
```

4. Run Cypress tests

```bash
npm run test
```

---

Made by [DevSkills](https://devskills.co).

Did you find this repo useful? **Give us a shout on [Twitter](https://twitter.com/DevSkillsHQ) / [LinkedIn](https://www.linkedin.com/company/devskills)**.

