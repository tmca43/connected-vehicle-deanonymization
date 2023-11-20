# Connected Vehicle BSM Deanonymization
 
The U.S. Department of Transportation claims that vehicle-to-infrastructure (V2I) communications will preserve the anonymity of drivers. Specifically, the department claims
> The system—operated by private entities—will not permit tracking through space or time of vehicles linked to specific owners or drivers or persons. Third parties attempting to use the system to track a vehicle would find it extremely difficult to do so, particularly in light of far simpler and cheaper means available for that purpose.

I assess that claim using the Basic Safety Message data from V2I pilots. Both pilots organized their data according to SAE 2735, an industry standard for vehicle communications.

The Tampba Bay sample data from [USDOT Open Data Portal](https://data.transportation.gov/Automobiles/Tampa-CV-Pilot-Basic-Safety-Message-BSM-Sample/nm7w-nvbm).

The bottom line is that this data can be used to recreate individual trips contrary to the claims of the DOT.