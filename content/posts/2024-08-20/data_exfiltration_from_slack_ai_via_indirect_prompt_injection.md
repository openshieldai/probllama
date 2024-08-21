+++
title = 'Data Exfiltration from Slack AI via indirect prompt injection'
date = 2024-08-20T05:00:25+02:00
+++
The blog article discusses a significant vulnerability in Slack AI that allows attackers to exfiltrate sensitive data from private channels through indirect prompt injection. By manipulating the language model of Slack AI, an attacker can post malicious instructions in a public channel, prompting the AI to retrieve and disclose information from private channels they do not have access to. The article outlines a detailed attack chain, demonstrating how this could lead to the unauthorized retrieval of sensitive information, such as API keys, or even facilitate phishing attempts. It highlights the increased risk presented by Slack AI's recent changes, which allow it to ingest files and documents, expanding the attack surface for potential exploitation. Finally, the authors emphasize the importance of responsible disclosure and the need for organizations to implement security measures to mitigate these vulnerabilities.

[More details here](https://promptarmor.substack.com/p/data-exfiltration-from-slack-ai-via)
