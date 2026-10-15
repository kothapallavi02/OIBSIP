# Social Engineering Attacks: Phishing, Pretexting, and Baiting
**Submitted by:** Kotha Pallavi  
**Track:** Security Analyst / Cybersecurity  
**Task:** Task 5 — Research Report: Social Engineering Attacks  
**Date:** October 2026

## Abstract
Social engineering is a cybersecurity technique in which attackers manipulate people into revealing information, granting access, or taking actions that benefit the attacker. This report focuses on phishing, pretexting, and baiting. It explains common attack types, the psychological methods used, documented examples, and practical prevention measures. The Anti-Phishing Working Group (APWG) observed 1,003,924 phishing attacks in the first quarter of 2025, showing that phishing remains a significant threat. The report recommends combining employee awareness, verification procedures, multi-factor authentication (MFA), technical controls, and clear incident-reporting processes.

**Keywords:** Social engineering, phishing, spear phishing, whaling, smishing, vishing, pretexting, baiting, cybersecurity.

## 1. Introduction
Organizations use technology to communicate, store data, and manage money. Attackers do not always need to break technical protections directly; they may instead manipulate a person into opening a malicious attachment, sharing a password, approving a login, or transferring money. Social engineering is effective because it targets human trust, helpfulness, fear, curiosity, and the desire to respond quickly.

APWG reported 1,003,924 phishing attacks in Q1 2025. It also reported that online payment and financial sectors together accounted for 30.9% of attacks in that quarter. These figures represent attacks observed by APWG and should not be interpreted as every phishing incident worldwide. [1]

## 2. What Is Social Engineering?
Social engineering is the deliberate manipulation of people to make them reveal confidential information or perform actions that weaken security. An attacker may pretend to be a colleague, manager, bank employee, technical-support worker, delivery company, or government official.

Common psychological techniques include:
- **Urgency:** Pressuring a person to act immediately.
- **Authority:** Pretending to be a manager or official.
- **Fear:** Threatening account closure, legal trouble, or financial loss.
- **Curiosity or reward:** Offering a prize, download, or interesting file.
- **Helpfulness:** Encouraging a person to connect a found USB drive or help a supposed colleague.
- **Trust and familiarity:** Using names, logos, job titles, or details gathered from public sources.

## 3. Phishing

### 3.1 Definition and How It Works
Phishing is a form of social engineering in which an attacker impersonates a trusted source through email, text messages, phone calls, social media, messaging apps, or QR codes. The aim may be to steal login details, obtain financial information, deliver malware, or persuade a victim to send money.

A typical attack follows these stages:
1. The attacker chooses a target and prepares a believable message.
2. The message is delivered by email, SMS, phone call, or another channel.
3. The message creates urgency, fear, curiosity, or trust.
4. The victim clicks a link, opens a file, shares credentials, provides an OTP, or approves a payment.
5. The attacker uses the access or information for fraud, data theft, or further attacks.

### 3.2 Types of Phishing
- **Spear phishing:** A personalized message aimed at a particular person or team.
- **Whaling:** A targeted phishing attempt against senior executives or other high-value individuals.
- **Vishing:** Phishing carried out through voice calls or voice messages.
- **Smishing:** Phishing delivered through SMS or text messages.
- **Email phishing:** Fraudulent emails sent to many recipients, often impersonating a known service.
- **QR-code phishing (quishing):** A QR code sends the user to a fraudulent website.
- **Business Email Compromise (BEC):** An attacker impersonates or compromises a trusted business email account to request money or sensitive information.

### 3.3 Real-World Case Study: Twitter, July 2020
In July 2020, attackers used phone-based social engineering against a small number of Twitter employees. According to Twitter’s public incident update, the attackers manipulated employees and obtained credentials that enabled access to internal support tools. The incident affected 130 accounts; attackers could take over 45 accounts to reset passwords, log in, and post tweets. High-profile accounts were used to promote a cryptocurrency scam. [2]

**Lessons learned:**
- Employees must verify unexpected IT-support calls through a trusted internal channel.
- Access to account-management tools should be restricted and monitored.
- MFA is important, but organizations must also protect recovery workflows, internal tools, and employee credentials.
- Employees need an easy way to report suspicious calls and messages.

