# Cyber-Task-16
1. Incident Response ReportIncident ID: IR-2026-001 Incident Type: Brute Force / Unauthorized Access Simulation +1Severity: Medium Executive SummaryThis report details a simulated security incident involving repeated failed login attempts aimed at gaining unauthorized access to a system. The activity was identified through manual log analysis and successfully contained by isolating the target account.+3Incident DetailsDetection Method: Analysis of system and authentication logs using Windows Event Viewer/Linux Logs.+1Root Cause: Weak credential policy allowing for automated password guessing.Containment: The affected account was temporarily disabled and the source IP was blocked.Eradication: Malicious scripts were removed, and the account password was reset.Preventive Recommendations Implement a robust account lockout policy after three failed attempts.Enforce Multi-Factor Authentication (MFA) for all system logins.Configure automated alerts for high-frequency authentication failures.
2. 2. Incident Timeline Document Time (IST)Action TakenPhase
   3. 10:00 AMSimulation of repeated failed login attempts initiated.Simulation
   4. 10:30 AMSuspicious activity identified via Windows Event ID 4625 (Failed Login).+1Identification
   5. 11:00 AMAttack classified as Brute Force; affected system isolated from the network.Containment
   6. 11:45 AMRoot cause identified as "admin" account vulnerability; threat removed.Eradication
   7. 12:30 PMSystem restored to secure state and monitored for further activity.Recovery
   8. 01:00 PMFinal documentation of timeline and actions completed.Lessons Learned
