---
layout: project
title: "Edit Table"
type: "UI Design"
description: "Creation of the ‘Edit Activity’ making up an editable data table, for ARKK Solutions financial automation platform."
image: "editable-table/main-image.png"
---

## OVERVIEW
Through the emergence of the Pillar 2 framework, multinational enterprises are expected to adhere to a global minimum tax on profits. Customers subject to these new rules would be required to submit large amounts of data, and we wanted to offer them a convenient way of doing this in an interactive table. It was also strongly felt that the benefits of an editable table would stretch beyond this use case. I was the only designer on this project, working mainly with the CTO and a small development team to fit new requirements into our existing table design, and create a new audit log for users to track any changes in.

## PROBLEM
- Users are limited in their ability to edit data within tables.
- Incorrect or missing data could only be addressed by updating original files then re-uploading.
- A change report which listed any changes made was difficult to read and interact with.

## GOALS
- Streamline the process by which users are amending table data to help with Pillar 2 submissions and beyond.
- For this process to occur on the platform.
- Users are able to keep track of these changes in an easy to use audit log.

<br>

---

### KICKOFF
![]({{ site.baseurl }}/assets/img/editable-table/kickoff-1.png)
We conducted an initial kick-off meeting to understand the problems we faced for both sides of this project. As Pillar 2 was a new set of rules, there was no existing process for us to examine how such data gets submitted. We instead focused on understanding how users might access and amend data in complex tables, and what they expected to see with regards to an audit trail.
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/kickoff-2.png)
I listed out some user scenarios following interviews with customers to help shape the solutions we came up with.

### AUDIT LOG RESEARCH
The existing approach to documenting changes on the platform was through a ‘change report’, which could only be viewed on export and consisted of a list that was difficult to read due to a lack of any helpful styling. This project brought welcomed motivation to update this feature.

![]({{ site.baseurl }}/assets/img/editable-table/audit-log-1.png)
I conducted research exploring the structure an audit log could take, and the standard features users would expect. The majority of these examples presented audit logs as a separate page, whereas we wanted to consider an audit panel that users could view alongside their data. For this I did general research into panels that were not necessarily for audit purposes.
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/audit-log-2.png)
After collecting all this information and with the requirements in mind I sketched out initial concepts for an audit log panel. Initially a big focus for us was to have a very narrow audit log panel to save on space, which you could expand out to fill the activity frame in this view.
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/audit-log-3.png)
I then developed some wireframes to consider different solutions. The differences I considered related to icons, panel width and expansion behaviour.
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/audit-log-4.png)
This was a panel we developed and used to test our requirements.

### FINAL DESIGNS
![]({{ site.baseurl }}/assets/img/editable-table/table-flat-table-2.png)
We already had a design for tables across the platform, the task here was more about introducing the new states we needed in an appropriate style. I experimented with different options here, but we preserved our existing pale blue row hover and introduced the selected state for a cell to be edited at a white fill with a thicker blue border. This was consistent with behaviour elsewhere for input fields. Further modifications we applied included horizontal and vertical lines across the table values, something we had previously achieved with space, but could not afford to do in this data heavy scenario.
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/table-flat-table-3.png)

![]({{ site.baseurl }}/assets/img/editable-table/final-designs-1.png)

![]({{ site.baseurl }}/assets/img/editable-table/final-designs-2.png)