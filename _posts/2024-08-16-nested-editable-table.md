---
layout: project
title: "Edit Table"
type: "UI Design | UX Design"
description: "Creation of the ‘Edit Activity’ making up an editable data table, for ARKK Solutions financial automation platform."
company: "ARKK Solutions"
image: "editable-table/main-image.png"
---

## Adding functionality to facilitate a new tax requirement
With the introduction of the OECD Pillar Two Framework, multinational enterprises are required to submit large volumes of jurisdiction-level financial data in order to comply with global minimum tax regulations. 

Within ARKK, this created a need for customers to amend and validate submitted datasets quickly without repeatedly reprocessing source files. 

This project introduced:
- Direct, in-platform editing of tabular financial data
- A persistent audit log for tracking amendments
- Support for nested table structures that aligned with Pillar Two reporting requirements 

I was the sole designer on this project, working closely with the CTO and a small engineering team to extend the platform’s existing table frameworks while introducing editability and traceable change history. 

<br>

---

### An inability to edit table data caused frustration from slow updates
Prior to this project, ARKK customers could not edit table data in-platform, which resulted in any incorrect values needing to be amended in the source file, and re-uploaded. A change history feature was also export-only and difficult to interpret. 

### Establishing our goals around keeping customers in the platform
![]({{ site.baseurl }}/assets/img/editable-table/kickoff-1.png)
As this was a new requirement, we had no established internal workflow to address benchmark against. We focused on understanding how users might access and amend data in complex tables, and what they expected to see with regards to an audit trail.

Customer interview were conducted to understand: 
- How they currently validate submitted datasets
- When corrections typically occur in the reporting process
- What level of change traceability is favourable

### User scenarios to emphasise a need for more flexibility
![no-border]({{ site.baseurl }}/assets/img/editable-table/kickoff-2.png)
From this, I developed user scenarios to identify where in-platform editing could replace file-based correction cycles. Current workflows were forcing users to take multiple steps to amend any data, or spot changes. These were key areas to focus on. 

### A change report only visible on export kept helpful information hidden
The existing approach to documenting changes was limited, making it difficult to:
- Identify individual changes
- Understand edit context 
- Trace any responsibility for changes

### Researching options to display changes in view 
![]({{ site.baseurl }}/assets/img/editable-table/audit-log-1.png)
Researching audit log patterns across enterprise platforms revealed that most logs were isolated from the worksheet, but easily accessible. I also reviewed panels outside of audit log needs, to get a broader understanding of displaying supporting information next to a detailed main frame. 
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/audit-log-2.png)
We moved towards an overlay which would allow users to:
- Search and filter amendments
- Review change metadata
- Maintain visibility of edits during data validation 
<br>
<br>

![no-border]({{ site.baseurl }}/assets/img/editable-table/audit-log-3.png)

### Choosing an overlay that didn’t interrupt workflow
![]({{ site.baseurl }}/assets/img/editable-table/audit-log-4.png)
Early iterations explored space-saving approaches by hiding sort and filter controllers, however usability testing showed that this reduced feature discoveryability. These were added back on the final design. We also learnt that it was important for customers to review table data alongside any changes, so we abandoned the full width expand functionality, instead giving them the ability to resize the panel themselves.

### Adding in the editability that customers needed 
![]({{ site.baseurl }}/assets/img/editable-table/table-flat-table-2.png)
Editable states were introduced into the existing table system to support data amendments. 

Interaction design considerations:
- Clear visual differentiation on hover for which cells were editable 
- Cell-level edit selection 
- Consistent focus and input behaviour 
- Gridline introduction to support dense financial datasets  
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/table-flat-table-3.png)

![]({{ site.baseurl }}/assets/img/editable-table/final-designs-1.png)
Improvements to the audit panel included minimised cards for change entries by default to save space, but the ability to expand or collapse all to review more details.
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/final-designs-2.png)

![]({{ site.baseurl }}/assets/img/editable-table/table-nested-table-1.png)
Nested table functionality was introduced to support jurisdiction-level grouping within Pillar Two submissions. 
<br>
<br>

![]({{ site.baseurl }}/assets/img/editable-table/table-nested-table-2.png)

![]({{ site.baseurl }}/assets/img/editable-table/table-nested-table-3.png)

![]({{ site.baseurl }}/assets/img/editable-table/table-nested-table-4.png)

### Customers could now review, amend and check all in one view
File re-upload cycles were dramatically reduced when customers were able to make changes to table data on the platform. Furthermore, customer feedback confirmed that having an amendment history viewable in-session was reported to be one of the most useful updates they had received. 

The impact of these small changes was huge in improving workflow and customer satisfaction.


### Big changes from a small team
Working within a small product team on these changes allowed for rapid iteration and direct collaboration with the engineering team. 

Future developments that were highlighted throughout our initial work included adding a visual link between audit entries and table changes, particularly for distinguishing between removed rows or amended cells, to strengthen traceability within complex reporting scenarios.