### 3.4 Four Phishing Prevention Recommendations
1. **Verify before acting:** Do not use links or phone numbers included in suspicious messages. Visit the official website or contact the organization using a known, trusted channel.
2. **Protect credentials:** Never share passwords, PINs, or OTPs. Use unique passwords and enable MFA, preferably with a security key or authenticator method where available.
3. **Use technical protections:** Apply email filtering, web protection, endpoint security, and timely software updates.
4. **Report quickly:** Report suspicious messages or calls to the organization’s security team or platform. If credentials were entered, change them from a trusted device and revoke other sessions where possible.

## 4. Pretexting

### 4.1 Definition
Pretexting is a social engineering method in which an attacker invents a believable story or identity to persuade someone to disclose information or perform an action. The attacker may pretend to be a bank representative, HR employee, supplier, police officer, manager, or IT-support agent. The story may be prepared using information found on public websites or social media.

### 4.2 How a Pretext Is Built
1. The attacker selects a role that the victim is likely to trust.
2. The attacker creates a plausible reason for contacting the victim.
3. The attacker uses personal or organizational details to sound genuine.
4. The attacker asks for information, access, a payment, or a change to a process.
5. The attacker uses the victim’s response to commit fraud or gain access.

### 4.3 Real-World Case Study: Ubiquiti Networks, 2015
Ubiquiti Networks disclosed in a U.S. Securities and Exchange Commission filing that it had been affected by business email compromise fraud involving employee impersonation and fraudulent requests targeting its finance department. The fraud resulted in transfers totaling approximately US$46.7 million to overseas accounts. The company reported that some funds were recovered. [3]

This case illustrates how a false identity and a believable business request can bypass normal judgement and payment controls. It is an example of impersonation-based business email compromise; it should not be assumed that every detail of the incident was publicly established as a single pretexting conversation.

### 4.4 Three Pretexting Prevention Measures
1. **Independently verify identity:** Call the person using a trusted directory number or confirm in person. Do not rely on the contact details supplied in the request.
2. **Require dual approval:** Use documented approval and a second-person review for payments, bank-account changes, sensitive data requests, and privilege changes.
3. **Minimize information exposure:** Share sensitive information only with authorized people, and avoid posting internal processes, staff details, or travel information publicly.

## 5. Baiting

### 5.1 Definition
Baiting is a social engineering technique that offers something tempting to encourage a person to take an unsafe action. Physical baiting may involve a USB drive left in a public place. Digital baiting may involve fake software, pirated media, game cheats, free downloads, or files advertised as valuable. The bait may lead to malware installation, credential theft, or unauthorized access.

### 5.2 Physical and Digital Baiting
- **Physical baiting:** A person finds a USB drive labelled “Salary,” “Exams,” or “Confidential” and plugs it into a computer out of curiosity or to identify its owner.
- **Digital baiting:** A website offers a free tool or file that is actually malicious, or tricks a user into disabling security protections to install it.

### 5.3 Documented Research Case Study: Dropped USB Drives
Researchers from the University of Illinois at Urbana–Champaign and collaborating institutions published a 2016 study titled *Users Really Do Plug in USB Drives They Find*. In a controlled experiment, researchers dropped 297 USB drives around a university campus. They estimated a success rate of 45–98% for drives being picked up and connected, with the first drive connected in less than six minutes. The research used files designed to measure access without executing unexpected code on participants’ computers. [4]

The study demonstrates that curiosity and the desire to return a found item can lead people to connect unknown devices. It was a controlled research experiment, not evidence that every found USB drive contains malware.

### 5.4 Three Baiting Prevention Measures
1. **Never connect unknown devices:** Give found USB drives to the organization’s IT or security team. Do not plug them into personal or work computers.
2. **Download from trusted sources:** Use official websites and approved software stores. Avoid cracked software, suspicious attachments, and offers that require disabling security tools.
3. **Apply device controls:** Organizations should restrict unauthorized USB storage, use endpoint protection, and train staff on how to report suspicious devices or downloads.

## 6. Quid Pro Quo (Bonus Topic)
Quid pro quo means “something for something.” In this attack, the attacker offers a service, benefit, or help in exchange for information or access. For example, a caller may pretend to provide technical support and ask the user to reveal a password or install remote-access software.

