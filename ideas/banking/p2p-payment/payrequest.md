# PayRequest: casual peer-to-peer payment requests

An idea for a frictionless “pay a friend” request service in Iran, inspired by Tikkie and other instant-permissioned bank payment apps.

## 1. Title
PayRequest – peer-to-peer payment requests without IBAN guesswork

## 2. Author
- Author: Sina Khorrami
- Background: software architect and enthusiast with deep experience in secure, scalable software systems, distributed architecture, and API platforms
- Contact: [LinkedIn](https://www.linkedin.com/in/sina-khorrami/)

## 3. Abstract
QuickMoney Iran is a mobile/web service that simplifies casual payments between friends, family, and small vendors by removing the need to share IBANs. Users send a link/QR code or username request; the receiver accepts and confirms a linked bank account. Fund transfer happens through interbank API orchestration and existing digital banking rails.

## 4. Why It’s Interesting
- Why now: Iranian digital wallets and open banking are growing, but peer-to-peer casual payments are still clunky and error-prone.
- Why Iran: traditional IBAN-based transfers require too many manual steps; people prefer launching one shared request from chat and paying in 1 tap.
- Expected impact:
  - reduce P2P transfer setup effort by 80%
  - lower failed transfers, wrong-account sends, and reconciliation overhead
  - boost e-commerce micro-transactions and local economy (delivery, freelancers, school groups)
  - improve transparency and trust with receipts, confirmations, and optional social split-bills

## 5. Approach
- Phase 1 (0-4 months): build the product concept with banks and fintech APIs; design ID+phone/email -> bank account resolution flow with user consent.
- Phase 2 (4-8 months): launch MVP with a provider bank and 2 partner banks; support payment link+QR+chat deep link.
- Phase 3 (8-14 months): integrate with major banking apps; add group payments, IOU split, recurring casual transfers.
- Phase 4 (14+ months): national exchange between all bank channels; loyalty/tax reporting APIs; international remittance support.
- Security:
  - user authentication via national digital identity / bank SSO,
  - per-request token, encrypted link,
  - fraud detection for transaction-splitting abuse,
  - audit and dispute resolution.
- UX:
  - create/send request in 10s,
  - accept with one tap from notifications,
  - automatic payer details verification,
  - built-in split bill template and history.

## 6. Help Needed
- Talent: API engineers, mobile product designers, bank integration specialists, compliance/legal.
- Funding: initial seed from e-pay fintech VC or joint bank fund.
- Data: access to open banking APIs, customer onboarding data (KYC/phone) with privacy safeguards.
- Partnerships:
  - major banks (Mellat, Melli, Saderat, etc.)
  - PSPs, shoras, e-wallet operators
  - layering with national identity and payment infrastructure (Shaparak, Shetab)

## 7. Supporting Material (recommended)
- Benchmarks (most used / important):
  - Tikkie (Netherlands) — link/QR payment requests by bank app.
  - Swish (Sweden) — national phone/QR P2P requests, bank-built infrastructure.
  - Zelle (USA) — bank network instant requests by phone/email.
  - PayNow (Singapore) — phone/NRIC/QR pay request and collect via central registry.
  - UPI (India, via Google Pay/PhonePe/Paytm) — instant request and collect across banks (massive scale).
- Links:
  - Tikkie: https://www.tikkie.me/
  - Swish: https://www.getswish.se/
  - Zelle: https://www.zellepay.com/
  - PayNow: https://www.abs.org.sg/
  - UPI (NPCI): https://www.npci.org.in/what-we-do/upi/product-overview
  - Open Banking standard
  - Chrome/WhatsApp payments user flows
- Visuals:
  - request flow diagram (sender link -> receiver confirm -> bank transfer)
  - fallbacks for non-user, recipient bank not integrated
  - timeline (pilot, scale, API federation)
- Video idea:
  - 90-second demo of bill splitting at coffee shop: “get paid without asking for IBAN”.
