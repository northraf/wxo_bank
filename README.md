<html lang="en-US">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <img src = "DTE_Bank_wxO.png"
    	width="auto" height="1200"
         alt = "New Watson Assistant Bank" />

</head>

<!-- add your script here -->
<script>
  window.watsonAssistantChatOptions = {
    integrationID: "bd351f05-9175-4a32-89b5-de5323779e88", // The ID of this integration.
    region: "aws-us-east-1", // The region your integration is hosted in.
    serviceInstanceID: "20240201-1635-4978-90fa-ee7eb719d913", // The ID of your service instance.
    onLoad: async (instance) => { await instance.render(); }
  };
  setTimeout(function(){
    const t=document.createElement('script');
    t.src="https://web-chat.global.assistant.watson.appdomain.cloud/versions/" + (window.watsonAssistantChatOptions.clientVersion || 'latest') + "/WatsonAssistantChatEntry.js";
    document.head.appendChild(t);
  });
</script>

<body></body>

</html>
