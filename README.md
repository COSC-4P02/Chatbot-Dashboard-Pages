# Chatbot-Ai Dashboard Page

[Try it now](https://dash.chatbot-ai.ga)

## Add Status Card

Find in `<script>` section and add after `// Card insert here`

```
insertAfter(div, createCardElement("Display Name",httpGet(stats_api + "Stats Database Query"),"Bubble Description"));

```