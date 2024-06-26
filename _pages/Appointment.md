---
title: Appointment Management
author: Cisco CC TSA Team
date: 2023-08-07
layout: post
---

```
Last modified: Thu, 10 August 2023
```

## Overview of the Use Case:

The Appointment Management Use Case demonstrate:

- Check my Appointment Status
- Change my Appointment
- Cancel my Appointment


### Demo Video

> The video below shows a demo about this Use Case:

{: .block-tip }
<div style="padding-bottom:56.25%; position:relative; display:block; width: 100%">
	<iframe src="https://app.vidcast.io/share/embed/959c34cd-e8b7-48d4-8c4c-93236832d513" width="100%" height="100%" title="Appointment Management Demo" frameborder="0" loading="lazy" allowfullscreen style="position:absolute; top:0; left: 0;border: solid; border-radius:12px;"></iframe>
</div>

### How to configure this Demo Use Case in your Tenant

1.	**WA_Appointment.workflow**
2. Create a new flow and Import from WA_Appointment.workflow in the ConnectFlows directory.
3. Make the following changes:
- 	Edit the Trigger Node to add AbdulDemoAppointment (or whatever unique trigger you want to use)

<center><img src="https://webexcctsa.github.io/wxcc-usecases/assets/gitbook/images/Appointment/triggerword.png" width="80%"></center>



- In the Agent Handover path edit the Queue Task to add your own queue
- Open and save All Receive nodes.
- Open the QnABot node and select the QA BOT created above [QA BOT Name]
- Save and Make Live – select the appropriate WhatsApp App.



## Flows 

<a href="https://webexcctsa.github.io/wxcc-usecases/assets/ConnectFlows/WA_Appointment.workflow">WA_Appointment.workflow</a><br> 

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

