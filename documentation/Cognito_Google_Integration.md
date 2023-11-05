# Minimal Google integration with Cognito

## Cognito User Pool Creation

Step 1: Configure Sign In Experience

- We can use Email only login for our application.

Step 2: Configure security requirements

- We can use default setting for password policy.
- We can disable MFA for our application.

Step 3: Configure security requirements

- We can add email and verified email as required attributes.

Step 4: Configure message delivery

- We can use send email with Cognito option.

Step 5: Integrate your app

- Set a user pool name.
- Check the use the Cognito hosted UI.
- We will use a Cognito domain name.
- We need to create public client.
- Use jwt.oi as callback URL.
- For the starters we can use Implicit grant flow.
- For OpenID connect scopes remove phone and add Profile.

After this we will see the created user pool.


