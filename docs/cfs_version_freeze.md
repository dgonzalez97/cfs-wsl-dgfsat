# cFS version freeze

Phase A uses the official NASA cFS bundle in this repository as a pinned submodule.

Bundle pin:
- repository: `nasa/cFS`
- tag: `v7.0.0`
- commit: `b4ec679b2fd9d825610515ceb186cbfa80c60cfc`

Resolved submodule pins:
```text
 21868fb7bc250497d4691580515e7dcf53d595b4 apps/ci_lab (v7.0.0)
 068f75639c84788db396b1568a5cb65d13f792a3 apps/sample_app (v7.0.0)
 c8396121e5ca6c76f7a1aba70b054e12af407cde apps/sch_lab (v7.0.0)
 e9893d43ef5b4ad303cbdf5bc1f095f5e4419f33 apps/to_lab (v7.0.0)
 215e2243735c2e2465fcf8629c29af5ba22d4d33 cfe (v6.8.0-rc1+dev393-1282-g215e2243)
 beb74d4233232ae0e81321947f2a74d9dfa287b8 libs/sample_lib (v7.0.0)
 24c864161a7ab2d6ffbd1e0bc2f75df5f1c43057 osal (5.0.0-bv-1221-g24c86416)
 623fc3e5c6aa87ec468c643372b263193af1e4aa psp (equuleus-rc1-89-g623fc3e)
 2e004a6fba134c586f240f2c787605a6488af327 tools/cFS-GroundSystem (v7.0.0)
 da72f6160d7a9da5d1895135d1ce3adf20b84ae4 tools/elf2cfetbl (v7.0.0)
 5d56ef0709451f30a17c430f5cad6fb0e986a388 tools/tblCRCTool (v7.0.0)
```

Notes:
- The top-level freeze is the official `v7.0.0` bundle tag.
- Reproducibility comes from the recorded cFS commit and the recursive submodule SHAs above.
- Raspberry Pi, Yocto, boot/update work, and libcsp are intentionally out of scope in this phase.
