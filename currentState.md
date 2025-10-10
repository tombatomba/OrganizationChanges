# Current state

Mother company is based in EU. IT is well recognized in Insurance and finance services. There are five branches. (Croatia, Serbia, Monetenegro, North Macedonia, Kosovo*)
Four of them are Non-EU (Serbia, Kosovo, Montenegro, N. Macedonia) with own subdiaries which include pension funds, Car service (MOT), life and non-life insurance etc...
Even though the legal frameworks are not identical, there are strong similarities in regulatory requirements and accounting standards. With only minor differences, a common professional language is used across all entities. The actuarial tables applied in calculations are identical, and the overall economic systems are very similar, with comparable income levels per capita.

In this document, focus is on  EU countries.

## Common core IT system

Each non-EU subsidiary uses an identical IT core system. The system is maintained by a company based in Serbia, employing around 15–20 specialists.

The operating model includes a joint steering body that aligns and approves development plans for the upcoming year. During regular operation, system maintenance is managed through a dedicated ticketing platform, where each company submits its own requests for minor changes. These requests are handled independently and are not visible to other client companies.


##Simplified Application Architecture

![Logical architecture in insurance companu](/media/LogicalArchitecture.png)


## Business software
According to diagram above, it is obvious complexity in current arhitecture. Even Core system is same, there are list of customization specific for each group.
Software landscape is stil various due to:
* legacy reasons (some companies are just follow current track)
* different business requirements and needs
* different competences in local subsidiaries
* lack of common enterprise bus around core system

## Of the shelf software
Even not listed, other software solutions used vary from one group member to another, although in some areas there is a significant influence from the Group, which has managed to introduce unified solutions.
Consequently, the list of vendors varies.

## Infrastructure

If we exclude the recent efforts to unify and organize the security segment with the support of the Group, the basic infrastructure elements remain entirely at the discretion of the subsidiaries. In addition to using different manufacturers (firewalls, servers, storage), this also results in partnerships with various vendors specialized in specific solutions and devices.
Similar as in software landscape it leads to:
* lack of standardization
* higher costs
* complex vendor management
* security chalanges
* limited knowledge sharing
* dependancy on critical workforce

## Digital Workplace software and general ledger

Despite the existing challenges, there is a segment that has been successfully centralized and is operating effectively, already showing measurable improvements in service quality and performance. This centralized segment covers key components of the Microsoft ecosystem, including email, Office, Navision, and the Service Desk platform.

