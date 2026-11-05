# Design and technical

Prompts for design management and technical review.

## Design review comments

**Use it for:** consolidating review comments from several people into one clear response.

~~~
You are an experienced design manager. Consolidate the design review comments below into a single comments schedule for [package or document, revision].

Columns: Ref, Drawing or section, Comment, Reviewer, Category (compliance / coordination / buildability / cost / clarification), Priority (high / medium / low), Action required.

Merge duplicates. Flag comments that conflict with each other. Do not change the technical meaning of any comment.

Comments: [paste]
~~~

**Check before you use it:**
- Merged comments still say what each reviewer meant
- Conflicting comments are resolved by a person, not the AI

## Specification compliance check

**Use it for:** a first pass comparing a product or proposal against the specification.

~~~
You are an experienced technical manager. Compare the product data below against the specification clause.

Specification clause: [paste]
Product or proposal: [paste data sheet text]

Produce a table: Requirement, Specified, Proposed, Compliant (yes / no / unclear), Comment.
Then list the questions to send to the supplier for anything unclear.
~~~

**Check before you use it:**
- Performance values are checked against the original documents
- Certification and test standards are checked by a competent person

## Submittal review

**Use it for:** reviewing a subcontractor or supplier submittal before it goes to the design team.

~~~
You are an experienced design manager. Review the submittal below for [package].

Check it against: [the specification clause, drawings and any previous comments, pasted below]

Report:
1. Completeness: what is missing
2. Apparent non-compliances
3. Coordination issues with other packages
4. Recommended status: approved / approved with comments / revise and resubmit
5. Draft comments to return to the subcontractor

Submittal: [paste]
Reference documents: [paste]
~~~

**Check before you use it:**
- The recommended status is a recommendation, not a decision
- Design responsibility under the contract is respected

## Technical query

**Use it for:** raising a technical query with a manufacturer or specialist.

~~~
You are a technical manager. Draft a technical query to [manufacturer or specialist] about [product or system].

Context: [where it is being used and the conditions]
Question: [what we need to know]
Standards or regulations that apply: [list]
Answer needed by: [date]

Clear, specific questions that can be answered in writing. Under 200 words.
~~~

**Check before you use it:**
- Project details shared externally are appropriate to share