**Prevention:**
- Verify support staff through official internal channels.
- Never disclose passwords or OTPs to receive technical help.
- Install remote-access tools only when approved by the organization and initiated through its documented support process.

## 7. Comparison Table

| Attack type | Primary target | Psychological lever exploited | Best countermeasure |
|---|---|---|---|
| Phishing | Email, messaging, or online-service users | Urgency, fear, trust, curiosity | Verify links and requests; MFA; report suspicious messages |
| Spear phishing | A selected employee or team | Personalization and familiarity | Verify unusual requests through a separate channel |
| Whaling | Executives or senior staff | Authority and business pressure | Executive awareness and independent approval |
| Vishing / smishing | Phone and text-message users | Urgency and fear | Call back using an official number; do not share OTPs |
| Pretexting | Employees, customers, finance or support staff | Trust, authority, plausible stories | Verify identity and require dual approval |
| Baiting | People tempted by a device, file, or free offer | Curiosity, reward, helpfulness | Never use unknown devices; download only from trusted sources |
| Quid pro quo | Users seeking help or a benefit | Reciprocity and helpfulness | Use approved support channels and never share credentials |

## 8. Organisational Recommendations: Five-Point Employee Awareness Checklist
1. **Pause and inspect:** Check unexpected messages, links, attachments, QR codes, and requests for sensitive information.
2. **Verify identity separately:** Use a known phone number, official directory, or trusted internal channel.
3. **Protect access:** Use unique passwords, MFA, approved devices, and least-privilege access.
4. **Follow payment and data procedures:** Confirm supplier bank changes and unusual transfers independently; require dual approval where appropriate.
5. **Report without delay:** Report suspicious messages, calls, USB devices, downloads, or accidental disclosure. Preserve evidence and follow the incident-response process.

Organizations should reinforce this checklist through regular training, simulated exercises conducted with authorization, secure email and endpoint controls, clear reporting channels, and lessons learned from incidents. Training should encourage reporting rather than blame employees for mistakes.

## 9. What to Do if an Attack May Have Succeeded
- If a password was entered on a suspicious page, change it from a trusted device, change it anywhere it was reused, enable MFA, and sign out other sessions if possible.
- If an unexpected file was opened or installed, disconnect the affected device from the network if instructed by the organization’s incident procedure and contact IT/security support promptly.
- If money was transferred or banking information was exposed, contact the bank or payment provider immediately through an official channel.
- Preserve screenshots, message headers, sender details, timestamps, and transaction references. Do not forward malicious links to others.
- In India, suspected cybercrime can be reported through the National Cyber Crime Reporting Portal at https://cybercrime.gov.in/. For financial cyber fraud, contact the national helpline at **1930** as quickly as possible.

## 10. Conclusion
Phishing, pretexting, and baiting exploit human trust rather than relying only on technical weaknesses. Phishing uses deceptive communications; pretexting builds a false identity or scenario; baiting offers something tempting to encourage unsafe behaviour. Documented incidents and research show that these methods can cause account compromise, financial loss, and organizational disruption. Effective defence requires both people and technology: verify identities independently, protect credentials with MFA, follow payment approvals, avoid unknown devices and downloads, keep systems protected, and report suspicious activity quickly.

## 11. References
1. Anti-Phishing Working Group (APWG), *Phishing Activity Trends Reports*, Q1 2025 summary. https://apwg.org/trendsreports
2. Twitter, *An update on our security incident*, July 18, 2020; updated July 30, 2020. https://blog.x.com/en_us/topics/company/2020/an-update-on-our-security-incident
3. U.S. Securities and Exchange Commission, Ubiquiti Networks, Form 8-K, “Business Fraud,” August 2015. https://www.sec.gov/Archives/edgar/data/1511737/000157104915006288/t1501817_8k.htm
4. Tischer, M. et al., *Users Really Do Plug in USB Drives They Find*, 2016 IEEE Symposium on Security and Privacy. University of Illinois research record: https://experts.illinois.edu/en/publications/users-really-do-plug-in-usb-drives-they-find/
5. Cybersecurity and Infrastructure Security Agency (CISA), *Secure Our World: Recognize and Report Phishing; Use Strong Passwords; Turn on MFA*. https://www.cisa.gov/secure-our-world
6. Government of India, *National Cyber Crime Reporting Portal*. https://cybercrime.gov.in/
