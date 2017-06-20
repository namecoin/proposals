IFA Proposals
=============

| Number       | Title                                      | Type     | Status   |
|--------------|--------------------------------------------|----------|----------|
| [0000][0000] | Proposal Guidelines & Process              | Process  | Draft    |
| [0001][0001] | Domain Names                               | Standard | Draft    |
| [0002][0002] | Domain Names - Non-DNS Types               | Standard | Draft    |
| [0003][0003] | Domain Names - Dehydrated TLS Certificates | Standard | Draft    |

*This list does not contain proposals that have been deferred, rejected, or withdrawn.*

[0000]:https://github.com/ifa-wg/proposals/blob/master/ifa-0000.md
[0001]:https://github.com/ifa-wg/proposals/blob/master/ifa-0001.md
[0002]:https://github.com/ifa-wg/proposals/blob/master/ifa-0002.md
[0003]:https://github.com/ifa-wg/proposals/blob/master/ifa-0003.md

How-To
=======
Those wishing to submit a proposal should first should bring their idea to the relevant communities and then submit a new proposal as outlined in the [Proposal Guidelines & Process][0000].

Discussion relevant to a pending draft should, whenever possible, take the form of Gitub issue tickets. Github tickets should reference the proposal and/or pull requests to help ensure that all discussion is captured.  

You can clone this repository using:

	git clone https://github.com/ifa-wg/proposals ifa-proposals

Before submitting a PR for a new proposal or to update an existing proposal, install and run DocToc:

	npm install -g doctoc
	doctoc ifa-proposals/ifa-000x.md --title '**Table of Contents**'

You must include DocToc markup in the document before running DocToc:

	 <!-- START doctoc -->
	 <!-- END doctoc -->
