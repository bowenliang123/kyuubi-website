---
title: New Committer Process
menu:
    main:
        name: "New Committer Process"
        parent: "community"
        weight: 3 
---
<!---
  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License. See accompanying LICENSE file.
-->

<img src="https://svn.apache.org/repos/asf/comdev/project-logos/originals/kyuubi-1.svg" alt="Kyuubi logo" width="30%" align="right" />

This guideline is based on [apache newcommitter](https://community.apache.org/newcommitter.html#new-committer-process)

- [The process of new Committer](new_committer_process#the-process-of-new-committer)
    - [Call a vote in mailing `private@kyuubi.apache.org`](new_committer_process#call-a-vote-in-mailing-privatekyuubiapacheorg)
    - [Close the vote](new_committer_process#close-the-vote)
    - [If the result is positive, invite the new committer](new_committer_process#if-the-result-is-positive-invite-the-new-committer)
    - [If accept, then: Accept the committer](new_committer_process#if-accept-then-accept-the-committer)
    - [Wait until we see that receipt of CLA is recorded](new_committer_process#wait-until-we-see-that-receipt-of-cla-is-recorded)
    - [Request creation of the committer account](new_committer_process#request-creation-of-the-committer-account)
    - [Notify the committer of completion](new_committer_process#notify-the-committer-of-completion)
- [Template](new_committer_process#template)
    - [Committer Vote Template](new_committer_process#committer-vote-template)
    - [Close Vote Template](new_committer_process#close-vote-template)
    - [Committer Invite Template](new_committer_process#committer-invite-template)
    - [Committer Accept Template](new_committer_process#committer-accept-template)
    - [Committer Done Template](new_committer_process#committer-done-template)

## The process of new Committer

### Call a vote in mailing `private@kyuubi.apache.org`

see **Committer Vote Template**

### Close the vote

see **Close Vote Template**

### If the result is positive, invite the new committer

see **Committer Invite Template**

### If accept, then: Accept the committer

see **Committer Accept Template**

### Wait until we see that receipt of CLA is recorded

### Request creation of the committer account

see **Committer Account Creation**

- Wait until root says it is done
- PMC Chair enables svn and other access
- Add committer to the appropriate groups in JIRA and CWiki

### Notify the committer of completion

see **Committer Done Template**


## Template

Note that, there are three placeholder in template should be replaced before using

- NEW_COMMITTER_NAME
- NEW_COMMITTER_EMAIL
- NEW_COMMITTER_APACHE_NAME

### Committer Vote Template

```text
To: private@kyuubi.apache.org
Subject: [VOTE] New committer: ${NEW_COMMITTER_NAME}
```
```text
Hi Kyuubi PMC,

This is a formal vote about inviting ${NEW_COMMITTER_NAME} as our new committer.

${Work list}[1]

[1] https://github.com/apache/kyuubi/commits?author=${NEW_COMMITTER_NAME}
```

Note that, Voting ends one week from today, i.e. [midnight UTC on YYYY-MM-DD](https://www.timeanddate.com/counters/customcounter.html?year=YYYY&month=MM&day=DD)
See voting [guidelines](https://community.apache.org/newcommitter.html)


### Close Vote Template

```text
To: private@kyuubi.apache.org
Subject: [RESULT] [VOTE] New committer: ${NEW_COMMITTER_NAME}
```
```text
Hi Kyuubi PMC,

The vote has now closed. The results are:

Binding Votes:

+1 [TOTAL BINDING +1 VOTES]
 0 [TOTAL BINDING +0/-0 VOTES]
-1 [TOTAL BINDING -1 VOTES]

The vote is ***successful/not successful***
```

### Committer Invite Template

```text
To: ${NEW_COMMITTER_EMAIL}
Cc: private@kyuubi.apache.org
Subject: Invitation to become Kyuubi committer: ${NEW_COMMITTER_NAME}
```
```text
Hello ${NEW_COMMITTER_NAME},

The Kyuubi Project Management Committee (PMC) 
hereby offers you committer privileges to the project.
These privileges are offered on the understanding that
you'll use them reasonably and with common sense.
We like to work on trust rather than unnecessary constraints. 

Being a committer enables you to more easily make 
changes without needing to go through the patch 
submission process.

Being a committer does not require you to 
participate any more than you already do. It does 
tend to make one even more committed.  You will 
probably find that you spend more time here.

Of course, you can decline and instead remain as a 
contributor, participating as you do now.

A. This personal invitation is a chance for you to 
accept or decline in private.  Either way, please 
let us know in reply to the private@kyuubi.apache.org
address only.

B. If you accept, the next step is to register an iCLA:
    1. Details of the iCLA and the forms are found 
    through this link: https://www.apache.org/licenses/#clas

    2. Instructions for its completion and return to 
    the Secretary of the ASF are found at
    https://www.apache.org/licenses/#submitting

    3. When you transmit the completed iCLA, request 
    to notify the Apache Kyuubi and choose a 
    unique Apache ID. Look to see if your preferred 
    ID is already taken at 
    https://people.apache.org/committer-index.html
    This will allow the Secretary to notify the PMC 
    when your iCLA has been recorded.

When recording of your iCLA is noted, you will 
receive a follow-up message with the next steps for 
establishing you as a committer.
```

### Committer Accept Template

```text
To: ${NEW_COMMITTER_EMAIL}
Cc: private@kyuubi.apache.org
Subject: Re: invitation to become Kyuubi committer
```
```text
Welcome. Here are the next steps in becoming a project committer. After that
we will make an announcement to the dev@kyuubi.apache.org list.

You need to send a Contributor License Agreement to the ASF.
Normally you would send an Individual CLA. If you also make
contributions done in work time or using work resources,
see the Corporate CLA. Ask us if you have any issues.
https://www.apache.org/licenses/#clas.

You need to choose a preferred ASF user name and alternatives.
In order to ensure it is available you can view a list of taken IDs at
https://people.apache.org/committer-index.html

Please notify us when you have submitted the CLA and by what means 
you did so. This will enable us to monitor its progress.

We will arrange for your Apache user account when the CLA has 
been recorded.

After that is done, please make followup replies to the dev@kyuubi.apache.org list.
We generally discuss everything there and keep the
private@kyuubi.apache.org list for occasional matters which must be private.

The developer section of the website describes roles within the ASF and provides other
resources:
  https://www.apache.org/foundation/how-it-works.html
  https://www.apache.org/dev/

Just as before you became a committer, participation in any ASF community
requires adherence to the ASF Code of Conduct:
  https://www.apache.org/foundation/policies/conduct.html

Yours,
The Apache Kyuubi PMC
```

### Committer Done Template

```text
To: private@kyuubi.apache.org, ${NEW_COMMITTER_EMAIL}
Subject: account request: ${NEW_COMMITTER_NAME}
```
```text
${NEW_COMMITTER_NAME}, as you know, the ASF Infrastructure has set up your
committer account with the username '${NEW_COMMITTER_APACHE_NAME}'.

Please follow the instructions to set up your SSH,
svn password, svn configuration, email forwarding, etc.
https://www.apache.org/dev/#committers

You have commit access to specific sections of the
ASF repository, as follows:

The general "committers" at:
  https://svn.apache.org/repos/private/committers

If you have any questions during this phase, then please
see the following resources:

Apache developer's pages: https://www.apache.org/dev/

Naturally, if you don't understand anything be sure to ask us on the dev@kyuubi.apache.org mailing list. 
Documentation is maintained by volunteers and hence can be out-of-date and incomplete - of course
you can now help fix that.

A PMC member will announce your election to the dev list soon.
```
