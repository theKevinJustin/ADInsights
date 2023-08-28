# ADInsights
Proactive.Microsoft.Windows.Server.AD.Account.Password.Customizations 1.0.3.8

Download here

Proactive Microsoft Windows Server AD 2016 Account Password Customizations - Multiple datasources for group and user changes, password check monitor and rule alert reports, on-demand tasks for report workflows, and lastly, DC Security events for Datamart ingestion.

Version History:
v1.0.3.8   8 Jun 2023 - Updated Event rule 4634 to rule out computer logouts
v1.0.3.7   6 Jun 2023 - Updated Event rules to DW, reports to informational alerts,PasswordCheck DS/WA
v1.0.3.5  21 Mar 2023 - Removed ID blocks, Event collection rules, disabled alert rules
v1.0.3.4   8 Feb 2023 - Updated Account password/expiring report, scheduler to weekly,AppOwner alerts, tweaked rules for DODVisitor
v1.0.3.3   8 Feb 2023 - Updated Lockout Monitor to 300/hour, standard alert text display strings, changed rules to ContainsSubstring
v1.0.3.1   7 Feb 2023 - Updated Lockout Monitors, count, added AD DC Security event rules, Alert string tuning
v1.0.2.8  30 Jan 2023 - Updated PasswordCheck DataSources with additional teams
v1.0.2.7   9 Nov 2022 - Updated PasswordCheck DataSources with additional teams
v1.0.2.6  29 Aug 2022 - Updated PasswordCheck DS for additional teams
v1.0.2.4  11 Aug 2022 - Updated Microsoft.Windows.Server.AD.PasswordCheck.Monitor DS/WA
v1.0.2.0   1 Aug 2022 - Updated DS timeouts, added third customer stanza to DS/WA, hidden character cleanup
v1.0.1.7  29 Jun 2022 - Security Event rules and scripts, Updated 4720,4726,4728,4729 events and PowerShell scripts
v1.0.0.11  3 Mar 2022 - Updated RegEx, DS and WA for reports, 4722 enabling disabled ID
v1.0.0.7  24 Feb 2022 - Added for 4720,4728 events with RegEx, specific account lockout, Expiring, LastPassSet, WA, Task
v1.0.0.0  25 Aug 2021 - KWJ - Pack addresses group changes, password last set, expiring, auth failures, and lockout alerts.


Proactive Microsoft Windows Server NEC AD 2016 Account Password Customizations 1.0.0.4

Download here

Proactive Microsoft Windows Server NEC AD 2016 Account Password Customizations - Multiple datasources for group changes, including rule and demand tasks for report workflows.

Version History:
v1.0.0.3  11 Jul 2023 - Added Alert rules for PasswordCheck DS/Task/WA
v1.0.0.1   8 Jun 2023 - Updated rules to include NEC for subscription purposes - Microsoft Windows Server NEC DC Security EventID 472
v1.0.0.0   6 Jun 2023 - Created to check NEC AD OU's, alert on DC Security EventID's 4728, 4729 for NEC RC OU named groups
