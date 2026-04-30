---
country: Colombia
document_name: High Level Analysis for Colombia Regulated Market Casino Compliance
source_file: High Level Analysis for Full Solution for Columbia_Betway v2.0 (with complete Financial Considerations).pdf
extracted_date: 2026-04-30
jurisdiction: Colombia
---

# High Level Analysis for Colombia Regulated Market Casino Compliance

Error! No text of specified style in document. Page | 2 of 12

## Contents

- FINANCIAL CONSIDERATIONS ............................................................................................................ 3
- LEGISLATION ................................................................................................................................ 3
- CAPEX AND SITE COSTS .............................................................................................................. 4
- OPEX .......................................................................................................................................... 4
- OPERATIONAL REQUIREMENTS ......................................................................................................... 5
- REGISTRATION ............................................................................................................................. 5
- EXTERNAL REGISTER CHECKS....................................................................................................... 6
- PLAYER JOURNEY ......................................................................................................................... 6
- BANKING ...................................................................................................................................... 6
- BACKOFFICE UPDATES .................................................................................................................. 7
- LAST LOGIN REMINDER .................................................................................................................. 7
- CURRENCIES ................................................................................................................................ 8
- LANGUAGES ................................................................................................................................. 8
- DOMAIN........................................................................................................................................ 8
- TERMS AND CONDITIONS ............................................................................................................... 8
- PLAYER PROTECTION CONTENT .................................................................................................... 8
- RESPONSIBLE GAMING & SELF RESTRICTION REQUIREMENTS ......................................................... 9
- LIMITS ...................................................................................................................................... 9
- EXCLUSIONS ............................................................................................................................. 9
- SESSION LIMITS ........................................................................................................................ 9
- INACTIVITY TIMEOUT.................................................................................................................. 9
- BET LIMITS ............................................................................................................................. 10
- PLAYER’S CONSENT TO INSTALLATIONS .................................................................................... 10
- GAMES ....................................................................................................................................... 10
- SESSION TIME ............................................................................................................................ 10
- USER ACCOUNT HISTORY (PLAYCHECK AND CASHCHECK) ............................................................ 10
- INSPECTION SYSTEM ................................................................................................................... 11
- SAFE ........................................................................................................................................ 11
- INTEGRITY CHECKER ................................................................................................................... 11
- LOGGING .................................................................................................................................... 11
- PLAYER DEVICES ........................................................................................................................ 11
- INCOMPLETE GAME POP UP ......................................................................................................... 11
- RTP MONITORING ...................................................................................................................... 12
- CERTIFICATION / TESTING ........................................................................................................... 12

Error! No text of specified style in document. Page | 3 of 12

## Financial Considerations

The information below is confidential and has been developed for internal private use. Neither the whole nor any part of the information in this document may be disclosed, used or relied upon by any other person. The material contained below is deemed sensitive in nature.

## Legislation

| Description | Value |
|---|---|
| Status | Regulated - framework completed during 2016 |
| Regulatory Framework | - Legal system based on civil law and under the 1991 constitution, laws are approved by the Colombian Bicameral Congress.<br>- Law 643/2001 is the primary piece of legislation concerning gambling and the government has also issued several decrees to regulate different aspects of the gaming industry. |
| Prohibitions | Article 4 prohibits the sale of “games of chance”:<br>1. To minors or persons who suffer mental illness<br>2. Games:<br>a. where conditions are not displayed to players.<br>b. that affect the health of players.<br>c. related to illicit activities.<br>d. not specifically authorised by Coljuegos. |
| Regulatory Authority & licenses | Law 643/2001 grants the monopoly of gaming activities to the Colombian state. It requires private operators to gain licences (in the form of concession contracts) from the gambling authority, Coljuegos. Concession contracts can be granted for no less than three or more than five years |
| Online games permitted | Acuerdo 4/2016 permits the following games:<br>- Online casino games (roulette, blackjack and baccarat)<br>- Online gaming machines<br>- Bingo<br>- Poker (cash and tournament)<br>- Fixed-odds betting on the result of sports and non-sports related events<br>- Betting exchanges on the result of sports and non-sports related events. |

Error! No text of specified style in document. Page | 4 of 12

