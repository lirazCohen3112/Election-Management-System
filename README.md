
Project presentation: https://drive.google.com/file/d/11hNzzSpgwSvPbYQo-K8oarRkB0Sedtbr/view

Election Data Management System Project - Development and Maintenance of a Database Using MySQL

In this project, I developed a comprehensive and secure data management system for the election process, including the management of data related to parties, candidates, voters, votes, regions, polling stations, observers, and reports. The system is based on a MySQL database and is designed to streamline, organize, and analyze election data.

Key Aspects of the Project:

- Database Development: Designed and created the overall structure of the database, including tables such as parties, candidates, voters, votes, regions, and polling stations.

- Use of TRIGGERS: Implemented triggers to ensure data integrity, including:
  - Validation before adding votes, such as ensuring that a voter has not voted in the same election.
  - Verifying that the candidate is running in the election before adding votes.
  - Preventing the deletion of candidates if they have existing votes.

- Writing PROCEDURES and Functions:
  - Developed functions to calculate voting percentages for candidates and the average age of voters who participated in multiple elections.
  - Created procedures to query data based on various criteria, including candidate details, last names, and identifying the election winner.

- Advanced Queries:
  - Executed a variety of complex queries, including:
    - Identifying the region with the most polling stations.
    - Searching for voters who have voted in more than one election.
    - Generating reports that display information about votes and candidates.

- Enforcing Data Integrity: Through triggers and pre-checks, the system ensures the validity of votes, election consistency, and data integrity.

- Teamwork and Productivity: Collaborated with a team to develop system improvements and upgrades, including optimizing performance and expanding analytical capabilities.
