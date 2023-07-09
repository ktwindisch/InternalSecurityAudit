<h1>Botium Toys - Internal Security Audit</h1>

<h2>Description:</h2>

This audit consists of a company named Botium Toys who is currently under marketing pressure to increase their sales market by pushing into the E.U. In order to do this, the company wants to audit their compliance. They also want to establish best practices as they revamp their security measures in line with their goals: 

To adhere to the NIST CSF, establish a better process for their systems to ensure they are compliant, and fortify system controls.
Botium Toys also wants to adapt to the concept of least permissions when it comes to user credential management, establish their policies and procedures, which includes their playbooks and ensure they are meeting compliance requirements.

<h2>Frameworks Used:</h2>

- <b>NIST CSF</b>
- <b>GDPR</b>
- <b>PCI DSS</b>
- <b>SOC type 1</b>
- <b>SOC type 2</b>

<h2>Environments Used:</h2>

- <b>Windows 10</b>

<h2>Audit walk-through:</h2>

<p align="left">
<h4> Controls Assessment </h4>
<b>Current assets </b><br/>
<br/>
Assets managed by the IT Department include: <br/>
<ul>
<li>On-premises equipment for in-office business needs <br/> </li>
<li>Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc. <br/></li>
<li>Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management <br/></li>
<li>Internet access <br/></li>
<li>Internal network <br/></li>
<li>Vendor access management <br/></li>
<li>Data center hosting services <br/></li>
<li>Data retention and storage <br/></li>
<li>Badge readers <br/></li>
<li>Legacy system maintenance: end-of-life systems that require human monitoring <br/></li>
</ul>
<h4> Compliance Checklist:  </h4>
<ul>
<li>GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens’ data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen’s data is compromised, they must be informed within 72 hours of the incident. Botium Toys needs to adhere to GDPR because they conduct business and collect personal information from people worldwide, including the E.U.<br/></li>
<br/>
<li>PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. Botium Toys needs to adhere to PCI DSS because they store, accept, process, and transmit credit card information in person and online.</li><br/>
 
<li>SOC1 and SOC2 are a series of reports that focus on an organization’s user access policies at different organizational levels. They are used to assess an organization’s financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud. Botium Toys needs to establish and enforce appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.</li>
</ul>
<h4> Stakeholder Memorandum: </h4>
<h4>Summary/Recommendations:</h4>
It is recommended that critical findings relating to compliance with PCI DSS and GDPR be promptly addressed since Botium Toys accepts online payments from customers worldwide, including the E.U. Additionally, since one of the goals of the audit is to adapt to the concept of least permissions, SOC1 and SOC2 guidance related to user access policies and overall data safety should be used to develop appropriate policies and procedures.<br/> 
<br/>
Having disaster recovery plans and backups is also critical because they support business continuity in the event of an incident. Integrating an IDS and AV software into the current systems will support our ability to identify and mitigate potential risks, and could help with intrusion detection, since existing legacy systems require manual monitoring and intervention.<br/>
<br/>
To further secure assets housed at Botium Toys’ single physical location, locks and CCTV should be used to secure physical assets (including equipment) and to monitor and investigate potential threats. While not necessary immediately, using encryption and having a time-controlled safe, adequate lighting, locking cabinets, fire detection and prevention systems, and signage indicating alarm service provider will further improve Botium Toys’ security posture.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