| Description | Value |
|---|---|
| Taxation | 15% on gross gaming revenue provided 83% RTP (return to player).<br><br>Annual fixed fee equal to 811 times the Colombian minimum monthly wage (approx.US$175,500).<br><br>Under the scope of the Colombian tax regime, as gambling services are subject to VAT obligations, online gambling operators are required to retain this tax. |
| Server location | The regulator does not require a specific location for the gambling server. However, as part of the technical standards for the operation of online gambling services, operators are required to maintain a data safe in country, which will capture and make available to the gambling authority all game-related information. |

## CAPEX and Site Costs

Columbia requires Tier III Certification from Uptime Institute (ie. concurrently maintainable site infrastructure without any shutdowns for equipment replacement / maintenance). At the moment Continent 8 Technologies (who provide us with this infrastructure) doe not hive this certification and it estimated that we would require a capital investment of €560k (£500k).

## OPEX

| Description | Value |
|---|---|
| Market Entry Costs | Nil |
| Certification | It is estimated that 20 first variant and 20 second variant games will be delivered per anum at a cost of €708 and €587 per game (Total of €25.9k in Year-1) |
| Software Development costs | A more detailed analysis needs to be completed, but given our initial analysis of the legislation and potential development work required we have estimated that a minimum of 122,899 hours will be required (approximately €4m) |
| SAFE | It is assumed that the SAFE will be provided by a third party (eg. MORPHO) and will be an Operator cost. |
| External Production Costs | Nil |

Error! No text of specified style in document. Page | 5 of 12

## Operational Requirements

The list below describes the high level operational requirements which would need to be fulfilled according to Colombian regulation. The list is a guideline and shall not be understood as an exhaustive list which guarantees compliance.

## Registration

A compliant registration is required to be developed. A clear notice must be displayed warning players about the prohibition of underage gambling and the risks of gaming addiction. The message displayed must cover topics including the protection of minors and responsible gambling. Only a single player account is permitted. Only Colombian nationals or foreigners who have a valid immigration cards are permitted to register. Players must be checked against the Operator’s exclusion register at time of registration.

During registration:

- Players must be given an opportunity to set a daily, weekly and/or monthly deposit limit.
- Players must provide the specific information required by the Regulator including:
  - Identification and personal data (identification number, first name, middle name, maiden name, surname, sex, DOB, Place of Birth, date of issue of identification card, place of issue of identification card, expiration of immigration card, nationality, citizenship)
  - Domicile (home address, municipality, postal code, telephone number)
  - Email address
  - Information about “prohibitions of participating in online games”
  - Daily, weekly & monthly limits
- Players must specifically consent to:
  - The use of their personal information in the personal identification systems (driving license databases, etc.) and in exclusion lists.
  - Access by Coljuegos to information on transactions by players for them to carry out transparency and control activities
  - The Operator accessing information sources such as risk centers and financial entities.
  - The sending of reports to the System for the Prevention and Control of Money Laundering and Financing of Terrorism.
  - Receiving information and recommendations on self-control in gaming and other responsibility messages.
  - Marketing Campaigns – including an option to opt out.

By default, the consent must be set to “I do NOT accept”, using buttons or checkboxes.

Error! No text of specified style in document. Page | 6 of 12

## External Register Checks

There is no external register solution available in Colombia, so external register checks are not required, however, Coljuegos provides Operators with a list of excluded players on a quarterly basis, and that list is required to be managed by the Operator. Dev will be required to ensure this list is checked at time of registration and periodically as required. An option would be to implement this check at time of Login.

## Player Journey

A full range of player statuses with associated actions will be required to be dev’d.

| Status | Requirement |
|---|---|
| Provisional | - Players must be created as provisional and Operators have 30 days to verify the player.<br>- Provisional Players may not withdraw funds. |
| Activated | Players have full access to the casino. |
| De-activated | - Player has not been verified within 30 days.<br>- Player has been inactive for 6 months / 1 year (suspended) |
| Closed | - Player’s accounts have been cancelled.<br>- Players accounts has been suspended for 11 months / 2 years |
| Blacklisted | Players account is suspended due to suspected or proved fraud or suspicious behavior. |
| Excluded | Players have self-excluded themselves from the Casino or been excluded by Coljuegos, by court order, or by the Operator. |

Annual verification of players is required, and some backoffice updates may be required to support this.

Every six (6) months, the player's address must be checked and updated. Again, some backoffice updates may be required to support this.

## Banking

A compliant banking solution will be required to be dev’d, which includes:

- Preventing provisional players from withdrawing
- Honouring of deposit limits

Error! No text of specified style in document. Page | 7 of 12

- Indications of amounts that can be withdrawn by the player considering any tax that is payable that the Operator is required to withhold. This is new functionanality that we have not previously done.

