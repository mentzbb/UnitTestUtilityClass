# Unit Test Utility Mentz Challenge

## About
For an overview of Mentz, see the [Blog Post](http://bobbuzzard.blogspot.com/2019/05/introducing-mentz-salesforce-developer.html)
 
This challenge requires you to write unit tests for an Apex utility class that provides helper
methods for processing opportunity records.

The following Trailhead modules are available to learn more about unit testing in Apex:

* [Apex Testing](https://trailhead.salesforce.com/en/content/learn/modules/unit-testing-on-the-lightning-platform)
* [Unit Testing on the Lightning Platform](https://trailhead.salesforce.com/en/content/learn/modules/unit-testing-on-the-lightning-platform)


## Taking the Challenge

To take the challenge you build out the ./force-app/main/default/OpportunityUtils_Test.cls class to cover all scenarios you can identify. Note that 100% test coverage does not indicate all scenarios are covered! Check all of your unit tests pass before submitting your solution. There are a couple of ways of doing this.

### Scratch Org
If you want to iterate on your development, use the Salesforce CLI force:source:push/pull commands 
to deploy to your scratch org and execute the unit tests.

### Developer Edition
To deploy to a non-scratch org, use:

`sfdx force:source:deploy -p ./force-app/ -u <username>`

if you don't want to deploy the code, you can carry out a check deployment and execute the tests to get the results:

`sfdx force:source:deploy -l RunSpecifiedTests -r OpportunityUtils_Test -c -u <username> -p ./force-app/`

## Requesting Mentoring

Ensure you have installed the [MENTZ sfdx plugin](https://www.npmjs.com/package/mentz).

Execute the following command: 

`sfdx mentz:publish -c "<comment>" -f <solution_filename> -u <username> -m`

Parameters:

| Name | Description |
| --- | --- |
| `<comment>` | a comment that raises any areas of concern to the mentor |
| `<solution_filename>` | the full pathname to your unit test class |
| `<username>`  | your username in the Mentz instance |

## Publishing the solution

Ensure you have installed the [MENTZ sfdx plugin](https://www.npmjs.com/package/mentz).

Execute the following command: 

`sfdx mentz:publish -c "<comment>" -f <solution_filename> -u <username>`

Parameters:

| Name | Description |
| --- | --- |
| `<comment>` | a comment that raises any areas of concern to the mentor |
| `<solution_filename>` | the full pathname to your unit test class |
| `<username>`  | your username in the Mentz instance |

