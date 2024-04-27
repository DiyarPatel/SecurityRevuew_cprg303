# SecurityRevuew_cprg303
Security Review for Data Storage for STUDYPLANNER app.

a. What is your security recommendation? Why did you choose it?

Recommendation: Encrypt sensitive data stored in the Keystore to ensure it is securely protected.
Justification: Encrypting sensitive data adds an extra layer of security, making it harder for unauthorized users to access user credentials or cryptographic keys even if they gain access to the storage.

b. Who does the recommendation benefit?

Beneficiary: This recommendation primarily benefits end-users by enhancing the security of their sensitive data stored within the application.
c. If the recommendation was found somewhere other than the provided checklist, include a link to it.

Source: This recommendation is a common practice in mobile application security and aligns with best practices for protecting sensitive data.
d. When would the recommendation have to be implemented?

Implementation Timeline: Given the critical nature of protecting sensitive data, the implementation of encryption for the Keystore should be prioritized and integrated into the application's next release cycle.

e. Why do you think your project needs your recommendation?

Justification: Our project needs this recommendation to ensure that sensitive user data, such as credentials or cryptographic keys, is adequately protected from unauthorized access, maintaining user trust and compliance with data protection regulations.

f. How do you think your recommendation could be applied?

Application: Implementing encryption for sensitive data stored in the Keystore involves using cryptographic algorithms to convert the data into a secure format. This implementation is feasible and can be integrated into the existing data storage mechanisms of the application with proper encryption libraries and practices.
