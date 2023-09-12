1. Path Traversal Exploitation

    Real-World Example: Imagine a hacker wants to buy a high-end gadget on an e-commerce site. Instead of going through the regular checkout process, they manipulate the website's URL directly to access the payment confirmation page. By doing this, they skip the 2FA requirement and successfully make the purchase without authenticating.

2. Token Pivoting

    Real-World Example: A cybersecurity expert discovered a vulnerability in a popular email service. They found that when users logged in, the service issued an authentication token. The expert realized that even if users had 2FA enabled, they could reuse the token to access the email account without needing a new 2FA code.

3. Token Exfiltration

    Real-World Example: An attacker compromised a company's customer database and stole authentication tokens. With these tokens, they were able to bypass 2FA for multiple user accounts. This allowed the attacker to access sensitive information and perform unauthorized actions.

4. Leaked Token Discovery

    Real-World Example: During a security assessment of a popular social media platform, a white-hat hacker noticed that certain API responses contained user-specific authentication tokens. By analyzing these responses, the hacker could retrieve tokens, bypass 2FA, and potentially take control of user accounts.

5. Email Verification Link Manipulation

    Real-World Example: A hacker gained access to a user's email account and discovered an email containing a link to verify a new login. Despite the user having 2FA enabled, the hacker used this verification link to access the account without needing to enter a 2FA code.

6. Session-based 2FA Subversion

    Real-World Example: An attacker exploited a vulnerability in a popular online banking application. They initiated a 2FA login process with their own account and a victim's account simultaneously. After successfully completing 2FA for their account, they intercepted the session and used it to access the victim's account, as the backend only checked for a successful 2FA for the session.

7. Password Reset Persistence

    Real-World Example: A cybersecurity researcher found a flaw in an online forum's password reset process. Even after changing the password multiple times, the user remained logged in without being prompted for 2FA. This allowed the researcher to gain unauthorized access to the user's account.

8. OAuth Compromise

    Real-World Example: An attacker successfully phished a user's Google account credentials. With access to the victim's Google account, the attacker then exploited the OAuth permissions to access various linked services, bypassing 2FA and gaining control over the victim's accounts on those services.

9. Brute Force Precision

    Real-World Example: In a sophisticated cyber attack, an adversary targeted a financial institution with 2FA protection. The attacker employed a methodical approach, trying thousands of possible 2FA codes but beginning with fake ones to avoid triggering alarms. Eventually, they discovered the correct code and bypassed 2FA.

10. Rate Limit Manipulation
- Real-World Example: An attacker targeted a cryptocurrency exchange with a rate-limiting system in place for 2FA code entry. However, the attacker exploited a flaw that allowed them to repeatedly send the same code, effectively resetting the rate limit. This enabled them to carry out a successful brute force attack.

11. Client-Side Rate Limit Bypass

    Real-World Example: An attacker targeted a popular online gaming platform with 2FA protection. They discovered that the platform had no rate limits on 2FA code entry. This allowed the attacker to repeatedly guess 2FA codes without any restrictions, ultimately succeeding in bypassing 2FA.

12. In-App 2FA Variability

    Real-World Example: A cybersecurity researcher examined a financial application that had 2FA enabled for login but not for changing the account email address. By exploiting this inconsistency, the researcher successfully changed the email address associated with an account without encountering 2FA verification.

13. SMS Rate Limit Subversion

    Real-World Example: An attacker targeted a telecommunications provider's online account management system. While they couldn't bypass the 2FA, the attacker exploited the system by sending a large number of SMS verification requests, resulting in substantial costs for the provider.

14. Endless OTP Exploration

    Real-World Example: In a complex cyber attack on a cryptocurrency exchange, the adversary discovered that the exchange used a simple OTP generation algorithm. The attacker repeatedly tried a limited set of OTPs until one matched, successfully bypassing 2FA.

15. Race Condition Exploitation

    Real-World Example: During a security assessment of an e-commerce platform, a white-hat hacker identified a race condition vulnerability in the 2FA process. By timing their actions precisely, the hacker tricked the system into disabling 2FA for a targeted user account.

16. Remember Me Vulnerabilities

    Real-World Example: An attacker targeted an online banking service with a "Remember Me" feature. They discovered that the feature used easily guessable cookies. By guessing the correct cookie, the attacker gained unauthorized access to user accounts without 2FA.

17. Subdomain Secrets

    Real-World Example: A cybersecurity researcher investigating a popular cloud service provider found that some testing subdomains still used older versions of the platform. These older versions lacked 2FA, providing an opportunity for attackers to bypass security.

18. API Vulnerabilities

    Real-World Example: An attacker examined the API endpoints of a popular social media platform. They discovered that older API versions, located in directories like "/v3/", did not enforce 2FA. The attacker leveraged this vulnerability to bypass 2FA for targeted accounts.

19. Session Management Oversight

    Real-World Example: A software company implemented 2FA for its user accounts but failed to terminate old sessions when users enabled 2FA. An attacker exploited this oversight by accessing an account using an old session that didn't require 2FA verification.

20. Backup Code Conundrum

    Real-World Example: An attacker discovered a vulnerability in a cloud storage service. Through CORS misconfigurations, they were able to access backup codes from the response of the backup code endpoint. With stolen backup codes and knowledge of a user's username and password, the attacker bypassed 2FA.
