# Meteor on FHIR Forum
We decided to write a Wordpress/Discourse clone using Meteor and FHIR resources.  


#### Installation

```sh
meteor npm install --save jquery bootstrap react react-dom react-router react-bootstrap react-komposer react-router-bootstrap faker jquery-validation react-addons-css-transition-group react-addons-pure-render-mixin react-toolbox react-mixin faker react-highcharts eslint-plugin-react eslint-plugin-meteor eslint-config-eslint react-scroll-box

meteor npm install
meteor
```

#### Usage  

```sh
## Initialize with FHIR test data
INITIALIZE=true Patients=true Practitioners=true meteor
```


#### Testing    

```sh
meteor npm start
meteor npm test
meteor npm run staging
meteor npm run production

## Test Coverage
COVERAGE_APP_FOLDER=/Users/abigailwatson/Code/GlassUI/fire-demo/ meteor npm run-script coverage
# http://localhost:3000/coverage
```

#### Mobile Build  

```sh
meteor run ios --mobile-server meteor-on-fhir.meteorapp.com
```    



#### Licensing

Abigail Watson
Artistic License 2.0

The code is free, but be careful about media assets, some of which are not publicly licensed.  
