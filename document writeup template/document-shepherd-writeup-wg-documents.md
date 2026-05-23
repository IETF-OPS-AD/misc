# Document Shepherd Write-Up for Working Group Documents

   *This version is dated x X 2026.*

   Thank you for your service as a document shepherd. One of the
   responsibilities of the shepherd is to answer the questions in this
   write-up to provide helpful context to Last Call and Internet
   Engineering Steering Group ([IESG][1]) reviewers.  Your diligence in
   completing it is appreciated.  The full role of the shepherd is
   further described in [RFC 4858][2].  You will need at least the
   cooperation of the authors and editors to complete these checks.

   Note that some numbered items contain multiple related questions;
   please be sure to answer all of them.

## Document History

   1.   Does the working group (WG) consensus represent the strong
        concurrence of a few individuals, with others being silent, or
        was a broad agreement reached?

   2.   Was there controversy about particular points, or were there
        decisions where the consensus was particularly rough?

   3.   Has anyone threatened an appeal or otherwise indicated extreme
        discontent?  If so, please summarize the areas of conflict in
        separate email messages to the responsible Area Director.
        (NOTE: This should be in a separate email because this filled
        questionnaire will be publicly available.)

   4.   For protocol documents, are there existing implementations of
        the contents of the document?  If so, are those implementations
        reported somewhere, either in the document itself (as [RFC
        7942][3] recommends) or elsewhere (please state where)?

        Have potential implementers indicated their plans to
        implement?

## Additional Reviews

   5.   Have reviews for the document happened in other IETF WGs or
        external organizations?  If so, please provide references to
        those reviews.

   6.   Describe how the document meets any required formal expert
        review criteria, such as the YANG Doctor, media type, and URI
        reviews.

   7.   If the document contains a YANG module, does the document’s
        Datatracker page indicate that it has no errors and warnings?

        Has a YANGDOCTOR review been done on a recent version,
        indicating that it is ready for publication?

        Does the document use the various templates in RFC 9907
        (mainly, YANG module, Security, and IANA templates)?

   8.   Describe reviews and automated checks performed to validate
        sections of the document written in a formal language, such as
        XML, JSON code, ABNF/RBNF/BNF rules, ASN.1, CBOR's CDDL, etc.

## Document Shepherd Checks

   9.   Will publication of the document be consistent with the
        chartered objectives and deliverables of the WG?  In the
        shepherd’s opinion which charter text covers the content of the
        document?

   10.  Based on your review, is this document clearly written,
        complete, technically accurate, correctly designed, and ready to
        be handed off to the responsible Area Director?

   11.  Several IETF Areas have assembled [lists of common issues that
        their reviewers encounter][6].  Have such issues been identified
        and addressed?  For which area does this still need to happen in
        subsequent reviews?

   12.  What type of RFC publication is being requested ([Best Current
        Practice][12], [Proposed Standard, Internet Standard][13],
        [Informational, Experimental or Historic][14])?

        Why is this the appropriate type of RFC?

   13.  If the document uses BCP 14 key words [18], does the document
        follow the guidance in [19]?

        Have you noted any unclear or inappropriate use of key words?

   14.  Have reasonable efforts (e.g., WGLC via the Datatracker) been
        made to remind the WG of the intellectual property rights (IPR)
        disclosure obligations described in [BCP 79][7]?

        Please summarize any relevant discussion, including links to
        publicly available messages when applicable.

   15.  Has each author, editor, and contributor shown their willingness
        to be listed as such?

        If the total number of authors and editors on the front page
        is greater than five, please provide a justification.

   16.  Please list any remaining I-D nits in the version of the
        document you reviewed that you feel are actual errors. Simply
        running the [idnits tool][8] is not enough; please review
        the ["Content Guidelines" on authors.ietf.org][15].  Idnits may
        display false positives; please flag those and please briefly
        explain as needed.

        (NOTE: No need to provide explanation for common false positives
        that are self-explanatory such as the existence of a newer version
        of referenced I-D)
                
### Document References

   17.  Should any informative references be normative or vice-versa?
        See the [IESG Statement on Normative and Informative
        References][16].

   18.  List any normative references that are not freely available to
        anyone.  Did the community have sufficient access to review any
        such normative references?

   19.  Are there any normative downward references (see [RFC 3967][9]
        and [BCP 97][10]) that are not already listed in the [DOWNREF
        registry][17]?  If so, please list them.

   20.  Are there normative references to documents that are not ready
        to be submitted to the IESG for publication or are otherwise in
        an unclear state?  If so, what is the plan for their completion?

   21.  Will publication of this document change the status of any
        existing RFC(s)?  If so, does the Datatracker metadata correctly
        list those RFCs on the title page, in the abstract, and in the
        introduction?

### IANA Considerations

   22.  Describe your review of the IANA considerations section,
        especially its consistency with the body of the document.

        Confirm that all IANA requested actions are associated with
        the appropriate reservations in IANA registries.

        Confirm that any referenced IANA registries have been clearly
        identified.

        Confirm that each newly created IANA registry specifies its
        initial contents, allocation procedures, and a reasonable
        name (see [RFC 8126][11]).

   23.  List any new IANA registries that require Designated Expert
        Review for future allocations (Expert Review, Specification
        Required). If any, please confirm that the document includes
        guidelines for Designated Experts.  Are these instructions to
        the Designated Expert clear?
    

[1]: https://www.ietf.org/about/groups/iesg/ 
[2]: https://www.rfc-editor.org/rfc/rfc4858.html 
[3]: https://www.rfc-editor.org/rfc/rfc7942.html 
[4]: https://wiki.ietf.org/group/ops/yang-review-tools 
[5]: https://www.rfc-editor.org/rfc/rfc8342.html 
[6]: https://wiki.ietf.org/group/iesg/ExpertTopics 
[7]: https://www.rfc-editor.org/info/bcp79 
[8]: https://www.ietf.org/tools/idnits/ 
[9]: https://www.rfc-editor.org/rfc/rfc3967.html 
[10]: https://www.rfc-editor.org/info/bcp97 
[11]: https://www.rfc-editor.org/rfc/rfc8126.html 
[12]: https://www.rfc-editor.org/rfc/rfc2026.html#section-5 
[13]: https://www.rfc-editor.org/rfc/rfc2026.html#section-4.1 
[14]: https://www.rfc-editor.org/rfc/rfc2026.html#section-4.2 
[15]: https://authors.ietf.org/en/content-guidelines-overview 
[16]: https://www.ietf.org/about/groups/iesg/statements/normative-informative-references/ 
[17]: https://datatracker.ietf.org/doc/downref/ 
[18]: https://datatracker.ietf.org/doc/bcp14/ 
[19]: https://datatracker.ietf.org/doc/statement-iesg-statement-on-clarifying-the-use-of-bcp-14-key-words/ 

