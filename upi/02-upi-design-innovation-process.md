# UPI Through Design Innovation Process Lens (NIFT Focus)

This file reframes UPI from history/tech into PROCESS your faculty grades: how designers would have done it.

## 1. Empathize / Discover - User + Context Insights
- Cash pain 2014-16: 86% currency Rs500/1000, queues, POS Rs8000 + 2% MDR unaffordable for kirana, IFSC+account+MMID typing fails low-literacy.
- Field truths: chai stall no screen-check in noise, feature phones 400M+, 13 langs, women/shared phones, migrant SIM change, merchant fear screenshot fraud.
- Methods to cite: shadowing kirana, journey mapping cash, pain-point clustering (cost, typing, trust, language, network).
- Insight statement: Users don't want payments app, they want 10-sec confirmed handover with zero hardware.

## 2. Define - HMW + Design Brief
- HMW: enable any Indian with any phone to pay any merchant with zero extra hardware and instant trust?
- Constraints: RBI security 2-factor, banks keep accounts, works offline/GSM, interoperable not walled, frugal subsidy.
- Success metrics defined early: <30 sec TAT, <Rs10 acceptance cost, works *99# voice, name-check before PIN.
- Ecosystem problem not product: unbundle account (bank) from experience (PSP app).

## 3. Ideate - Principles (say these as innovation)
1. Protocol not product: open API VPA/QR/Intent anyone builds on (vs Visa toll/wallets lock).
2. Decoupling: Mapper VPA>Account hides IFSC, Intent deep-link any app.
3. Frugal acceptance: Rs10 QR print = terminal, Soundbox Rs150/mo = confirmation screen.
4. Trust-by-design: payee-name display, 2-factor SIM+PIN/bio, 90-sec retry not spin, pre/post Autopay alerts, ODR TCC/RET.
5. Inclusion first: *99# USSD, 123Pay IVR/missed/sound, Lite offline, HelloUPI voice, Circle delegation 15k/mo.

## 4. Prototype - Build on Rails, Pilot Small
- Reuse IMPS 2010 rails + NFS switch + ISO messaging, add Mapper + Switch + Common Library HSM.
- Prototypes: 17 bank apps closed Oct-2015-Apr-2016, pilot 21 banks 11-Apr-2016, BHIM as reference app for lagging banks, BharatQR extensible fields UPI+Aadhaar+IFSC.
- DFM equivalent: minimal dot - QR sticker + silent SMS bind + 4-digit PIN, no POS/NFC needed v1.
- Test with extremes: feature phone, no-data basement (later LiteX NFC), noisy bazaar (Soundbox TTS 11 langs).

## 5. Test / Validate - Stress + Iterate
- Demonetization 08-Nov-2016 live stress +600% Dec: exposed switch flood -> led to Aug-2025 API caps (balance 50/day, autopay non-peak, status 3/2hr 90-sec).
- UPI 2.0 16-Aug-2018: OD link, mandate block-funds, invoice inbox, signed intent anti-tamper from merchant feedback.
- Failure design: pending > check 3x > refund 1hr > UPIHelp ODR, deemed acceptance 15-Feb-2025 + penalty.
- Metrics: 1.78Cr FY17 > 24162Cr FY26, 12B Jan-24 > 24.51B Aug-26, 86% tickets <Rs500 inclusion proof.

## 6. Implement / Orchestrate - Ecosystem as Design Material
- Roles designed: RBI regulator, NPCI Sec-8 switch, Issuer debit, Acquirer credit, PSP pipes, TPAP UX, merchants QR.
- Incentive design: zero-MDR law 10A/269SU Jan-2020 + subsidy FY22 1389Cr FY24 3631Cr FY25 1500Cr Rs0.06/txn -> 15-Sep-2026 OC237 MDR 0.4% >Rs2000 eff 15-Oct-2026 customer free (sustainability pivot to cite).
- Governance: 30% TPAP cap to Dec-2026, steering Asbe+Rajola 22 members, DPIP Smart Registry 01-Sep-2026 8 banks salted-hash + AI score Phase2.
- Service blueprint: front (app/QR/Soundbox) / back (Mapper/Switch/CBS/RBI net T+0) / support (labs, seed, dispute, fraud 1930).

## 7. Scale / Evolve - Platform Extensions (same QR)
- Lite 5k/1k no PIN clean passbook > LiteX NFC offline 500/txn
- Autopay mandate 15k auto 1L MF/Ins/CC > Circle full/partial
- Credit: RuPay CC P2M nil to 2k + pre-sanctioned line any app
- Global NIPL 11 + remittance PayNow/TIPS/Nexus + export stacks Peru/Namibia
- UPI ATM ICCW scan-cash no skimming + CBDC interoperable one QR two monies
- Voice HelloUPI BillPay IoT Tap wearables car fridge Circle devices

## 8. What to say as Designer (jury lines)
- We didn't design app UI, we designed protocol + trust + inclusion + incentives.
- Innovation = decoupling + frugal touchpoint + audible confirmation + vernacular voice + delegation.
- If trust is product, switch + Soundbox + name-check is interface.
- Next: one dashboard Apply>Pay>Autopay>Dispute, plain cards, one Soundbox all QRs, wait-tracker, starter packs.

Use each numbered head as one board column: Insight > HMW > Principle > Prototype > Test > Orchestrate > Scale.
