# Henceforward

[![Netlify Status](https://api.netlify.com/api/v1/badges/ce5e098c-fda6-4521-8edf-604991791e4b/deploy-status)](https://app.netlify.com/sites/henceforward/deploys)

## Initial Setup
```
git clone git@github.com:thalida/henceforward.git
cd henceforward
npm install
```

## Running Locally
```
npm run serve
```
Runs a local version with hot-reload at http://localhost:8080/


## Build & Deploy
Continous deployment is enabled on Netlify, both main and staging auto-deploy from merged PRs. 

* production site: https://henceforward.co
* staging site: https://staging.henceforward.co

### Netlify Settings
<img width="946" alt="Screen Shot of Netlify continous deployment settings" src="https://user-images.githubusercontent.com/3401715/119423701-e587c880-bcd1-11eb-828a-09e8b77e2de3.png">


### Staging
1. **Create a new PR on Staging**.
2. **Verify your changes via Netlfiy.** Netfliy will automatically create a preview build linked the PR.
3. **Merge to Staging**.
4. **Staging Build Starts** Netlify will automactially rebuild and deploy the staging site.
5. https://staging.henceforward.co wil be updated!


### Production
1. **Create a new PR to Main**. `main` is the production branch.
2. **Verify your changes via Netlfiy.** Netfliy will automatically create a preview build linked the PR.
3. **Merge to Main**.
4. **Production Build Starts** Netlify will automactially rebuild and deploy the production site.
5. https://henceforward.co wil be updated!

---

## Mailchimp
Mailchimp form is embedded on the Coming Soon landing page.
https://github.com/thalida/henceforward/blob/main/src/views/ComingSoon.vue#L15-L50

<img width="642" alt="Screen Shot of form on the landing page" src="https://user-images.githubusercontent.com/3401715/119425411-4fee3800-bcd5-11eb-8337-b76db9b720c5.png">


---

## Analtyics
Google Analytics is used for tracking and monitoring site activty.


---


### Additional Commands

**Run All Tests**

```
npm run test 
```


**Run your unit tests**
```
npm run test:unit
```

**Lints and fixes files**
```
npm run lint
```

---


### Additional Resources
* Customize Vue Config: [Configuration Reference](https://cli.vuejs.org/config/).