The following banking methods are permitted:

- Current or savings Bank accounts in entities authorized and overseen by the Financial Superintendence of Colombia.
- Credit cards issued by entities authorized and overseen by the Financial Superintendence of Colombia.
- Any other instruments of payment offered by entities authorized and overseen by the Financial Superintendence of Colombia, such as wire transfers and payment gateways of the Colombian financial system and offered by the operator.
- Transfers of drafts or collection through Operators of Mail services of Payment authorized by the Ministry for Information Technology and Communications.
- Rechargeable prepaid cards.
- Payments in cash through physical points established by the operator.

In relation to withdrawals: Funds may only be withdrawn from the gaming account by electronic transfer to the bank account or credit card in the player’s name registered and identified on the platform, with a financial entity authorised and supervised by the Financial Superintendence of Colombia. In the case of credit cards, the Operator must inform the player that the withdrawal may not exceed the limit of its card.

## Backoffice updates

Backoffice tools will be required to be updated to support Colombian requirements including but not limited to:

- Help Desk
- Financial Transactions (limits)
- Update Account Status – including re-activation of players
- Player verification with provision for Annual verification of the player
- Removal / revocation of exclusion – dev will be required to support this.
- Support of new Responsible Gaming requirements (bet and session limits) – this will be a substantial amount of work as we have not done this previously.
- Reporting – statuses, limits and any new Responsible Gaming requirements - – this will be a substantial amount of work as we have not done this previously.

## Last login reminder

The date and time of the player’s last login must be displayed.

Error! No text of specified style in document. Page | 8 of 12

## Currencies

To meet regulatory requirements, the only currency supported in Colombia online casinos is the Colombian Peso. The platform is required to record the balance and movements expressed in game credits.

## Languages

The only language supported in Colombian casinos is Spanish. Full translation is required of games, clients and value adds.

## Domain

Websites are required to have a dot co (.CO) domain to operate online games.

## Terms and Conditions

It is the operator’s responsibility to manage the Terms and Conditions page for their casino.

## Player Protection Content

- General protection

Stipulated player protection information must be accessible to players on the casino website and must all be provided in Spanish, and must provide the following:

- Information on the potential risks related to gaming
- Notice on minor’s prohibition
- Notice on responsible gaming
- Games offered and all game rules
- Data Confidentially policy
- Mechanism available to limit their bets and duration of their sessions
- Link to a downloadable copy of the Casino’s T&Cs and the date and time of the player’s consent
- Coljuegos logo and link to the Coljuegos institutional website – client dev will be required to support this.
- Link to a web page for self-exclusion from gaming with the possibility of consulting the status and registration in the Excluded Player Registry.
- Link to a support page, including frequent questions.

- From the interfaces from which the player’s play, the following information below must be provided. Dev will be required for our cleints to support this some of these requirements.

- Name and /or logo of the Operator
- Telephone number and address of the Operators (physical and electronic)
- Licence Agreement (Concession) Number and dates its applicable
- Termination Date of the Licence Agreement (Concession)

Error! No text of specified style in document. Page | 9 of 12

- Prize Plans for games – provision will need to be made for the creation of these documents.
- Seal of Authorisation from Coljuegos
- Message authorised by Coljuegos stipulating that participation by minors is not permitted
- Rules of the game

## Responsible Gaming & Self Restriction Requirements

To meet regulatory requirements, the following self-restrictions options need to be available:

## Limits

Daily, weekly and/or monthly limits are set at time of registration. Requests to make limits more restrictive must be applied immediately. Requests to make limits less restrictive must be applied after 72 hours, and only after the player has confirmed his request again. This is similar to the UK, but dev will be required to support this requirement.

## Exclusions

Players must be given the option to exclude themselves temporarily or permanently via the user account web page, from a game or game types for periods established by the Operator. On termination of the period for a temporary exclusion, players must have the option to renew or cancel the restriction. Additional work will be required to provide the options for players to specifically cancel or renew a restriction.

A permanent exclusion may not be revoked for a minimum period of 6 months. A special exclusion revocation services is required which will require the player to:

- Provide updated information and documentation required for registration
- Sign a declaration requesting revocation of the exclusion

Work in the backoffice will need to be done to support this removal of exclusion requirement.

The Operator is required to make provision to ensure players that have been notified to it by Coljuegos (via a list sent quarterly) or by court order, or who have a relationship with the Operator, are excluded from gambling. We will need to provide options for this via the backoffice.

