Contributor Guidelines
======================

Thank you for helping us make this specification better! We welcome bug reports
and suggestions for improvements, both to the behavior the specification
describes, and to the way in which the description is written.

To propose a concrete change, edit `index.bs` in this repository's root
directory, and send a PR. It might be helpful to file an issue first for larger
proposals to ensure that there's alignment on the desired outcome and approach.

Tests
-----

It's essential to ensure that the specification reflects implementation reality.
To that end, we require that relevant tests be created or adjusted when making
changes to the specification. Tests for this specification can be found in the
`/directory-goes-here` directory of [`web-platform-tests/wpt`][wpt].

If adding a test for a given change is not practical given limitations in the
testing infrastructure, you'll need to explain why and [file an issue][wpt-bug]
with the `type:untestable` label so we can follow up on it later.

A dashboard showing the tests results when running against various browser
engines can be seen at [`wpt.fyi/results/directory-goes-here`][fyi].

[wpt]: https://github.com/web-platform-tests/wpt
[fyi]: https://wpt.fyi/results/directory-goes-here
[wpt-bug]: https://github.com/web-platform-tests/wpt/issues/new


Implementations
---------------

As above, we'd like the specification to reflect reality to the extent possible.
That means we require some level of alignment from browser engines before
making changes to the specification. There should be a path to interoperability
clearly laid out, with at least two engines approving a change, and no engine
strongly opposed.

When proposing changes to the specification, engines' positions can be explained
either by linking to relevant discussions, CCing specific engineers who can
vouch for the engine's interest, and/or pointing to official standards positions
when available.

In addition to positive interest, we'll require a link to issues filed against
each affected implementer to ensure they're aware of the need to align their
implementation with the change to the specification.


Patent Policy and Licensing
---------------------------

Contributions to this repository are intended to become part of Recommendation-track documents 
governed by the [W3C Patent Policy](https://www.w3.org/Consortium/Patent-Policy/) and
[Document License](https://www.w3.org/Consortium/Legal/copyright-documents). To contribute, you must 
either participate in the relevant W3C Working Group or make a non-member patent licensing
commitment.

If you are not the sole contributor to a contribution (pull request), please identify all 
contributors in the pull request's body or in subsequent comments.

To add a contributor (other than yourself, that's automatic), mark them one per line as follows:

```
+@github_username
```

If you added a contributor by mistake, you can remove them in a comment with:

```
-@github_username
```

If you are making a pull request on behalf of someone else but you had no part in designing the 
feature, you can remove yourself with the above syntax.
