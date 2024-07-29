+++
title = 'Google Colab AI: Data Leakage Through Image Rendering Fixed. Some Risks Remain.'
date = 2024-07-25T05:00:25+02:00
+++
Google Colab AI, now just called Gemini in Colab, was vulnerable to data leakage via image rendering. This is an older bug report, dating back to November 29, 2023. However, recent events prompted me to write this up: Google did not reward this finding, and Colab now automatically puts Notebook content (untrusted data) into the prompt. Let’s explore the specifics. Google Colab AI - Revealing the System Prompt At the end of November last year, I noticed that there was a “Colab AI” feature, which integrated an LLM to chat with and write code.
[More details here](https://embracethered.com/blog/posts/2024/google-colab-image-render-exfil/)

