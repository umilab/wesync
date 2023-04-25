[![Wesync](assets/logo-horizontal.png)](https://weloobe/products/wesync)

---

## Goals

Wesync is a **continuous file synchronization program**. It synchronizes
files between two or more computers. We strive to fulfill the goals below.
The goals are listed in order of importance, the most important one being
the first. This is the summary version of the goal list - for more
commentary, see the full [Goals document](https://github.com/umilab/wesync/GOALS.md).

Wesync should be:

1. **Safe From Data Loss**

   Protecting the user's data is paramount. We take every reasonable
   precaution to avoid corrupting the user's files.

2. **Secure Against Attackers**

   Again, protecting the user's data is paramount. Regardless of our other
   goals we must never allow the user's data to be susceptible to
   eavesdropping or modification by unauthorized parties.

3. **Easy to Use**

   Wesync should be approachable, understandable and inclusive.

4. **Automatic**

   User interaction should be required only when absolutely necessary.

5. **Universally Available**

   Wesync should run on every common computer. We are mindful that the
   latest technology is not always available to any given individual.

6. **For Individuals**

   Wesync is primarily about empowering the individual user with safe,
   secure and easy to use file synchronization.

7. **Everything Else**

   There are many things we care about that don't make it on to the list. It
   is fine to optimize for these values, as long as they are not in conflict
   with the stated goals above.

## Getting in Touch

The first and best point of contact is the [Forum](contact@weloobe.com).
If you've found something that is clearly a
bug, feel free to report it in the [GitHub issue tracker](https://github.com/umilab/wesync/issues).

## Signed Releases

As of v0.10.15 and onwards release binaries are GPG signed with the key
D26E6ED000654A3E, available from https://weloobe.com/products/wesync#security and
most key servers.

There is also a built in automatic upgrade mechanism (disabled in some
distribution channels) which uses a compiled in ECDSA signature. macOS
binaries are also properly code signed.

All code is licensed under the [MPLv2 License](https://github.com/umilab/wesync/LICENSE).
