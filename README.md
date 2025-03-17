
<!-- In your <head> tag -->
<script src="https://cdn.botpress.cloud/webchat/v2.3/inject.js"></script>
<style>
  #webchat .bpWebchat {
    position: unset;
    width: 100%;
    height: 100%;
    max-height: 100%;
    max-width: 100%;
  }

  #webchat .bpFab {
    display: none;
  }
</style>

<!-- Put this on your page BEFORE the script below -->
<div id="webchat" style="width: 500px; height: 500px;"></div>

<!-- In your <body> tag -->
<script>
  window.botpress.on("webchat:ready", () => {
    window.botpress.open();
  });
  window.botpress.init({
  "botId": "8f14ee00-2249-4358-b688-0d804311b8e3",
  "configuration": {
    "website": {},
    "email": {},
    "phone": {},
    "termsOfService": {},
    "privacyPolicy": {},
    "color": "#3B82F6",
    "variant": "solid",
    "themeMode": "light",
    "fontFamily": "inter",
    "radius": 1,
    "showPoweredBy": false,
    "allowFileUpload": false
  },
  "clientId": "6f2ebfbe-d9ab-4cab-a0e2-5a9c3e94bcda",
  "selector": "#webchat"
});
</script>
