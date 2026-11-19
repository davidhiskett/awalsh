---
layout: project
title: "Edit Table"
type: "UI Design | UX Design"
description: "Creation of the ‘Edit Activity’ making up an editable data table, for ARKK Solutions financial automation platform."
company: "ARKK Solutions"
image: "editable-table/edit_main_image.png"
---

## Improving functionality to facilitate a new tax requirement
The introduction of the OECD Pillar Two Framework requires multinational enterprises to pay a minimum level of tax on their global profits. This creates a significant data management challenge for businesses that need to collect, consolidate, then review large amounts of financial data from different entities. 

This created a technical requirement for editable tables across the ARKK platform, to accommodate multi-report reviewing. In-turn, this surfaced the assumption that the current change report feature would be problematic to users submitting within this framework in its current state. 

As the sole designer I worked directly with the CTO and a small engineering team to extend table functionality, and introduce a more user friendly change history.

Key achievements:
- Direct in-platform table editing removed reliance on external file corrections to make simple updates to datasets
- The introduction of an in-context audit log replaced a previous export-only, densely displayed approach to viewing change history, lowering the time it takes to validate a dataset
- Users who engaged with new edit and audit functionality experienced less friction overall, with reduced support messages related to amendment and upload cycles 
- Helped position the platform as a complete end-to-end solution, reducing reliance on external tools

<br>

---

### A need to keeping customers on-platform
It was clear we needed to make tables editable to prevent customers having to leave the platform to make essential updates. Inefficiency here would also have been compounded with the complex reporting in the new framework. We outlined our initial assumptions and goals, focusing on the technicalities around editing and logging changes. 

![]({{ site.baseurl }}/assets/img/editable-table/kickoff-1.png)

### Users need to leave the platform to make simple changes
Alongside this I collated information relating to this issue from existing feedback, customer conversations and existing data. 
<br>

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_key_findings.png)

Having to amend data in original files, then reupload them was frustrating customers because it broke focus when jumping off then back on the platform, which took time. This was particularly stressful if errors were noticed close to a deadline, and it became difficult to track changes with the change report being download-only, and displayed as very dense text.

### Failure to improve dataset amendments could lose customers
![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_insights.png)

With multiple actions becoming locked in a cycle of repetition, it increases the risk of new errors, along with irritating customers who are completing the same task multiple times, often in separate windows or tools. If we focus on validation as a key customer goal, we can streamline how files are uploaded and checked.

### A journey trapped in repetition
![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_journey_map.png)

I collected findings into a journey map, highlighting frustrations and identifying opportunities. Aside from knowing we needed to make tables editable, this helped with how the audit trail could further support an improved experience because it was so closely linked to changes. 

### Highlighting the importance of dataset validation
![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_design_implications.png)

Organising insights into jobs that users are trying to accomplish helped create the design solutions I could work off before I started testing them out. This also highlighted the different levels of ‘reviewing’ that took place.

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_JTBD.png)

As the table editing functionality was largely a technical activity, I created the interaction and UI details it needed, keeping them as simple as possible. I then started experimenting with the information architecture of the audit log. 
<br> 

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_product_strategy.png)

### A more accessible and usable change history
![no-border]({{ site.baseurl }}/assets/img/editable-table/audit-log-1.png)

Researching audit log patterns across enterprise platforms revealed that most logs were isolated from the worksheet, but easily accessible. I also reviewed different types of panels, to understand how supporting information is commonly displayed next to a detailed main frame.
<br>

![no-border]({{ site.baseurl }}/assets/img/editable-table/audit-log-2.png)

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_AL_usability_testing.png)
<br>

During testing with early iterations of the audit log, a horizontal table-like display confused users, but the search and filter were appreciated. Users were more drawn to the details on the card view, yet confused by why the author of the change was the most highlighted, leading aspect. It was also noted here that they found it more difficult to know how to search or filter entries. 

### The editability that customers needed 
As part of adding edit functionality, interactive states were added to the table to allow users to amend their data easily. Tooltips guided which cells could be changed.

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_final_1.png)

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_final_2.png)

An audit log panel was introduced as an overlay so that datasets and change history could be viewed simultaneously. Considering how many changes customers can have, the expandable card was chosen to give the ability to scan changes quickly, but also review details when necessary. 
<br>

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_final_3.png)

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_final_4.png)

![no-border]({{ site.baseurl }}/assets/img/editable-table/edit_final_5.png)
<br>

### Review, amend & check in one view
After launch, the frequency of file re-uploads did drop amongst customers as they were able to make changes to datasets within the platform. Customer feedback also confirmed that having a new audit trail, viewable within the platform was one of the most useful updates they had received, as they were able to complete tasks much faster. 

### Big changes from a small team
Working within a small team on these changes allowed for rapid iteration and direct collaboration with the engineering team.

Potential future developments that were highlighted as we completed this work included upgrading edit functionality from cell to row level, and strengthening traceability across audit log entries and datasets when multiple changes are made to the same cell. 
