<h1>Data Manipulation within Splunk</h1>

<h2>Description</h2>
Data processing, parsing, and manipulation are important for getting meaningful insights from machine-generated data. Having the right skills is very useful when responding to security threats, investigating incidents, and monitoring system health. In this lab, I will be covering how events are parsed in Splunk, the importance of conf files, how to extract custom fields, and how to identify timestamps within an event log.
<br />
<br />
In this scenario, we are working as a SOC analyst who needs to ingest some logs for a client. Splunk needs to be configured to parse and transform the logs, we have the following issues: Event breaking, multi-line events, Masking, and extracting custom fields. We will be addressing these issues within the terminal on our VM.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Splunk</b> 
- <b>SPL</b>
- <b>linux CLI</b>
- <b>splunk stanzas</b>

<h2>Environments Used </h2>

- <b>Linux Virtual Machine</b>

<h2>Configuration Files and their Purpuse</h2>

- <b>Inputs.conf - Defines data inputs and how to collect data from sources.</b> 
- <b>Props.conf - Specifies parsing rules for different sourcetypes to extract fields and define field extractions.</b>
- <b>Transforms.conf - Allows you to define field transformations and enrichments on indexed policies, and access control.</b>
- <b>Indexes.conf - Manages the configuration of indexes in Splunk, including storage, retention policies, and access control.</b>
- <b>Outpus.conf - Specifies the destination and settings for sending data  to various outputs, such as remote Splunk instances or third-party systems.</b>
- <b>Authentication.conf - Manages authentication settings and user authentication methods.</b>

<h2>Lab Walk-through</h2>
