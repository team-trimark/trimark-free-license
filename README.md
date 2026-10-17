# License Repository

License repo for the Trimark Free License family.

The crux of this license family is to ensure free use for the end-user.
Anyone may use the original source code, for any purpose, within the limits
the law allows, as long as the product they build with it stays free for
its end-users as described below.

The original author does not take responsibility for the actions of the
end-product other developers have created which depends on, incorporates,
is a direct variation of, or otherwise uses the codebase.

## Before you adopt this license

By publishing code under this license family, you permanently and completely
give up the right to monetize that version of the code. This applies to you
as the original author too. Your profit from the licensed version will be
near zero. See [Owner's monetization waiver](#owners-monetization-waiver).

## Licenses

| License | Directory | Short name |
| --- | --- | --- |
| Trimark Free For All | [`trimark-free-for-all/`](trimark-free-for-all/) | FFA |
| Trimark Free For Non-Commercial | [`trimark-free-for-non-commercial/`](trimark-free-for-non-commercial/) | FNC |

## Comparison

| Usage Type | FFA | FNC |
| --- | --- | --- |
| Commercial Use | Allowed, but the end-product must be free for anyone, including commercial and business users | Allowed, but the end-product must stay free for anyone using it non-commercially |
| Personal Use | Allowed, but the end-product must be free for anyone | Allowed, but the end-product must stay free for anyone using it non-commercially |
| Charging users | Not allowed | Commercial users only |
| Freemium and in-app purchases | Not allowed | Commercial users only |
| Source disclosure | Not required | Not required |
| Attribution | Not required | Required only for paid software |
| Owner monetization | Waived for each licensed version | Waived for each licensed version |
| Relicensing | Future versions only, after a meaningful codebase change or with written consent of all copyright holders, with 90 days' notice (30 if the license is frozen) | Future versions only, with written consent of all copyright holders, with 90 days' notice (30 if the license is frozen) |
| Liabilities | None | None |
| Servicing | As-is | As-is |
| Copyrights | Stay with the owner | Stay with the owner |
| Trademark | Can be repackaged, original name must not be used | Can be repackaged, original name must not be used |

## Definitions

### End-product

Something is an end-product if an individual, corporation, or other entity
can viably use it as-is to:

- create or increase revenue,
- optimize internal processes,
- lower operating costs, or
- otherwise increase their profit or economic gain.

It is **not** an end-product if all three of these hold:

1. The source code is offered in full.
2. A non-professional, non-developer could reasonably not use it as-is.
3. The license stays pinned. See [Pinning and relicensing](#pinning-and-relicensing).

This is meant to catch nearly all usable software. Library-style forks that
meet all three conditions remain fully under the control of their developer.
There are no other exceptions.

Code published under this exemption must stay source-available. The
end-products built from it may be closed-source.

### Meaningful change

A change to the codebase is meaningful if:

1. it substantially changes how the code works internally, not only how its
   data is named or arranged; and
2. the change was not made mainly to meet this definition; and
3. where the code reads or writes persistent data (such as configuration or
   save-state files), that data from the earlier version could not be
   converted to the new version by simple automated conversion without
   significant schema changes or loss or insertion of data.

### Commercial use

These are all potential commercial clients:

- businesses,
- individuals acting for profit, and
- partially commercial entities.

Schools, non-profits, and governments are commercial users if they give
the firm selling the end-product any of the following:

- cash,
- payment in kind,
- economic benefits, including tax credits, trade benefits, and relaxed
  regulation, or
- any other competitive advantage.

If they use the end-product completely free of charge, their use is not
commercial.

### Paid software

An end-product becomes paid software the moment any individual,
corporation, government, or other entity pays the company in any form,
of any size, and any part of the end-product is limited for those who
do not pay or stop paying. Payment includes:

- currency,
- payment in kind,
- contractual benefits, and
- any other economic benefit.

### Free

"Free" means free of charge, not necessarily source-available. An end-product is
free if it can be obtained and used without paying. The end-product may be
closed-source.

Under FFA, the end-product must be free for everyone, including commercial
and business users. It may never be paid software.

Under FNC, the end-product must be free for non-commercial users. It may
be paid software for commercial users only.

## Payments from users

No payment of any kind may be taken from users who must get the
end-product for free. These are all users under FFA, and non-commercial
users under FNC. This includes:

- donor badges and other vanity privileges, and
- mentions or special thanks given in return for payment.

There are two exceptions.

### Charity

Payments are allowed if 95% or more of the total revenue is donated in
return for no direct economic benefit.

- Total revenue excludes VAT, sales tax, and other legal withholdings.
- Claiming tax credits for the donation, or recording it as a cost of the
  company, is allowed.

### Contributions to the codebase

Bug bounties, responsible disclosure programs, and other direct
contributions to the codebase may be compensated.

- Compensation must be cash, equity, or payment in kind.
- Compensation may not be the software itself, or privileges within it.

## Charging commercial users (FNC only)

Under FNC, a company may charge commercial users in one of two ways.

### Option 1: Self-hosted server

- The company provides a server binary that users can run on their own
  machines. The binary may be obfuscated.
- The binary is free of charge for non-commercial use.
- The company may charge entities that use the end-product commercially,
  or for their own business use, under any pricing scheme it chooses.
- The binary includes all features.

If the full binary needs more than a reasonable individual could self-host,
the company must also provide a lite version.

- The lite version may limit features and be optimized for performance.
- The lite version may not remove features that the original source
  code provides.

### Option 2: Fully paid commercial version

The commercial version may be entirely paid, with no self-hosted binary
required, if both of these hold:

- The non-commercial version is completely free.
- The non-commercial version has the same features, issues, and bugs as
  the equivalent commercial version.

### Choosing to charge or not

The provider of an FNC end-product chooses whether to charge each
commercial client or to provide the end-product to them for free. This
choice does not exist under FFA.

- The choice is made in written documentation when the client starts
  using the end-product.
- If there is no written documentation, the client is treated as using the
  end-product commercially. The provider may then charge retroactively,
  based on the pricing scheme it had publicly published at that time.

### Withdrawing free use

If the provider wishes to withdraw its written consent to free use, it must
notify the client in advance, as set out in their agreement. If the
agreement sets no grace period, the grace period is 180 days.

## Free versions stay free

Whatever is free in a version of the end-product that uses work under this
license stays free indefinitely for that version.

To charge for software that is currently free, the company must reverse
engineer or rewrite the implementation until attribution back to this
codebase is no longer legally required.

## Advertisements and telemetry

### Self-hosted servers

Self-hosted servers and services may not force advertisements or telemetry
on. If either is on by default, there must be a way to turn it off that
does not require changing the source code, such as a setting or
configuration option.

### Provider-hosted services

Provider-hosted services may have advertisements and telemetry on, as long
as a self-hosted alternative with the full feature set can be downloaded.

If there is no such download, the end-product is provider-hosted only.
This includes schemes where the company exclusively licenses certain third
parties to host it. In that case:

- Every provider-hosted variant must let the end-user turn telemetry off
  for free.
- Advertisements are still allowed, but they must be generic and
  non-tracking.

## Attribution

When FNC-licensed work is used in paid software, attribution to the
original work is required.

- Attribution may be de-emphasized, for example placed in the credits or
  documentation.
- Attribution must appear at least once in each form of deployment, such
  as web, native mobile, and native desktop.
- A progressive web app (PWA) counts as a separate deployment from the
  website.

## Pinning and relicensing

### Pinning

A pinned license stays in its family. FFA code stays FFA, and FNC code
stays FNC.

### License steward

New versions of the licenses are written only by the license steward,
Mirae Research, a software development firm registered in the Republic of
Korea under business registration number `726-15-02574`.

If Mirae Research is no longer in business, its successor automatically
becomes the license steward. An entity is the successor if, operating
under it and applying for new-business benefits in Korea, it would be
disqualified because of business continuity with Mirae Research.

Business continuity is evaluated under the tax law and trade law of the
Republic of Korea as in force on 16 October 2026. This applies to the
business continuity evaluation only.

If neither Mirae Research nor a successor exists, the licenses are frozen.
No new versions may be published, and every existing version stays valid
permanently.

### Version changes

Code may move to a newer version of its license only if the new version:

- benefits the end-user,
- limits the code author's rights rather than increasing them, and
- does not make the use of the code stricter.

### Relicensing

Code may not be relicensed under any license that permits something the
original license forbids, unless:

- **FFA:** the codebase has changed meaningfully, or all copyright holders
  of the original have given written consent.
- **FNC:** all copyright holders of the original have given written
  consent.

Relicensing applies to future versions only. Every version already
published stays under its original license permanently.

### Notice period

Any license change, including relicensing and moving to a newer license
version, must be publicly announced at least 90 days before it takes
effect.

If neither Mirae Research nor a successor exists, the notice period is
shortened to 30 days.

### Intent

FFA-published code stays source-available and truly free for everyone to
adopt and use. FNC-published code stays source-available and free for
non-commercial use, and allows paid versions only for business and
commercial use.

## Owner's monetization waiver

Every license holder permanently and completely waives the right to
monetize the codebase for the licensed version. License holders include:

- the original author of the codebase, and
- future authors who build on it and publish their work under identical
  license terms.

To monetize, the owner must make a meaningful change to the implementation,
or relicense future versions as described in
[Relicensing](#relicensing). The waiver for every version already published
cannot be undone.

**This limits the owner's profit from the licensed version to near zero.**
Owners should understand this before adopting the license.

---

This readme is not part of the license, and is informational only.
