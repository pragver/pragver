
# ![Pragmatic Versioning](img/title-light-512.png)

## Summary

This specification describes a set of rules and requirements that dictate how
each version identifier must be bumped and and assigned to releases, in a way
that communicates the kind of modifications that were done to a versioned
artifact.

A minimal version identifier takes the form `GRADE.MAJOR.MINOR.PATCH` and is
bumped by incrementing:

- The **Grade Number**, when any *disruptive modifications* are released.
- The **Major Number**, when any *backwards-incompatible modifications* are
  released.
- The **Minor Number**, when any *backwards-compatible alterations* are
  released.
- The **Patch Number**, when only *backwards-compatible corrections* are
  released.

![](img/pragver.png)

Optional Metadata containing additional information associated to the release or
the build take the respective forms `-RELEASE.METADATA` and `+BUILD.METADATA`
and can be appended to a minimal version identifier.


## Author

The Pragmatic Versioning specification is authored by
[Guillermo Calvo](https://github.com/guillermocalvo).

[![](https://resume.guillermo.in/assets/images/thumb.png)](https://guillermo.in/)


## License

This specification is released under
[Creative Commons — Attribution 4.0 International (CC BY 4.0)](LICENSE.md).

### You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow the license
terms.

### Under the following terms:

- **Attribution** — You must give *appropriate credit*, provide a link to the
  license, and *indicate if changes were made*. You may do so in any reasonable
  manner, but not in any way that suggests the licensor endorses you or your
  use.
- **No additional restrictions** — You may not apply legal terms or
  *technological measures* that legally restrict others from doing anything the
  license permits.

### Notices:

- You do not have to comply with the license for elements of the material in the
  public domain or where your use is permitted by an applicable
  *exception or limitation*.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  *publicity, privacy, or moral rights* may limit how you use the material.
