# guld Ledger

## Creating a Blockchain With Triple Entry Accounting

### Author: Zimmi <br> License: CC-BY-4.0

## Single, Double & Triple Entry Accounting

### *NOTE: Blockchains are examples of triple-entry accounting.*

|     |Error Checking|Auditing|Messaging|Example|
|-------|------|---------|---------|--------|
|Single|None|None|N/A|Assets -10|
|Double|Automatic for local book|Manual|Lossy|Assets -10 Expenses +10|
|Triple|Automatic for all books|Automated in Real-time by third parties|Redundant to Lossless|Assets -10 Expenses +10 <sign receipt>|

## ledger-cli

### [Ledger](https://www.ledger-cli.org/) is a powerful, double-entry, plaintext accounting system

![CommodityGULD](https://github.com/Alexstang/Zimmi-Slides/blob/master/Commodity%20GULD.jpg)

* Define commodities
* Automate Transactions
* Budgets and Forecasts
* Python scripts
* Accounts <br> * Assets <br> * Liabilities <br> * Equity <br> * Income <br> * Expenses <br> * custom

## Guld Ledger Format

### Account Format

1. A guld name
2. One of the standard accounting categories: Assets, Liabilities, Income, Expenses, Equity
3. Defined by the user

![Account](https://github.com/Alexstang/Zimmi-Slides/blob/master/Account.jpg)

### *Additionally required timestamp metadata (i.e. ; timestamp: 1519966340)*

![Timestamp](https://github.com/Alexstang/Zimmi-Slides/blob/master/Timestamp.jpg)

## Guld Ledger File Format

![ZimmiLedger](https://github.com/Alexstang/Zimmi-Slides/blob/master/ZimmiLedger.jpg)

* Usually one transaction per file with the timestamp as name.
* Only one file can exist with given timestamp in given name directory.
* Transaction limit of 1/name/sec

![ZimmiTimeStamp](https://github.com/Alexstang/Zimmi-Slides/blob/master/ZimmiTimestamp.jpg)

* Timestamp metadata matches file name.
* Since metadata is signed, this ensures nonce authenticity.

## Individual Accounts

### Individual accounts are controlled by a single, registered PGP key.

![RegisterIsysd](https://github.com/Alexstang/Zimmi-Slides/blob/master/RegisterIsysd.jpg)

* Individuals apply for a name using PGP public key.¹
* Registration costs 0.1 GULD.²
* Account in GULD ledger, and 4 official sub-accounts. <br> * Assets <br> * Liabilities <br> * Income <br> * Expenses

## Group Accounts

### Group accounts are controlled by consensus of one or more registered individual PGP keys.

### Equity Example

![Equity](https://github.com/Alexstang/Zimmi-Slides/blob/master/Equity.jpg)

* Registration costs ~0.1 GULD/member.²
* Have own account in GULD ledger, and 5 official sub-accounts. <br> * All Individual sub-accounts <br> * Equity
* Equity <br> * = Vote weight <br> * determines consensus

### Group Register Example

![GroupRegistration](https://github.com/Alexstang/Zimmi-Slides/blob/master/RegisterGroup.jpg)

## Official Templates

*A transfer transaction moves Assets from one guld name to another.*

![Transfer](https://github.com/Alexstang/Zimmi-Slides/blob/master/Transfer.jpg)

*A grant transaction rewards a member for contributions to the group. Reward is both in transferable Assets and non-transferable Equity.

![Grant](https://github.com/Alexstang/Zimmi-Slides/blob/master/Grant.jpg)

*A register transaction creates a new, typed namespace in the blocktree.*

![RegistrationTX](https://github.com/Alexstang/Zimmi-Slides)

## Advanced Tools

*Automated Transactions execute every time a matching line is found in a full transaction.*

![AutomatedTX](https://github.com/Alexstang/Zimmi-Slides/blob/master/AutomatedTX.jpg)

*Budgets allow for limits to be set and enforced for each sub-account and time period.*

![Budgets](https://github.com/Alexstang/Zimmi-Slides/blob/master/Budgets.jpg)

Scripts can be embedded in ledgers, or executed as hooks by the guld filesystem.³

![Scripts](https://github.com/Alexstang/Zimmi-Slides/blob/master/Scripts.jpg)

## Summary

### Guld branch + ledger = blockchain

## End Notes

1. Name availability subject to discretion of guld support admins until official, legally compliant policy can be written.
2. Guld name registration prices as of Apr. 1 2018. Group names in table not ratio, capped at 1,000 GULD.
3. [Guld FileSystem Specification](https://guld.io/docs/guldFS-Specification.pdf) - Additional Configuration

*Scripts can be embedded in ledgers, or executed as hooks by the guld filesystem.³*
