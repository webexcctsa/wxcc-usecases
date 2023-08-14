---
title: Insurance
author: Cisco CC TSA Team
date: 2023-08-10
layout: post
---

```
Last modified: Thu, 10 August 2023
```

## Overview of the Use Case:

The Insurance Use Case shows an Example how to Reporting an Accident using digital automation.


### Demo Video

> The video below shows a demo about this Use Case:

{: .block-tip }
<div style="padding-bottom:60.25%; position:relative; display:block; width: 100%">
	<iframe src="https://app.vidcast.io/share/a5995031-16b4-49a5-abe2-30beee362f43" width="100%" height="100%" title="Station Login" frameborder="0" loading="lazy" allowfullscreen style="position:absolute; top:0; left: 0"></iframe>
</div>

### How to configure this Demo Use Case in your Tenant

1.	**WA_Insurance.workflow**
2. Create a new flow and Import from WA_Insurance.workflow in the ConnectFlows directory.
3. Make the following changes:
   - 	Edit the Trigger Node to add YOUR_TRIGGER_Word (or whatever unique trigger you want to use)

![Trigger Word](/assets/images/Insurance/triggerword.png)

- In the Agent Handover path edit the Queue Task to add your own queue
- Open and save All Receive nodes.
- Open the QnABot node and select the QA BOT created above [QA BOT Name]
- Save and Make Live – select the appropriate WhatsApp App.




# Flows 


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

<p style="text-align:center"><strong>Congratulations, you have completed this lab! You can continue with the next one.</strong></p>
		
<p style="text-align:center;"><img src="///assets/gitbook/images/webex-small.png" width="100"></p>
<center><img src="///assets/gitbook/images/webex.png" width="100"></center>