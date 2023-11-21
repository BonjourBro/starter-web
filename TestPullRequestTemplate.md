# Before submitting this Pull Request(PR), please make sure:

- [ ] Your code build is clean without any errors or warnings

- [ ] Any Feature flags implemented follow the recomenedations at [Feature Flagging][def]

- [ ] You have registered all Feature Flags used to [Feature Flag Registry][def2]

- [ ] You have added unit tests with a minimum of **80% coverage**

- [ ] MUnit test completed without calling external systems

- [ ] You have updated env-properties.yml files for all known environments, including those higher than QA

- [ ] Each of your integrations have a **README.md** with

      1. link to ISD for each integration
      2. Instruction for how to implement Smoke Test
      3. How to prepare Smoke Test
      4. Instructions on how to trigger the test
      5. Items to check and expected values

- [ ] milestonesID values are unique within the application and preferably, globally unique. 

- [ ] DataWeave files are in src/main/resources/dataweave/ 

- [ ] Your applications <env>-properties.yaml are uniform and tidy, files structure and spacing are uniform - same white space and keys

- [ ] YAML files comply to standards and sufficiently pass yamllint

    * Check against [YAML rules][def3]
        
- [ ] Files higher than Dev/QA match dev-properties.yaml

- [ ] Unknown encripted properties are marked with placeholders ("![placeholder]") 