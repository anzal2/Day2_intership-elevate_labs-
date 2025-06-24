# Day2_intership-elevate_labs-
Awareness of phishing tactics and email threat analysis skills.



📧 Sample Phishing Email (Example)
Subject: 🔒 Urgent Account Alert: Your Bank Account Has Been Locked!
From: support@bankofamerica-secure.com
Body:
     Dear Customer,
     We have noticed suspicious activity in your Bank of America account. For your protection, your account has been temporarily locked.
     Please verify your identity immediately by clicking the link below:
Verify Now
Failure to do so within 24 hours will result in permanent suspension of your account.

Thank you,
Bank of America Security Team

🔍 Step-by-Step Analysis:
1. Examine Sender's Email Address for Spoofing
Email shown: support@bankofamerica-secure.com
Spoofing sign: This is not a legitimate domain. Real emails would come from something like @bankofamerica.com. Phishers often use lookalike domains.

2. Check Email Headers (using tools like Google’s header analyzer)
Discrepancies found:
Return-Path differs from sender email.
Reply-To is a suspicious Gmail or unrelated domain.
Sent from IP address registered to a non-US server (phishing emails often come from unusual geolocations).

4. Identify Suspicious Links or Attachments
Link: Verify Now (http://secure-bofa-account-checker.com/login)
Suspicious sign: The domain is clearly not Bank of America's. It's trying to look similar but redirects to a phishing site.

4. Urgent or Threatening Language
Phrases like:
“Your account has been locked!”
“Failure to do so within 24 hours will result in permanent suspension”
This plays on fear to provoke immediate action.

5. Mismatched URLs
Hovering the link shows http://secure-bofa-account-checker.com, but the visible text may just say "Verify Now" — classic mismatch technique.

6. Spelling or Grammar Errors
Minor grammar issues:
“Thank you, Bank of America Security Team” — missing comma after “Thank you”
“verify your identity immediately” — overly robotic tone.
Phishing emails often have awkward phrasing or formatting.
