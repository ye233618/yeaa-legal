# Y.EAA Privacy Policy

*Last updated: February 26, 2026*

Y.EAA is a Chrome browser extension operated by the Y.EAA developer. This policy describes how we collect, use, and protect your information.

## 1. Information We Collect

- **Account information**: When you sign in with Google, we receive your email address and display name from Google OAuth. We do not access your Google password.
- **Resume data**: When you upload a resume, we extract and store its contents (name, work history, education, skills) to assist with completing application forms.
- **Job application data**: We record which jobs you have applied to, form answers generated during applications, and application status.
- **LinkedIn page content**: Our content script runs on LinkedIn job application pages (linkedin.com/jobs) to read form field labels and structure to determine what information to fill. We do not scrape or store LinkedIn profile data beyond what is needed to complete the current form.
- **Usage data**: We track application counts for credit management. We do not track browsing history, keystrokes, or activity outside of the extension's job application features.

## 2. How We Use Your Information

- To assist users in completing job application forms using AI-generated suggestions based on their profile data
- To track your application history
- To authenticate your account and manage usage credits

We process your data based on your consent (by installing and using the extension) and contractual necessity to provide the service.

## 3. Data Storage and Security

- All data is stored in Google Cloud Firestore, hosted in the United States, operated by Google Cloud Platform.
- All data transmission between the extension and our server uses HTTPS encryption.
- Direct client access to the database is denied by security rules; all data access is authenticated and routed through our backend server.
- OAuth tokens are used transiently for authentication and are not stored permanently on our servers.
- **Cross-border processing**: Your data may be transferred to and processed in the United States, where our servers are hosted. By using Y.EAA, you consent to this transfer.

## 4. Data Sharing

- We do **not** sell, rent, or trade your personal information to third parties.
- We do **not** use your data for advertising or marketing purposes.
- We do **not** share your data with data brokers, analytics companies, or credit agencies.
- Your resume data and form context are transmitted to Google Gemini API solely to generate suggested form answers (see Section 6). We rely on Google's contractual commitments that API-submitted data is not used to train their foundational AI models.

## 5. Data Retention and Deletion

- Your profile and application data are retained as long as your account is active.
- Accounts inactive for more than 180 days may have their data automatically deleted.
- Backup systems may retain data for up to 30 additional days after deletion.
- Temporary operational data (such as rate-limiting records) is automatically deleted via TTL policies.
- You may request deletion of all your data at any time by contacting us at the email below. We will process deletion requests within 30 days.

## 6. Third-Party Services

These third-party providers may process data on our behalf:

- **Google Firebase**: Used for user authentication (Firebase Auth) and data storage (Cloud Firestore). Subject to [Google's Privacy Policy](https://policies.google.com/privacy).
- **Google Cloud Run**: Hosts our backend server. Subject to [Google Cloud Terms of Service](https://cloud.google.com/terms).
- **Google Gemini API**: Used to process your resume data and job form context to generate suggested answers. Data is sent via authenticated API calls. Subject to [Google's API Terms of Service](https://ai.google.dev/gemini-api/terms).

## 7. Children's Privacy

Y.EAA is not intended for use by individuals under the age of 16. We do not knowingly collect information from children.

## 8. Changes to This Policy

We may update this policy from time to time. Changes will be posted at this URL with an updated "Last updated" date.

## 9. Contact

For privacy inquiries or data deletion requests, contact: yeaanyc@gmail.com
