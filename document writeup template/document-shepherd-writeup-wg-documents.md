# Document Shepherd Write-Up for Working Group Documents

   *This version is dated x X 2026.*

   Thank you for serving as a document shepherd. One of the
   responsibilities of the shepherd is to consider and answer the questions in this
   write-up to provide helpful context to Last Call and Internet
   Engineering Steering Group ([IESG][1]) reviewers.  Your diligence in
   completing it is appreciated.  The full role of the shepherd is
   described in [RFC 4858][2].  At a minimum, you will need the
   cooperation of the authors and editors to complete these checks.

   Note that some numbered items contain multiple, related questions;
   please be sure to answer all of them. When an item does not apply
   to the document, please indicate "N/A".

## Document History

   1.   Characterize consensus to publish the document: does it represent the strong
        concurrence of a few individuals, with others being silent, or
        was a broad agreement reached?

   2.   Indicate any significant controversy about particular points, or
        where consensus on an aspect of the document was particularly rough. 

   3.   If anyone threatened an appeal or otherwise indicated extreme
        discontent, please summarize the areas of conflict in
        separate email messages to the responsible Area Director.
        (NOTE: This should be in a separate email because this filled
        questionnaire will be publicly available.)

   4.   For protocol documents, Indicate whether there are existing implementations,
        where they are listed (noting that [RFC 7942][3] recommends they be
        reported in the document itself).

        Also, please list any parties that have listed plans to implement.

## Additional Reviews

   5.   Provide references to any reviews of the document by other IETF WGs
        or external organizations.

   6.   Describe or refer to the results of any required formal expert
        review criteria (e.g., the YANG Doctor, media type, and URI
        reviews).

   7.   If the document contains a YANG module:
   
        * Convey whether the document’s Datatracker page indicates
          any errors or warnings.

        * Has a YANGDOCTOR review been done on a recent version,
          indicating that it is ready for publication?

        * Does the document use the various templates in RFC 9907
          (mainly, YANG module, Security, and IANA templates)?

   8.   Describe all reviews and automated checks performed to validate
        sections of the document written in a formal language, such as
        XML, JSON code, ABNF/RBNF/BNF rules, ASN.1, CBOR's CDDL, etc.

## Document Shepherd Checks

   9.   Confirm that publication of the document be consistent with the
        chartered objectives and deliverables of the WG. Where possible,
        indicate the specific charter text that relates to the document.

   10.  Confirm that in your opinion this document is clearly written,
        complete, technically accurate, correctly designed, and ready to
        be handed off to the responsible Area Director.

   11.  Identify the relevant [lists of common issues that
        area reviewers encounter][6].  Confirm that such issues been identified
        and addressed, identifying any that are still pending.

   12.  Indicate the type of RFC publication is being requested ([Best Current
        Practice][12], [Proposed Standard, Internet Standard][13],
        [Informational, Experimental or Historic][14]) 
        and why it is appropriate in this case.

   13.  If the document uses BCP 14 key words [18], confirm that the document
        follows the guidance in [19], noting any unclear or inappropriate
        use of keywords.

   15.  Confirm that reasonable efforts (e.g., WGLC via the Datatracker) have been
        made to remind the WG of the intellectual property rights (IPR)
        disclosure obligations described in [BCP 79][7].

        Please summarize any relevant discussion, including links to
        publicly available messages when applicable.

   16.  Confirm that each author, editor, and contributor shown their willingness
        to be listed as such.

        If the total number of authors and editors on the front page
        is greater than five, please provide a justification.

   17.  Please list any remaining I-D nits in the version of the
        document you reviewed.  Simply running the [idnits tool][8] is
        not enough; please review the ["Content Guidelines" on
        authors.ietf.org][15].  Idnits may display false positives;
        please flag those and please explain as needed.

### Document References

   17.  List any informative references that should be normative, or vice-versa.
        See the [IESG Statement on Normative and Informative
        References][16].

   18.  List any normative references that are not freely available to
        the public. For each, characterize whether the community had
        sufficient review access.

   19.  List any normative downward references (see [RFC 3967][9]
        and [BCP 97][10]) that are not already present in the [DOWNREF
        registry][17].

   20.  List any normative references to documents that are not ready
        to be submitted to the IESG for publication or are otherwise in
        an unclear state. For each, indicate the plan for their completion, if known.

   21.  Indicate whether publication of this document change the status of any
        existing RFC(s).  For each, convey whether the Datatracker metadata correctly
        list that RFC on the title page, in the abstract, and in the
        introduction.

### IANA Considerations

   22.  Confirm that the IANA considerations section is consistent
        with the body of the document.

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
        guidelines for Designated Experts.  Are the instructions to
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