## Session Limits

Players must have the option to limit the duration of a game session. The duration (time elapsed) of the game session must be displayed. Dev work is required to meet this requirement.

## Inactivity Timeout

A 20 min inactivity timeout is required.

Error! No text of specified style in document. Page | 10 of 12

## Bet Limits

The Player must have the option to limit the amount that can be bet during a game session. This is new functionality that we currently to do support. Substantial dev will be required.

## Player’s Consent to Installations

Express player consent is required for the downloading of any components onto the player’s device. A log must be saved with the date and time of initial installation and records of updates subsequently downloaded and installed on the device. Some development work will be required here, especially around the logging.

## Games

The following game-related implementations must be included in Colombian casinos:

- Games
  - Autoplay – there appear to be some limits around the number of Spins for autoplay
  - Quickspin and QuickDeal must be disabled for Colombian casinos as a minimum 3 second spin is required
  - Multi-player games are not supported in Colombia without significant development
  - The Game interface must have a clearly visible display of the time that has elapsed since the start of a game session. Development work will be required to meet this requirement.
  - The game Interface must have a clearly visible permanent notice regarding responsible gaming. Development work will be required to meet this requirement.

Progessives: Work will be required around Jackpots in order for them to be offered in Columbia.

- Clock/server time must be in Colombian time and synchronised with a reliable time source - if the gaming server is required to be in Columbian time, this may mean it will need to be ringfenced.

- Help

Microgaming game help must be available in Spanish for all Microgaming casino games.

## Session Time

The time elapsed since the player’s current login expressed in hours: minutes: seconds, must be available once the player has accessed the gaming platform. Development work will be required to support this requirement.

## User Account History (Playcheck and Cashcheck)

The User Account History provided to the player must record the player’s participation and transactions, including wins and losses. It is a requirement to reflect taxes that are payable by the player including VAT and withholding tax for occasional income. All game movements from Bonus wagering need to be reflected. User Account History must be provided online for the last 30 days with the option for the player to download it. The player must have the possibility of having access to older information by request to the operator for the player’s entire lifetime.

Error! No text of specified style in document. Page | 11 of 12

Player must be able to consult in real time, their gaming account balance and user account with every play made and bet placed covering any selected time period. A transaction report will permit players to consult their winnings and losses with timestamps for each game event, as well as account balance.

Firstly, signficant development work will be required to provide all the data that is required in these reports. Secondly, if real time data for any period of time is required, then significant development work may be required to support this requirement.

## Inspection System

Secure access is required by Coljuegos to the Central Gaming Unit (The Central Gaming Unit is composed of the Gaming Platform and the Gaming Software) for control purposes, and compliance with all other gaming regulation requirements. If this is referring to access to the Gaming Server, then this requirement is a massive concern.

**Central Gaming Unit:** Set of technical components necessary to process and manage the operations carried out by players during the games. It records all operations and results on events, distribution of prizes, operations related to player registration, aggregated and control data, and operational events of the gaming platform.

## SAFE

A fully complaint SAFE solution is required. The SAFE servers are required to be in Colombia. Significnat dev work will be required to comply with this requirement.

## Integrity Checker

Critical files (RNG and game engine software) on the gaming severs need to be checked daily to ensure that these are the authorised/certified versions.

## Logging

The system is required to log and store all operations carried out on the Central Gaming Unit by all users, and all player operations. Logs need to be kept for at least 6 months but information to older logs needs to be stored and made available for possible consultations during the term of the agreement.

## Player Devices

The Paltform is required to identify the different types, versions and operating systems of devices used by players. Oprators are required to send statistics on device usage to Coljuegos on a quarterly basis. We would need to develop a mechanism to enable Operaotrs to report this information quarterly.

## Incomplete Game Pop up

Incomplete game pop ups are required.

Error! No text of specified style in document. Page | 12 of 12

## RTP Monitoring

Operators need to ensure the correct operation of the games RTP. If any serious deviations are detected, the Operator must deactivate the affected games, types or variety, until such time as it resolves and remedies the incident. If abnormal operation is confirmed, the Operator must notify Coljuegos, indicating the situation, period, affected players and amounts, and the adopted measures.

## Certification / Testing

- Full certification of the Gaming System will be required to be completed before an Operator can go live.
- Critical Components of the Gaming System will need to be identified.
- Certification of changes to the critical components will be required.
- Penetration and vulnerability testing must be conducted on an annual basis and certification obtained