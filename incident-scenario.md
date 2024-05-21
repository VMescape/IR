# Incident Response Scenario

## Scenario Title: Unauthorized Access to Database

### Overview
On May 21, 2024, at 10:00 AM, the security team of Acme Corp identified unauthorized access to their customer database. The database contains sensitive customer information, including names, addresses, and payment details.

### Incident Details
- **Date and Time Detected**: May 21, 2024, 10:00 AM
- **Detected By**: SIEM detection
- **System Affected**: Customer Database Server
- **Type of Incident**: Unauthorized Access
- **Impact**: P1
  
### Incident Response Team
- **Incident Response Manager**: JP Haywood
- **Incident Response Officer**: Tony Bianco

### Response Actions

#### 1. Identification
- **Action**: Verify the unauthorized access
  - **Details**: Check database logs for unusual access patterns and identify the entry point.
  - **Responsible**: Incident Response Officer (Tony Bianco)
  - **Timestamp**: May 21, 2024, 10:15 AM

#### 2. Containment
- **Action**: Isolate the affected database server from the network
  - **Details**: Remove the server from the network to prevent further access.
  - **Responsible**: Incident Response Officer (Tony Bianco)
  - **Timestamp**: May 21, 2024, 10:30 AM

#### 3. Eradication
- **Action**: Remove malicious software and secure the entry point
  - **Details**: Perform a thorough scan and remove any detected malware. Patch vulnerabilities exploited for access.
  - **Responsible**: System Administrator 
  - **Timestamp**: May 21, 2024, 11:00 AM

#### 4. Recovery
- **Action**: Restore database from backup
  - **Details**: Restore the database from the last known good backup and verify its integrity.
  - **Responsible**: Database Administrator
  - **Timestamp**: May 21, 2024, 12:00 PM

#### 5. Lessons Learned
- **Action**: Conduct a post-incident review
  - **Details**: Analyze the incident, identify root causes, and implement measures to prevent future occurrences.
  - **Responsible**: Incident Response Manager
  - **Timestamp**: May 22, 2024, 9
