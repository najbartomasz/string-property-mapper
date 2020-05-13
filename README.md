[![Build Status](https://travis-ci.com/najbartomasz/string-property-mapper.svg?branch=master)](https://travis-ci.com/najbartomasz/string-property-mapper)
[![Coverage Status](https://coveralls.io/repos/github/najbartomasz/string-property-mapper/badge.svg?branch=master)](https://coveralls.io/github/najbartomasz/string-property-mapper?branch=master)
[![SonarCloud Quality Gate>](https://sonarcloud.io/api/project_badges/measure?project=najbartomasz_string-property-mapper&metric=alert_status)](https://sonarcloud.io/component_measures?id=najbartomasz_string-property-mapper&metric=qualitygates)

# string-property-mapper
Maps string properties defined in curly braces (`{}`) to dynamic values.

Example:
```
format = 'Some very {property1} {property2} text.'

// Input
property1 =  'short'
property2 = 'example'

// Output
message = 'Some very short example text.'
```

## Usage
Install **string-property-mapper** package:

`npm install https://github.com/najbartomasz/string-property-mapper.git`
