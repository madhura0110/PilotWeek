# PilotWeek

Aim:
	- Pilot Week project aims at providing hands-on case handling experience to new engineers through mock cases for an entire week, before they start working on 'real' customer cases. Engineers will be real DFM cases where they can experience meeting SLAs, researching an issue, logging quality notes, calling customers on the phone etc. TA or Buddy will be the customer and present technical issues for the new engineer to solve.

Expected Impact:
	- Better CSAT, fewer escalations
	- Morale & Confidence boost
	- Streamlined process to make new engineers live -> long term benefits

Each mock case interaction has these components in common:
	- DFM case process (SLA, Notes, SAP, Labor)
	- Customer interaction (Email etiquettes and/or phone etiquettes)
	- Troubleshooting a technical issue (Research, repro, data analysis, draw conclusions, unsupported tech/issue)
	- Familiarity with tools Using 

Examples scenarios:
	- Config: App giving HTTP 403 (Solution: IP restriction)
	- Perf: Timeout HTTP 500.121 (Solution: hardcoded timeout within the app)
	- Dev: Azure Functions Runtime unreachable (Solution: Storage unreachable)
	- OSS: Unable to SSH on KUDU (Solution: Image does not have SSH enabled)

Implementation:
	- OneNote/Website/Dynamics page that guides step-by-step. Provide access only to TA/Buddy
	- You can customize the cases you want to use for that engineer (this way, this is scalable even when we move into a vertical model)
	- The best way to get these scenarios is to have an ARM template deploy those resources for you by the click of a button. ARM templates will be stored in a GitHub repository.
