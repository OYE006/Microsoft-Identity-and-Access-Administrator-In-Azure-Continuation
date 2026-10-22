# Microsoft-Identity-and-Access-Administrator-In-Azure-Continuation

## Part 4: Configuring external collaboration settings

### Enabling Guest Users to perform self service sign-up

  - Sign in to Microsoft Entra admin center at https://entra.microsoft.com as Global Administrator.
  - In the left navigation menu, under Entra ID, select Users
  - Then select User Settings.
  - Scroll down and select manage external user collaboration settings.
  - Ensure that YES is marked for the setting Enable guest self-service sign up via user flows.

    <img width="776" height="425" alt="image" src="https://github.com/user-attachments/assets/cfd35d63-979b-4d2f-9a67-949455fa033a" />

  - Select Save at the top of the screen.

### Configuring external collaboration settings

  - In the left navigation menu, under Entra ID, select External Identities, and then select All identity providers.

    <img width="788" height="431" alt="image" src="https://github.com/user-attachments/assets/e2d687fa-fcbb-4be3-92fa-c703c6459a18" />
    
  - Select the Email one-time passcode item in the list of providers, then select Configured.

    <img width="786" height="355" alt="image" src="https://github.com/user-attachments/assets/3b932707-c600-47a6-b1cf-14456f7f5855" />

    > A one-time passcode is a very secure way to invite a user to join your organization.
  
  - Ensure that Yes is selected and save if needed.
  - Return to the External Identities menu and select External Collaboration Settings on the left.
  - Under Guest user access, review access levels that are available and then select Guest user access is restricted to properties and memberships of their own directory objects (most
    restrictive).
  - Under Guest invite settings, select Member users and users assigned to specific admin roles can invite guest users including guests with member permissions!

    <img width="786" height="436" alt="image" src="https://github.com/user-attachments/assets/679331b0-a903-4dcc-a736-b123275fd976" />

  - Under Collaboration restrictions, review the available options and accept the default settings.
  - Select Save at the top of the screen.

## Part 5: Adding guest users to the directory

 ### Adding a guest user
  - Sign in to Microsoft Entra admin center.
  - In the left navigation, under Entra ID, select Users, then select All users.
  - Select New user and on the New user menu, select "Invite external user" and add guest user information.

    <img width="779" height="420" alt="image" src="https://github.com/user-attachments/assets/ae02432b-fee7-45a2-bd0f-df3557748fc9" />
