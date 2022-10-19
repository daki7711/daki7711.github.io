---
title: 'Speak your mind : Introducing APTLY, the software platform that turns ideas into working apps'
collection: publications
permalink: /publications/kim2022speak
paperurl: 'http://daki7711.github.io/files/ICERIpaper2022.pdf'
date: 2022-09-22
venue: '15th annual International Conference of Education, Research and Innovation'
---

Abstract : MIT Aptly is a tool that uses the technology of large language models to automatically generate mobile apps from written or spoken natural language descriptions. Similar to Github’s Copilot, it is based on OpenAI’s Codex, a specially tuned version of GPT-3. Aptly lets people create programs without requiring any use of coding or knowledge of programming. For example, one can tell Aptly by speaking or typing:
 Make an app with a text box, a list of six languages and a button that says “translate.” When the button is clicked, translate the text into the selected language and show the translation.
The result is a complete functioning app for Android or iPhone. The app has a field for user input and six buttons labeled English, Spanish, French, German, Italian, Japanese. Pressing one of the buttons translates the input to the corresponding language. Aptly’s app generation is more than just a syntactic transformation of the input text. Aptly draws upon a large body of code with which it has been trained to provide a context for its app creation. In the above example, Aptly has independently chosen the six languages, something that was not specified in the input text.
As most large language models do, Aptly’s performance depends on the input given to OpenAI’s Codex. These inputs are referred to as prompts. Aptly crafts a prompt by providing a set of example pairs (a textual description of an example app and its corresponding code) along with the description of the desired app. Such prompt engineering is referred to as few-shot prompts. In order to optimize Aptly’s performance, when selecting example pairs, we choose the ones that are semantically close to
the description of the desired app.
The prospect of no-code platforms is currently sparking considerable ferment in enterprises concerned with professional programming careers. Similarly, Aptly poses challenges for research in computational thinking education for K-12 students. Much of the present-day curriculum emphasizes implementing computational artifacts using text-based coding with Python or block-based coding with Scratch or App Inventor. What will be the foundations for that curriculum when tools like Aptly are common and the transition from ideas to running programs can be accomplished automatically?
This presentation will demonstrate Aptly’s preliminary performance and review its implementation, which incorporates OpenAI Codex, Amazon Alexa and MIT App Inventor.

[Download paper here](http://daki7711.github.io/files/ICERIpaper2022.pdf)
