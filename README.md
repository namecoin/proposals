IFA RFCs
========

| Number       | Title                    | Type     | Status   |
|--------------|--------------------------|----------|----------|
| [0000][0000] | RFC Guidelines & Process | Process  | Draft    |
| [0001][0001] | Domain Names             | Standard | Draft    |

*This list does not contain RFCs that have been deferred, rejected, or withdrawn.*

[0000]:https://github.com/ifa-wg/rfc/blob/master/ifa-0000.md
[0001]:https://github.com/ifa-wg/rfc/blob/master/ifa-0001.md

How-To
=======
Those wishing to submit an RFC should first should propose their idea to the relevant communities and then submit a new RFC as outlined in the [RFC Guidelines & Process][0000].

Discussion relevant to a **pending** draft should, whenever possible, take the form of Gitub issue tickets. Github tickets should reference the RFC and/or pull requests to help ensure that all discussion is captured.  

You can clone this repository using:

	git clone https://github.com/ifa-wg/rfc ifa-rfc

Before submitting a PR for a new RFC or to update an existing RFC, install and run DocToc:

	npm install -g doctoc
	doctoc ifa-rfc/ifa-000x.md --title '**Table of Contents**'

You must include DocToc markup in the document before running DocToc:

	 <!-- START doctoc -->
	 <!-- END doctoc -->