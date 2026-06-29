Authentication, Authorization, and Accounting (AAA)

Introduction :

    AAA (Authentication, Authorization, and Accounting) is a security framework used to control access to computer systems, networks, applications, and data. It ensures that only authorized users can access resources and that their activities are properly monitored and recorded.

AAA is widely used in:

     1. Network security;
     2. Operating systems;
     3. Cloud computing;
     4. Banking systems;
     5. Enterprise environments;
     6. Cybersecurity operations;

The three components of AAA are:

    1. Authentication – Who are you?
    2. Authorization – What are you allowed to do?
    3. Accounting – What did you do?

1. Authentication :
     Meaning:

       Authentication is the process of verifying the identity of a user, device, or system before access is granted.

        It answers the question:

            "Who are you?"

        Before a user enters a system, the system must verify that the user is genuine.

Purpose of Authentication :

    The main objectives are:

      Verify identity;
      Prevent unauthorized access;
      Protect sensitive information;
      Establish trust between user and system;

Factors of Authentication : 

    Authentication generally uses one or more of the following factors:
      A. Something You Know:
            Information known only to the user.

         Examples:
            Password;
            PIN;
            Security question;

         Example:
            ATM PIN;

       B. Something You Have :
            A physical object possessed by the user.

          Examples:
              Smart card;
              Security token;
              Mobile phone receiving OTP;

          Example:
              OTP received during online banking.

        C. Something You Are
            Biometric characteristics unique to the user.

           Examples:
                Fingerprint;
                Face recognition;
                Retina scan;
                Voice recognition;

           Example:
                Unlocking a smartphone with a fingerprint.

Types of Authentication:

    A.Single-Factor Authentication (SFA):
      Uses only one factor.

      Example:
          Username + Password

      Advantages:
          Simple

      Disadvantage:
          Less secure

    B.Multi-Factor Authentication (MFA):
      Uses two or more factors.

      Example:
          Password + OTP
          Fingerprint + PIN

        Advantages:
            More secure

        Disadvantage:
            Slightly more complex

    Example of Authentication:
      A student logs into a university portal.

        Steps:
          Enter username.
          Enter password.
        System verifies credentials.

        If correct:
          Authentication successful.

        If incorrect:
          Access denied.

Importance of Authentication :

    Protects systems from attackers;
    Prevents identity theft;
    Secures confidential information;
    Forms the first line of defense;

2. Authorization :

       Meaning:
         Authorization determines what actions an authenticated user is permitted to perform.
   
       It answers the question:
          "What are you allowed to do?"

         Authentication occurs first, then authorization.
   
       Purpose of Authorization:
         Authorization ensures that users can access only the resources necessary for their role.

       How Authorization Works:

          After successful authentication:
            System checks user role;
            Permissions are evaluated;
            Appropriate access is granted;

        Example:
          Consider a college management system.

        Student
          Can:
            View marks;
            Download assignments;

          Cannot:
            Modify marks;
            Add students;

         Teacher
           Can:
             Upload marks;
             Manage attendance;

           Cannot:
              Change administrator settings

          Administrator
            Can:
              Create accounts;
              Modify system settings;
              Manage users;
   
         Types of Authorization Models:
             A. Role-Based Access Control (RBAC):
                Permissions depend on user roles.

                Examples:
                  Student;
                  Teacher;
                  Manager;
                  Administrator;
                  Most organizations use RBAC.
   
              B. Mandatory Access Control (MAC):
                 Access is controlled by strict security policies.

                 Common in:
                   Military;
                   Government agencies;

               C. Discretionary Access Control (DAC)
                  Resource owners decide who can access their files.

                  Example:
                    File sharing permissions;

       Importance of Authorization:
        Prevents unauthorized activities;
        Protects sensitive resources;
        Enforces security policies;
        Reduces insider threats;

3. Accounting :

       Meaning:
        Accounting is the process of recording, monitoring, and tracking user activities within a system.

         It answers the question:
          "What did you do?"
           Accounting creates logs and records for future review.

       Purpose of Accounting:
        Accounting helps organizations:
          Track user actions;
          Detect suspicious activities;
          Investigate incidents;
          Maintain compliance;
          Generate reports;

        Example:
          Suppose an employee logs into a company server.
            Accounting records:
              Username: John;
              Login Time: 9:00 AM;
              Logout Time: 5:00 PM;
              Files Accessed;
              Changes Made;
          These records are stored in logs.

Conclusion:

      AAA is one of the most important concepts in cybersecurity. It provides a structured approach to controlling access and monitoring user activities.

      Authentication verifies identity.
      Authorization determines permissions.
      Accounting records actions.
    
    Easy Memory Trick:
      AAA = Authentication + Authorization + Accounting
      Authentication → Who are you?
      Authorization → What can you do?
      Accounting → What did you do?
