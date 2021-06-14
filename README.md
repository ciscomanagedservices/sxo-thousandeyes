## SecureX Orchestrator Atomic Actions for ThousandEyes

Additional Resources: 

- API Docs: https://developer.thousandeyes.com/v6/
- BONUS: [ThousandEyes Swagger JSON Doc](/Cisco%20ThousandEyes%20API%20v6.json) 🎉

### In this repository, you'll find the following atomics:

#### 1. [List Tests](/TE-ListTests__definition_workflow_01P64NCSLWBSV7DQX4JFLMdEUnmyzFttPhe)

> **Purpose:** Retrieve & filter configured tests available in your ThousandEyes account

Documentation: https://developer.thousandeyes.com/v6/tests/#/test_list

Steps to use:
1. Setup your ThousandEyes API Target & Account Key
2. Provide a filter criteria/condition & what fields you'd like to have returned (this step is optional - by default, all fields/values are returned)
3. If the request is successful, the output of this atomic is a JSON string w/ rows that match the filter criteria
4. If the request is not successful, the output contains the error message

---

Contributors:

1. Aman Sardana (amasarda@cisco.com)
2. Anant Nambiar (ananambi@cisco.com)

Cisco CX Managed Services - Operate, June 2021
