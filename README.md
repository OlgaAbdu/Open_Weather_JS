# OpenWeather_05

https://openweathermap.org

**How to start working in our project?**

1. Clone repository to your machine.

2. Navigate to project root folder.

3. Run command ```npm ci``` in terminal VScode.

4. After, execute ```npx cypress open```  to run tests.

**Project Coding Convention**

Naming conventions:
We shall use Camelcase for naming conventions: ```camelCase```

Spec names:
student should create the spec containing the name of the group: ```bugBusters.cy.js``` 
or 
all students who do not have a group should create spec named - ```noGroup.cy.js```

**Spec structure:**

- Each block ```describe``` should contain name of group
- Each test (```it```) should contain name of test case (```AT```) 
example:

describe('groupBugBusters', () => {

    it('AT_003.001 | Search City', function () {
        ...
    })

    it('AT_004.001 | Switching weather to Metric system', function () {
        ...
    })
})