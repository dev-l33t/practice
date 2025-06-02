# Login Module - Test Cases

| TC ID  | Scenario                                      | Steps                                                                 | Expected Result                                          | Priority | Severity |
|--------|-----------------------------------------------|-----------------------------------------------------------------------|----------------------------------------------------------|----------|----------|
| TC001  | Login with valid credentials                  | 1. Open login page<br>2. Enter valid email/password<br>3. Click login | User logs in successfully and redirects to dashboard     | High     | Critical |
| TC002  | Invalid email format                          | 1. Enter "abc@" as email<br>2. Enter valid password<br>3. Click login | Error message "Invalid email format"                     | Medium   | Major    |
| TC003  | Password field masking                        | 1. Enter password in input box                                       | Password should appear masked                            | Low      | Minor    |

