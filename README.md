# Chatbot-Ai Dashboard Pages

[Try it now](https://dash.chatbot-ai.gq)

## Add Status Card

Find in `<script>` section and add after `// Card insert here`

```
insertAfter(div, createCardElement("Display Name",httpGet(stats_api + "Stats Database Query"),"Bubble Description"));

```
