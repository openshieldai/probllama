+++
title = 'ChatGPT Prompt Injection Attack via Single-Pixel Image'
date = 2023-05-29
+++
A new prompt injection attack targets users of the ChatGPT web version, allowing modification of chatbot answers with an invisible single-pixel markdown image that exfiltrates sensitive chat data to a malicious third-party. The attack can be extended to affect all future answers and make the injection persistent. It combines a set of tricks to deceive users without exploiting any vulnerabilities.

The attack scenario involves a user copying text from an attacker’s website, with the malicious prompt injected into the copied text. When the user sends this text to ChatGPT, the chatbot appends a single-pixel image to its response, sending the sensitive data to the attacker’s server. This can lead to sensitive data leakage, insertion of phishing links, and pollution of ChatGPT output.

[More details here](https://systemweakness.com/new-prompt-injection-attack-on-chatgpt-web-version-ef717492c5c2)
