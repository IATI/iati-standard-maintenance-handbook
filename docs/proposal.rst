===================
Managing A Proposal
===================

A proposal is the penultimate stage of making a change to the IATI Standard. It is preceded by consultation and research and, if unopposed, is followed by deployment. 

Stage the change
----------------

A proposal includes the specific, line-by-line change that is being proposed, to ensure that there is no ambiguity. 

This requires a GitHub pull request to be prepared which details the change. See instructions for:

* `embedded codelists <https://github.com/IATI/IATI-Codelists#downstream-updates>`_
* `non-embedded codelists <https://github.com/IATI/IATI-Internal-Wiki/blob/main/SSOT/IATI-Codelists-NonEmbedded.md>`_

Updates to the schema and rulesets are made through regular PRs on https://github.com/IATI/IATI-Schemas and https://github.com/IATI/IATI-Rulesets

Author the proposal
-------------------

Make a copy of the `proposal template <https://github.com/IATI/iati-standard-gazette/blob/main/docs/proposal-template.rst>`_ and fill it out with the relevant details. 

Make a copy of the `gazette template <https://github.com/IATI/iati-standard-gazette/blob/main/docs/gazette-template.rst>`_ and fill it out as well. 

Open a PR against https://github.com/IATI/iati-standard-gazette to preview the proposal and Gazette entry, and to prepare for publication. This  `proposal from June 2026 <https://github.com/IATI/iati-standard-gazette/pull/15/changes>`_ is a good example for reference.  

Once the date of publication has been agreed, update the PR on :code:`iati-standard-gazette` that you made earlier:

* Correct all dates and notice periods
* Add a note to the top of the proposal to note the Gazette circulation date
* Ask a colleague to review your work to check for any errors, inconsistencies, typos, etc

Publish the proposal 
--------------------

On the day of publication:

* Merge the pull request on iati-standard-gazette
* Copy the relevant details from the Gazette template into the Mailchimp email template (in Mailchimp itself) and send it to the Gazette mailing list

30/45 days later
----------------

Once the notified period has elapsed, assuming no objections:

* Update the note in the proposal to say that it's been accepted via a PR against iati-standard-gazette (see `example <https://github.com/IATI/iati-standard-gazette/pull/21>`_)
* Deploy the change