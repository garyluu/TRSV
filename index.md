---
layout: page
title: simple site
tagline: Easy websites with GitHub Pages
description: Minimal tutorial on making a simple website with GitHub Pages
---

### Validation Server Health
See {{site.validation-server-url}}/health_check to check its health.

### Validation Server Environment
See {{site.validation-server-url}}/environment to see the environment it is running on.

### Tool Registry Service Validation Status
| Service       | Status        |
| ------------- |---------------|
| Dockstore     | [![Validator Running]({{site.validation-server-url}}/trs/validator?url=https://dockstore.org:8443)]({{site.validation-server-url}}/trs/validator/debug?url=https://dockstore.org:8443) 
| {placeholder_name} | [![Validator Running]({{site.validation-server-url}}/trs/validator?url={placeholder_url})]({{site.validation-server-url}}/trs/validator/debug?url={placeholder_url})      
| Add based on template above, just change {placeholder_name} to your service name| Add based on template above, just change {placeholder_url} to your webservice's url

If you see "Validator Running", refresh the page in a minute.

