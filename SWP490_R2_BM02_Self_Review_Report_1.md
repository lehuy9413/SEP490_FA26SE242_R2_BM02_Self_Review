**dSWP490 · CAPSTONE PROJECT · REVIEW 2 · BM02**

# **SRS/SDD Self-Review Report – Review 2**

*Form BM02. Run the standard prompt on the proposed final registration form and the repository at tag review-2. Keep every finding exactly as produced by the AI; add only the Team response column. Export to PDF. File name: SWP490\_\<ProjectCode\>\_R2\_SelfReview.pdf*

## **1\. Run Information**

| Project code |  |
| :---- | :---- |
| **Project name** |  |
| **Team** |  |
| **Supervisor** |  |
| **AI tool and model** |  |
| **Run date** |  |
| **Repository tag / commit** |  |
| **Registration form version used** |  |
| **Version** |  |
| **Date** |  |

## **2\. Standard Prompt**

*Use this prompt without modification.*

| You are reviewing the SRS and SDD of a software capstone project against its registration form and source code. Report only; do not change any file. Inputs: the registration form, SRS, SDD (with diagrams), source code and database script in this repository. Check: 1\. Scope: FRs in the SRS not covered by the registration form, and    registration items with no FR. 2\. Requirements: FRs without an actor or testable acceptance criteria;    NFRs without metric, threshold and measurement method. 3\. Data: entities missing from the Logical ERD; ERD entities or attributes    missing from the database script, and tables not in the ERD. 4\. States: for each main entity, states used in code but missing from its    state machine; transitions with no triggering FR; states with no exit. 5\. Flows: main business flows in activity diagrams with no implementation    or no test. 6\. Architecture: components or third-party services in code but not in the    architecture diagram, and the reverse. 7\. Design vs code: modules, APIs or business rules implemented differently    from the SDD. Output one table: ID \| Category \| Location \| Finding \| Severity (High/Medium/Low) \| Evidence. Then list the 5 most important findings. If something cannot be verified from the repository, say so; do not guess. |
| :---- |

## **3\. Findings and Team Response**

*Team response: Fixed (link to commit) · Kept (reason) · Planned (owner and due date). Do not delete any finding.*

| ID | Category | Location | Finding | Severity | Evidence | Team response |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| *SR-01* | *Data* | *SDD §4 ERD* | *Entity Voucher used in code but missing from ERD* | *High* | *Voucher.java* | *Fixed – commit a1b2c3d* |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |

## **4\. Top 5 Findings (as reported by the AI)**

| \# | Finding ID | Summary |
| :---- | :---- | :---- |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

## **5\. Summary**

| Severity | Total | Fixed | Kept | Planned |
| :---- | :---- | :---- | :---- | :---- |
| *High* |  |  |  |  |
| *Medium* |  |  |  |  |
| *Low* |  |  |  |  |

*Every High finding marked Kept or Planned must also appear in section 5 (Known Gaps) of the Design Brief.*