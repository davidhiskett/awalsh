---
layout: project
title: "Admin dashboard redesign"
type: "UI Design | UX Design"
description: "Admin dashboard redesign for Yaspa's open banking dashboard."
image: "admin-dashboard/main-image.png"
---

## OVERVIEW
The admin dashboard at Yaspa is a crucial B2B communication tool, documenting data on open banking transactions.

With a growing list of complaints, and upcoming new features, there was a need to improve the dashboard with scalability in mind. The dashboard was originally built with only a few UX patterns in mind, which were based on assumption and never tested. As features have been added, so has the number of issues requiring short term fixes. Being a crucial stage in securing new contracts, improving the dashboard would also bring a welcomed update to sales collateral.

I was brought on board to tackle this redesign. I was the only designer on the project, working alongside a product manager, business analyst, data scientist, three front end developers and two testers. With further input from several other stakeholders.

## PROBLEM
- Multiple redundant and faulty features were presenting a poor user experience.
- Little consideration for UX led to inefficient layout and problematic navigation.
- Outdated and inconsistent visual design was impacting general experience and brand image.

## GOALS
- Update Ul to match current standards and incorporate updated brand assets - aiming for clarity, consistency and brand trustworthiness.
- Provide clear insights with better visualisation and reporting of transaction data.
- Improve usability through simplified layouts and navigation which supports expansion.
- Recognise accessibility standards in our design and development process.
- Create a design system that can facilitate future development.

<br>

---

### EXISTING DASHBOARD
My initial focus was to review the dashboard in its current state myself, to ensure I was approaching this task objectively. I took screenshots of every section, observing what in my view worked, didn’t work, or appeared to be missing.

![]({{ site.baseurl }}/assets/img/admin-dashboard/existing-dashboard-1.png)

### INTERVIEWS
Prior to joining the company, a design colleague had conducted interviews with three merchants who had recently integrated with Yaspa. These customers were asked open ended questions regarding their recent experience with the dashboard. A standout finding from this was checking the status of a transaction was a crucial task. It was also reported that some filters do not work reliably, and more analytics on both customers and transactions would be helpful.

As a product team we then spoke internally to the compliance, customer support and sales teams to get an assessment of how our colleagues, and the customers they spoke to daily, experienced the dashboard. Below is a summary of the points we discovered.

![no-border]({{ site.baseurl }}/assets/img/admin-dashboard/interviews-1.png)

### MARKET RESEARCH
We conducted market research to evaluate current visual and UX standards, with a particular focus on payments dashboards. We kept a communal board of screenshots, which I sorted by product and then further divided into specific areas for features relevant to us. From this, we found Stripe, GoCardless and Checkout.com useful in relevance and interesting design. This board was added to and used frequently by the whole team throughout the whole project.


We progressed with a collection of confirmed problems and an idea of how we wanted to reshape the dashboard, and we defined requirements for each section on confluence. For areas we were less certain about, including a new customers page, we held design workshops to outline what we knew, what was possible, and what had been requested. We also met with the front end team regularly to confirm expectations and functional requirements.


### LAYOUT EXPLORATION
Different options for general structure and navigation wdere considered, but from our research a main left navigation side bar was common and felt the most appropriate for future growth of the dashboard. This would free up the page header to be used for extra content, and provide space for future pages to be added underneath.

<div class="row two-column">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/layout-exploration-1.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/layout-exploration-2.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/layout-exploration-3.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/layout-exploration-4.png">
</div>

### WIREFRAMES
We created and reviewed wireframes for each section of the dashboard, below is a snapshot of this process. Regular feedback sessions were conducted within the product team, then larger ones with the front end developers, testers and CTO. The high fidelity designs were then shown to internal teams and we collectively processed and dealt with often conflicting requests.

<div class="row two-column">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/wireframes-1.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/wireframes-2.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/wireframes-3.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/wireframes-4.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/wireframes-5.png">
    <img src="{{ site.baseurl }}/assets/img/admin-dashboard/wireframes-6.png">
</div>

During this process it was agreed the visuals for an overview page would be created and displayed using the data visualisation tool Tableau, and that this would be in the second round of development. 

### FINAL DESIGNS
After collecting relevant feedback from internal teams, we submitted the final designs for development. This involved multiple handoff sessions with the front event developers and testers, to intercept last minute uncertainties and allow for these to be detailed on tickets. This was a fluid and collaborative process with the front end developers, who constantly reviewed their work with me before it was handed to the testing team.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-1.png)
Login screen updated in line with our website and brand refresh.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-2.png)
The payment pages were previously divided into two separate menu sections, but as these products are so closely related, we rearranged them into tabs to connect them and save on space. We then improved the search and filter functionality above the payments table, which was the most requested change in this project.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-3.png)
Each row on the payments table contains information about a single transaction. Further details then show on an overlay when a row is clicked. We changed the layout of this detailed information from a whole page view, which took you away form the table, to an overlay, which keeps the user in the same space and allows them to return to the table more easily. We focused on improving readability of this section with an underline connecting labels with the content.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-4.png)
The old customers section was reported to not be very meaningful, with basic details failing to pull through. Working closely with the product manager, we planned out more meaningful information about customers, including bank account information and overview statistics. We then checked this was possible with the backend team before finalising the designs. This section will be developed further in the future to display in-depth insights on customer’s gambling behaviour.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-5.png)

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-6.png)
The settings area was improved with a vertical menu, replacing a horizontal tab approach that was filling most of the screen. During research we learnt that users often need to contact our support team, particularly in the beginning stages of setting up their dashboard, so we made this feature more prominent in the toolbar. Other less used features, including developer documentation and knowledge base, were kept within the user menu.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-7.png)
One simple but impactful improvement we brought in this redesign was feedback. When assessing the state of the previous dashboard we realised that many actions were process with little or no feedback, resulting in confusion or multiple clicks waiting for a change. Any actions that resulted in a change would now include visible feedback on the screen, including errors to meaningfully guide users.

![]({{ site.baseurl }}/assets/img/admin-dashboard/final-design-8.png)
We included the option to have a collapsed side panel in the redesign, to give users more space to see their information. This has been reported as particularly useful on data heavy pages, including those with a table and the webhooks display.


### TESTING
As we were redesigning an existing dashboard, we were carrying over most of the existing functionality. Our aim with testing was therefore primarily internal, to ensure this functionality had been preserved. A challenge we came up against here though was a lack of documentation for the existing functionality. We worked closely with our business analyst to identify a list of user scenarios which we could then check, which we did as a team. This massively improved our process for the future.

Due to time constraints and a lack of willing customers to test the designs externally, we are still in the process of collecting feedback on the dashboard, which will be encouraged through a feedback button on the main side bar which links to a survey. In our announcement of the new dashboard, customers have also been encouraged to reach out to their account managers should they have any comments.


### REFLECTION
It was great to work on this project at a new company, and contribute to improving process at a busy startup. This is an ongoing project, and after we release the dashboard, our attention is shifting to fixes that still need doing, and new sections that will be added. I do see many areas for improvement and have kept a list of ideas which I consistently add to, for example I would personally like to see more of the brand update making its way into the dashboard in certain areas and would enjoy working with the marketing team to make this happen. I also would like to engage with customers to collect more meaningful feedback.