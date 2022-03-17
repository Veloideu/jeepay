# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are
currently being supported with security updates.

FileUpload Api

## Reporting a Vulnerability

The vulnerability was discovered through the table of contents below.

1. http://mch.d.jeepay.vip / Login
2. http://mch.d.jeepay.vip/current/userinfo / Go to your profile settings.
3. image(https://github.com/Veloideu/tank/blob/master/5.png?raw=true) / A script is also inserted while requesting to change the image of the avatar.
4. image(http://mgr.d.jeepay.vip/api/anon/localOssFiles/avatar/a84fd3d3-40be-4414-900f-49e3604c68a0.png) After that, if you access the image of the avatar, you can see that the XSS vulnerability occurs. 

This vulnerability is capable of... If a URL parameter is sent as content that makes up the content of an HTML page or JavaScript can be used in a user input form,
a malicious user (an attacker) can steal useful information, such as a user's or administrator's cookie or session value, 
and exploit other vulnerabilities and vulnerabilities. You can attack together

--
When uploading a file, it is recommended to substitute special symbols and specific words or change the file upload method.
