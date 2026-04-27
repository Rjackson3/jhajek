# Sprint-03

## Self-Critique

### My Role: Ryan Jackson,Developer

**In Sprint‑03, I took on the role of Lead Developer, and I was primarily responsible for implementing the Faker and creating the Loggin Sequence Diagram as well as assisting the team with debugging.**

### Assigned Tasks and Artifacts

**1. `Faker`**

Commit: 080f9e3 Updated Generate_Users to fit the application - Rjackson3 
PM Card:Dev - Add 25 simulated users and posts/operations using faker (3pts)

**2. MySQL changes**

Commit: 15090b4 focused the controller ip to 10.110.%.% - Rjackson3
PM Card: Dev - Troubleshoot production deployment issues (5pts)

**3. Loggin Sequence Diagram
Commit:a5f62f9 Add logging sequence diagram - Rjackson3
PM Card: Dev - Mermaid sequence diagram for logging in (2pts)


### Self-Critique and Areas of Improvement

**What went wall:** 

- I was able to deliver functional additions to the application and I fixed several deployment mismatches
- I was very open with what I don't know so when I did need to communicate during debugging I was very communicative and open

**Where I can improve:**

- There was a mishap where both me and Hamza were pushing the same change at the same time because I thought I would just do it myself so communicating who's doing what during debugging is an improvement I could make
-  
-

## Group Critique
### Emily Xu — [IT Ops]
Assigned Tasks:

Build and manage Packer VM templates
Deploy full stack using Terraform
Implement Vault secrets (KV, AppRole, DB, MinIO)
Remove hard‑coded secrets
Configure DB replication
Configure MinIO object storage
Validate firewall and API security
Demonstrate load balancer failover

What They Completed:
✅ Infrastructure fully deployed on Proxmox using Terraform
✅ VM templates successfully built with Packer
✅ Vault used for all secrets (no plaintext credentials)
✅ DB replication implemented and verified
✅ MinIO deployed and accessible via SDK
✅ Load balancer demoed live by terminating two instances
✅ Deployment process reproducible from scratch

What Blocked Them:
None

Areas of Strength:

Excellent communication
Proactive about checking on blockers

Areas for Improvement:




### Bezeleel Manor — [Developer 2]
Assigned Tasks:

Adjust application code for DB read/write separation
Support implementation of read replicas
Integrate MinIO object storage for media

What They Completed:
✅ Updated data access logic so writes go to the primary DB and reads go to replicas
✅ Supported MinIO SDK integration and verified media uploads
✅ Confirmed no hard‑coded secrets remained in the codebase

What Blocked Them:
None

Areas of Strength:

Proactive about checking on blockers
Completed tasks effeciently

Areas for Improvement:

Could be more communicative throughout the sprint

### Adam Lazarowicz — [PM]
Assigned Tasks:

Rotate roles immediately after Sprint‑02
Capture Sprint‑03 start state and end state
Break work into atomic tasks totaling 25 points
Ensure professor‑required items were included
Prepare and deliver the live Sprint‑03 presentation
Submit consolidated sprint‑03/report.md

What They Completed:
✅ Roles were rotated at the beginning of the sprint
✅ PM board included point values, owners, and required artifacts
✅ Sprint‑03 start state and changes were clearly documented
✅ Progress was tracked consistently throughout the sprint
✅ Blockers (DB replication and MinIO integration) were identified early and swarmed
✅ Report aggregated infrastructure, application, and testing artifacts

What Blocked Them:
Poor comminication: We barely heard from him most of the sprint and during the end he came back and needed to get in but it is partially on us for being unable to meet with him to discuss his role

Areas of Strength:
Even with the limitations of his schedule/communication he still made an active effort to be apart of the project.

Areas for Improvement:

Could be more proactive in communicating his schedule so we can equitably divide the workload and expectations. 

### Mohammad (Hamza) Khiyani — [UI/UX]
Assigned Tasks:

Test the production deployment (not localhost)
Perform real user workflows (login, post, reply, logout)
Log bugs using GitHub Issues
Track fixes and unresolved issues
Provide usability feedback under simulated load

What They Completed:
✅ Tested full user workflows in production
✅ Logged multiple GitHub Issues with reproduction steps
✅ Verified UI alignment with Sprint‑01 design
✅ Retested issues once fixes were deployed
✅ Identified usability concerns under simulated activity

What Blocked Them:
His tasks are partially reliant on the developers so his part comes near the end of the sprint

Areas of Strength:

Excellent communication with team and professor
Proactive about checking on blockers
Actively assisted in transition of roles and was still a major debugging force

Areas for Improvement:


