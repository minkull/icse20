# Call for Artifact Submissions

Authors of **papers accepted to the Technical Track** are invited to submit an artifact to the ICSE Artifact Track
for evaluation as a candidate **functional, reusable, available** artifact.
If the artifact is accepted it will receive one of the following badges on the front page of their paper and in the proceedings.

Authors of any prior SE work are 
are invited to submit an artifact to the ICSE Artifact Track
for evaluation as a candidate **replicated, reproduced** artifact.
If the artifact is accepted:

- Authors will be invited to give a lightning talk on this work at ICSE'20
- We will work with the IEEE Xplore and ACM Portal administrator to add badge the electronic version of their paper.

<table>
<thead></thead>
<tbody>
<tr><td><strong>Functional</strong>	</td><td align="center"> <strong>Reusable</strong> </td><td align="center"> <strong>Available</strong></td><td align="center"> <strong>Replicated</strong> </td><td align="center"> <strong>Reproduced</strong> </td></tr>
<tr><td>No Badge </td><td align="center"> <dl><img src="https://2019.icse-conferences.org/getImage/orig/red.jpg" alt=""></dl>  </td><td align="center"> <dl><img src="https://2019.icse-conferences.org/getImage/orig/green.jpg" alt=""></dl>	   </td><td align="center">  <dl><img src="https://2019.icse-conferences.org/getImage/orig/blue.jpg" alt=""></dl> </td><td align="center">  <dl><img src="https://2019.icse-conferences.org/getImage/orig/deepBlue.jpg" alt=""></dl> </td></tr>
<tr><td> <!--Functional--> Artifacts documented, consistent, complete, exercisable, and include appropriate evidence of verification and validation </td><td align="center"> <!--Reusable--> Functional + very carefully documented and well-structured to the extent that reuse and repurposing is facilitated. In particular, norms and standards of the research community for artifacts of this type are strictly adhered to. </td><td align="center"> <!--Available-->  Functional + Placed on a publicly accessible archival repository. A DOI or link to this repository along with a unique identifier for the object is provided. </td><td align="center"> <!--Replicated--> Available + main results of the paper have been obtained in a subsequent study by a person or team other than the authors, using, in part, artifacts provided by the author. </td><td align="center"> <!--Reproduced--> Available + The main results of the paper have been independently obtained in a subsequent study by a person or team other than the authors, without the use of author-supplied artifacts.</td></tr>
</tbody>
</table>


Papers with such badges contain reusable products that other researchers can use to bootstrap their own research. Experience shows that such papers earn increased citations and greater prestige in the research community. Artifacts of interest include (but are not limited to) the following.

- Software, which are implementations of systems or algorithms potentially useful in other studies.

- Data repositories, which are data (e.g., logging data, system traces, survey raw data) that can be used for multiple software engineering approaches.

- Frameworks, which are tools and services illustrating new approaches to software engineering that could be used by other researchers in different contexts.

This list is not exhaustive, so the authors are asked to email the chairs before submitting if their proposed artifact is not on this list.


## Evaluation Criteria

The ICSE artifact evaluation track uses a single-blind review process. Artifacts will be evaluated using the criteria in the last row of the above table.

Review will be via Github. All submitting authors must supply a valid Github id that identifies themselves.

The goal of this track is to encourage reusable research products. Hence, no **functional** badges will be awarded. 

## Best Artifact Awards

There will be two ICSE 2019 Best Artifact Awards to recognize the effort of authors creating and sharing outstanding research artifacts.

## Submission and Review

**IMPORTANT NOTE**: different badges have different submission procedures. See below.

### For Replicated and Reproduced Badges

For the badges “replicated” and “reproduced” authors will need to offer appropriate documentation that their artifacts have reached that stage. 

For these badges, the submission process is to offer a one page (max) abstract in PDF format:

- TITLE: **A (Partial)? (Replication|Reproduction) of XYZ**. Please add the term **partial**to your title if only some of the original work could be replicated/reproduced.
- WHO: name the original authors (and paper) and the authors that performed the replication/reproduction.
  Include contact information (emails). Mark one author as the corresponding author.
- WHAT: describe the "thing" being replicated/reproduced;
- WHY: clearly state why that "thing" is interesting/important;
- HOW: say how it was done first
- WHERE: describe the replication/reproduction. If the replication/reproduction was only partial, then explain what parts could be achieved or had to be missed.
- DISCUSSION: What aspects of this thing made it easier/harder to replicate/reproduce. What are the lessons learned from this work that would enable more replication/reproduction in the future for other kinds of tasks or other kinds of research.

2 PC members will review each abstract, possibly reaching out to the authors of the original Paper1. Abstracts will be ranked as follows.

- If pc members do not find sufficient substantive evidence for replication/reproduction, the abstract will be rejected.
- Any abstract that is overly critical of prior work, it will be rejected (\*).
- The remaining abstracts will be sorted according to (a) interestingness and (b) correctness.
- The top ranked abstracts will be invited to give lightning talks.

(\*) Our goal is to foster a positive environment that supports and
rewards researchers for conducting replications and reproductions. To
that end, we require that all abstracts and presentations pay due respect
to the work they are reproducing/replicating. Criticisms of prior work
is acceptable only as part of a balanced and substantive discussion of
prior accomplishments.


### For Reusable and Available Badgers

For the badges **reusable** and **available** badges, authors must supply some download information showing how
reviewers can access and execute (if appropriate) their artifact.

Authors of the papers accepted to the Technical Track must perform the following steps to submit an artifact:

- Preparing the artifact
- Making the artifact available
- Documenting the artifact
- Submitting the artifact

**1. PREPARING THE ARTIFACT**

There are two options depending on the nature of the artifacts: Installation Package or Simple Package. In both cases, the configuration and installation for the artifact should take less than 30 minutes. Otherwise the artifact is unlikely to be endorsed simply because the committee will not have sufficient time to evaluate it.

_Installation Package_ If the artifact consists of a tool or software system, then the authors need to prepare an installation package so that the tool can be installed and run in the evaluator’s environment. Provide enough associated instruction, code, and data such that some CS person with a reasonable knowledge of scripting, build tools, etc. could install, build, and run the code. If the artifact contains or requires the use of a special tool or any other non-trivial piece of software the authors must provide a VirtualBox VM image or a Docker container image with a working environment containing the artifact and all the necessary tools.

We expect that the artifacts have been vetted on a clean machine before submission.

_Simple Package_ If the artifact only contains documents which can be used with a simple text editor, a PDF viewer, or some other common tool (e.g., a spreadsheet program in its basic configuration) the authors can just save all documents in a single package file (zip or tar.gz).

**2. MAKING THE ARTIFACT AVAILABLE**

The authors need to make the packaged artifact (installation package or simple package) available so that the Evaluation Committee can access it. We suggest a link to a public repository or to a single archive file in a widely available archive format. If the authors are aiming for the badges “available” and beyond the artifact needs to publicly accessible. In other cases, the artifacts do not necessarily have to be publicly accessible for the review process. In this case, the authors are asked to provide a private link or a password-protected link.

**3. DOCUMENTING THE ARTIFACT**

The authors need to write and submit a documentation explaining how to obtain the artifact package, how to unpack the artifact, how to get started, and how to use the artifacts in more detail. The artifact submission must only describe the technicalities of the artifacts and uses of the artifact that are not already described in the paper. The submission should contain the following documents (in 
**markdown** plain text format) in a zip archive:

- A _CONTACT.md_ file listing emails and **github ids** (important) for the authors. Please mark one author as the _corresponding author_.
- A _README.md_ main file describing what the artifact does and where it can be obtained (with hidden links and access password if necessary). Also, there should be a clear description how to reproduce the results presented in the paper.
- A _STATUS.md_ file stating what kind of badge(s) the authors are applying for as well as the reasons why the authors believe that the artifact deserves that badge(s).
- A _LICENSE.md_ file describing the distribution rights. Note that to score "available" or higher, then that license needs to be some form of open source license.
- An _INSTALL.md_ file with installation instructions. These instructions should include notes illustrating a very basic usage example or a method to test the installation. This could be, for instance, on what output to expect that confirms that the code is installed and working; and the code is doing something interesting and useful.
- A copy of the accepted paper in pdf format.

**4. SUBMITTING THE ARTIFACT**

By January 15, 2020 register your research artifact at the ICSE submission site (URL TBD) by submitting an abstract describing your artifact. The abstract should include the paper title, the purpose of the research artifact, the badge(s) you are claiming, and the technology skills assumed by the reviewer evaluating the artifact. Please also mention if running your artifact requires specific Operation Systems or other environments.

By January 27, 2020 complete your artifact submission by uploading the materials described above. **IMPORTANT NOTE**: recall from
the above above that different badges require different materials.

For replicated and  reproduced  badges, results will be notified at the end of the reviewing process.

For reusable and available badges, the review process will be interactive.

- Reviewing will be on Github with reviewers commenting via anonymous Github ids. Authors should not comment until
at least two reviewers have added comments. Earlier author comments will be deleted.
- Prior to reviewing, there may be some interactions to handle set up and install.
Before the actual evaluation reviewers will check the integrity of the
artifact and look for any possible setup problems that may prevent it from
being properly evaluated (e.g., corrupted or missing files, VM won’t
start, immediate crashes on the simplest example, etc.). The Evaluation
Committee may contact the authors to request
clarifications on the basic installation and start-up procedures or to
resolve simple installation problems. Authors are informed of the outcome
and, in case of technical problems, they can help solve them during a
brief author response period. Given the short review time available,
the authors are expected to respond within a 48-hour period. Authors may
update their research artifact after submission only for changes requested
by reviewers in the rebuttal phase. Author submitting an open source
repository link, are expected to give a tag to time-stamp your submission.


## REVIEW COMMITTEE

TBD

## IMPORTANT DATES

Jan15: Pre-submission registration
Jan27: Submission deadline
Feb01: Review period (\*)
Feb20: Rebuttal period ends.
Feb24: Notifications
Feb25: Send list of artifacts badges to web chairs and proceeding chairs

(\*) : For the available and reusable badges, reviewing will be on Github with reviewers commenting via anonymous Github ids. Authors should not comment until
at least two reviewers have added comments. Earlier author comments will be deleted.



