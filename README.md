# mmci-versioncontrol-assignment
Team 3s Version Control Deliverable

+ Description of Use Case
+ Why is it a good use of version control (Git/Github)?
+ Where does it fall short in leveraging version control tools?
+ What would you do differently?
  + With the push for organizations to follow HIE standards set forth by the ONC, use of version control for development and amendments to the legal documents outlining these standards is imperative.  Guidelines for management of such documents using a version control tool like Git should be established, allowing for more efficient and streamlined governance over shared agreements, such as the DURSA.  Recommendations for Git utilization include:
    - An organization at the federal level for the ONC or, more specifically, the NHIN.
      - Designated members of NHIN governance hold admin rights. 
      - Public and private entities request membership to the organization and granted appropriate read-write priveleges.
    
    - Repositories under the federal organization for legal documents categorized by type.
      - Should include instructions and standards for accessing and contributing to documents for organizations to follow a structured version control process. 
    
    - Inidividual Documents (ex: DURSA) with branches for each section.
      - Public and private entities able to fork repositories to their individual projects for amendments to terms.
      - Groups within these organizations able to follow the same process and make amendments to specific sections of the document.
      - Organizations create pull requests to have their updated terms merged with the master document.
      - NHIN governance admin or SME responsible for accepting changes and merge with the master document or send back for denial or revisions. 
    
    - Establishment of security standards for all contributing parties, from federal to local organizations, as well as for teams within those entities for improved awareness and more efficient management of versions. 
