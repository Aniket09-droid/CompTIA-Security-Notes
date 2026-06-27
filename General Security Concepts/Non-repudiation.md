Hello everyone..!! Aniket Paul this side. Today is the second day of my cybersecurity journey documentation, here in this document i will talk about the another most important term Non-repudiation used in cybersecurity for maintaining and runs the security policies and methods smoothly.

NON-REPUDIATION :
    Definition:
    Non-repudiation is a security principle that ensures that a person or entity cannot deny performing an action, sending a message, or participating in a transaction. It provides proof of origin and proof of integrity, making actions accountable and legally reliable.

In simple words:
Non-repudiation means that once someone sends a message or performs an action, they cannot later deny doing so because there is reliable evidence to prove it.

Why is Non-Repudiation Important?

Answer : In the digital world, many activities take place online:

    1.Banking transactions;
    2.Email communication;
    3.E-commerce purchases;
    4.Electronic contracts;
    5.Filing taxes online;
    6.Sharing confidential documents;

Without non-repudiation, anyone could simply claim:

    "I never sent that email."
    "I never approved that payment."
    "I never signed that contract."

Non-repudiation prevents such denial by creating verifiable evidence.

Objectives of Non-Repudiation:

    Non-repudiation provides:
    1. Proof of Origin
        It proves who created or sent the message.

        Example:
        Alice sends an email to Bob. The system can prove that Alice was indeed the sender.
    2. Proof of Delivery
        It proves that the recipient received the message.

        Example:
        Bob cannot claim that he never received the document if the system has delivery records.
    3. Accountability
        Every action is linked to a specific user.

        Example:
        An employee approves a financial transaction. Later, they cannot deny their approval because logs and digital signatures provide evidence.

How Non-Repudiation Works:

      Suppose Alice wants to send a message to Bob.

      Step 1: Create Message
        Transfer ₹10,000 to XYZ Company.
        
      Step 2: Digital Signature
        Alice signs the message using her private key.

      Step 3: Send Message
        The signed message is sent to Bob.

      Step 4: Verification
        Bob uses Alice's public key to verify:
            The message came from Alice.
            The message has not been altered.

        Thus, Alice cannot later deny sending the message.

Mechanisms Used to Achieve Non-Repudiation:

    1. Digital Signatures:
      Digital signatures are the most common method for providing non-repudiation.
        They provide:

            Authentication;
            Integrity;
            Non-repudiation;
      Example:

          When you digitally sign a PDF contract, there is cryptographic proof that you signed it.

      You cannot later say:
          "I never signed that document."

      2. Public Key Infrastructure (PKI):

         PKI uses:

            Public keys;
            Private keys;
            Digital certificates;
            Certificate Authorities (CA);

         These components verify identities and establish trust.

      3. Digital Certificates

          Certificates issued by trusted Certificate Authorities bind a public key to an individual or organization.

            Examples:

              SSL/TLS certificates;
              Employee identity certificates;

          These certificates help prove ownership and authenticity.

      4. Audit Logs:

          Systems maintain records of activities such as:

            Login times;
            File access;
            Transactions;
            User actions;

          These logs provide evidence when disputes arise.

            Example:

              An administrator deletes a file.
                  Audit logs record:
                  Username;
                  Date;
                  Time;
                  IP address;

              Therefore, the administrator cannot deny deleting the file.

      5. Time Stamps:

          Time stamps record the exact date and time when an event occurred.

            They prove:
              When a document was created.;
              When it was signed.;
              When it was received;

Examples of Non-Repudiation:

      Online Banking:
      Suppose you transfer ₹5,000 through internet banking.

    The bank records:

      User ID;
      Date and time;
      IP address;
      OTP verification;
      Transaction ID;

    Later, you cannot claim:
      "I never made this transaction."
      The records provide evidence.

      Email Communication
      A company executive sends approval for a project.

    The email server maintains:

      Sender details;
      Time stamps;
      Message headers;

    Thus, the sender cannot deny sending the email.

  
Electronic Contracts:

Two companies sign a contract electronically.

Digital signatures and certificates prove:
Who signed it.
When it was signed.

Neither party can later deny the agreement.

E-Commerce:

When purchasing a product online:
Order records are stored.
Payment receipts are generated.
Confirmation emails are sent.
These serve as evidence of the transaction.

Advantages of Non-Repudiation:

    Provides accountability;
    Prevents fraud;
    Supports legal evidence;
    Protects electronic transactions;
    Builds trust in digital communication;
    Helps investigate incidents;
    Essential for e-commerce and banking systems;

Real-Life Analogy:

    Imagine signing a paper contract.

    Your signature proves that:

    You read the agreement.
    You accepted the terms.

    Later, you cannot simply say:

    "I never signed this contract."

    Similarly, in cybersecurity, digital signatures, certificates, and logs act as electronic evidence, ensuring that users cannot deny their actions.
