# 💰 _Ransom notes for group_ gwisinlocker
* **[gwisinlocker.txt](https://ransomware.live/ransomware_notes/gwisinlocker/gwisinlocker.txt)**

```
Hello [snip],
You have been visited by GWISIN.
We have exfiltrated a lot of sensitive data from your networks, including, but not limited to:

I. Production applications, source (Git/SVN), files and DBs
[1] LIMS (all regions) + DNA and other internal platforms

By combining lab (LIMS) data and the primary big customer platform (DNA), it is easy to identify customer projects, credentials and data.
Despite ISO27001 and ISMS-P with a good PIMS strategy, you have failed to protect customer data across all services.
Your privacy policy assures customers their data security and privacy is top priority, reality seems very different. 
We wonder what your customers will have to say about that?

[2] My-genomestory (MGS), myPETGENE and general DTC related data

Once again failing to protect very sensitive data and communications of your customers.

[3] Infrastructure and sequencing pipeline data / scripts 

Everything from documentation to project specs to produced VCFs and PDF reports post-analysis were collected. 
More importantly, a full deep dive of your network infrastructure documentation and access.
The only way to kick us out is to buy all new hardware, including network equipment (UTM / switches) and sequencing / data storage systems.  
Someone could have quietly modified your sequencing pipeline instead of contacting you, causing you much bigger issues (legal, financial and otherwise). 
Can you really trust your results, if you can't trust your input data and processing pipelines?

II. Internal Data & Communications

[1] ERP/CRM Systems (NEOE, Dynamics)
[2] Active Directory dump with credential history (NTDS + passive credential collection)
[3] DO GW with DB (your groupware contains a lot of data)
[4] Exchange email communications (PST) of targeted important employees in various roles
[5] Financial / Accounting / Research / IT / Customer / Etc. documents

- A lot of documents and other files were collected from SHARE/NEWSHARE machines among other servers
- Your DLP and monitoring was rendered effectively useless and could not stop us, neither could your security team and defensive products

We have also encrypted critical Windows and Linux servers.
We recommend that you do NOT restart servers or recovery may be slower.
The good news for you is that we can:
- Decrypt all files with extension ".[victim_snip]" very quickly
- Delete all sensitive data we have exfiltrated, instead of selling it
- Help you improve your security
- Disappear and not be your problem anymore

All you have to do is follow the instructions:
1.) Download Tor Browser: https://www.torproject.org/download/
2.) Go to our website: http://[snip]:[snip]@gwisin4yznpdtzq424i3la6oqy5evublod4zbhddzuxcnr34kgfokwad.onion
3.) Login with username: [snip], password: [snip]
4.) Change password (one time setup)
5.) Setup end-to-end message encryption password
6.) Read the full instructions on the website and contact us using the message system provided there

[WARNING - #1] 
If you are having trouble reaching our website, attempt closing and re-opening the Tor browser. 
If you are still unable to reach our website, create a DNS TXT record @ [victim_subdomain].[victim_domain].com containing a hex-encoded email address and we will contact you.
However, eventually we will need to communicate using our website to preserve the privacy of all parties involved. 

[WARNING - #2]
Do NOT contact law enforcement (such as NPA, KISA or SMPA) or threat intelligence organizations as they may prevent you from recovering quickly.
They can't really help you and they don't care if your business is destroyed in the process.
Contact us within 72 working hours, so we can negotiate in good faith and resolve this quickly.


```


> [!TIP]> Ransomware notes are provided by [Zscaler ThreatLabz](https://github.com/threatlabz/ransomware_notes) under MIT License
> 




Last update : _Monday 20/11/2023 16.14 (UTC)_

