Script that generates KQL queries for threat hunting.

This script utilizes **malwoverview** to generate a **KQL query** to search for **Network IoC** within your environment.

Just type the malware family name you want investigate.

Make sure you have malwoverview installed and configured on your host. (https://github.com/alexandreborges/malwoverview)

This implementation fetches IoC from MALWARE BAZAAR, THREATFOX and URLHaus. Feel free to add your sources too, depending on the API you have access.
