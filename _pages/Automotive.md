---
title: Automotive
author: Cisco CC TSA Team
date: 2023-08-06
layout: post
---

```
Last modified: Thu, 14 August 2023
```

## Overview of the Use Case:

The Automotive Use Case shows the following:

- Get a Brochure
- Test Drive booking
- Deflect to WhatsApp or Call Back 


### Demo Video

> The video below shows a demo about this Use Case:

{: .block-tip }
<div style="padding-bottom:56.25%; position:relative; display:block; width: 100%">
	<iframe src="https://app.vidcast.io/share/embed/e280e48b-bb9f-4335-a1fa-95c39427ec33" width="100%" height="100%" title="Automotive Demo" frameborder="0" loading="lazy" allowfullscreen style="position:absolute; top:0; left: 0;border: solid; border-radius:12px;"></iframe>
</div>
### How to configure this Demo Use Case in your Tenant

1.	**WA_Automotive.workflow**
2. Create a new flow and Import from WA_Automotive.workflow in the ConnectFlows directory.
3. Make the following changes:

- In the Agent Handover path edit the Queue Task to add your own queue
-	Open and save All Receive nodes.
-	Open the TaskBot node and select the QA BOT created above [Task BOT Name]
-	Save and Make Live – select the appropriate WhatsApp App.


## Flows 

<a href="https://webexcctsa.github.io/wxcc-usecases/assets/ConnectFlows/WA_Automotive.workflow">WA_Automotive.workflow</a><br> 


<br>
<br>
---

  <script>
    document.addEventListener('DOMContentLoaded', () => {
      console.log('DOMContentLoaded OKOK')
    })

    window.addEventListener('load', () => {
      console.log('window load OK')
    })
  </script>

<p style="text-align:center"><strong>Congratulations, you have completed the configuration for this Demo Use Case! You can continue with the next one.</strong></p>
		
<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/webex-small.png" width="100"></center>
