v1.7.0 / 2025-06-03
========================
test(bdd): adding scheduler logic bdd by @abhilashshetty04 in #323
chore(deps): update analytics dependency by @niladrih in #325
feat(charts): add analytics ID and KEY envs to csi controller by @niladrih in #326
small typo by @chandanpasunoori in #327
fix readme typo by @runzhliu in #329
feat(chores): Add missing tools to nix-shell by @mhkarimi1383 in #352
build: a number of fixes on Makefile and nix-shell by @tiagolobocastro in #360
docs(security): cross-reference security docs by @tiagolobocastro in #362
docs: improve contribution guides by @tiagolobocastro in #361
build: various makefile fixes by @tiagolobocastro in #363
[fix] Fix invalid YAMLs in crds by @nilroy in #364
test: add volume provisioning test on cordoned node by @abhilashshetty04 in #375
docs: update microk8s instructions by @dsharma-dc in #378
correctly indent podLabels on node service by @ecniiv in #380
use parseint for capacity parsing to avoid range overflow by @abhilashshetty04 in #387
update csi spec version to v1.9.0 by @abhilashshetty04 in #391
feat(provisioning): extra format options (mkfs) added by @mhkarimi1383 in #335

lvm-localpv-1.6.2 / 2024-09-19
========================
<b>NOTE</b>: This was only a chart release that addressed a bug on prior chart. 
* fix(chart): revert env OPENEBS_NAMESPACE to LVM_NAMESPACE for v1.6.x ([#333](https://github.com/openebs/lvm-localpv/pull/333),[@niladrih](https://github.com/niladrih))

v1.6.1 / 2024-09-16
========================
* chore(deps): update analytics dependency ([#325](https://github.com/openebs/lvm-localpv/pull/325),[@niladrih](https://github.com/niladrih))

v1.6.0 / 2024-07-03
========================
* feat(analytics): add heartbeat pinger ([#318](https://github.com/openebs/lvm-localpv/pull/318),[@niladrih](https://github.com/niladrih))

v0.4.0 / 2021-04-14
========================
* updated storage and apiextension version to v1 ([#40](https://github.com/openebs/lvm-localpv/pull/40),[@shubham14bajpai](https://github.com/shubham14bajpai))
* add support for thin provision lvm volumes ([#30](https://github.com/openebs/lvm-localpv/pull/30),[@prateekpandey14](https://github.com/prateekpandey14))
* upgrade grpc lib dependency to v1.34.2 ([#37](https://github.com/openebs/lvm-localpv/pull/37),[@iyashu](https://github.com/iyashu))
* reload lvmetad cache before querying volume groups ([#38](https://github.com/openebs/lvm-localpv/pull/38),[@iyashu](https://github.com/iyashu))

v0.4.0-RC2 / 2021-04-12
========================

v0.4.0-RC1 / 2021-04-07
========================
* updated storage and apiextension version to v1 ([#40](https://github.com/openebs/lvm-localpv/pull/40),[@shubham14bajpai](https://github.com/shubham14bajpai))
* add support for thin provision lvm volumes ([#30](https://github.com/openebs/lvm-localpv/pull/30),[@prateekpandey14](https://github.com/prateekpandey14))
* upgrade grpc lib dependency to v1.34.2 ([#37](https://github.com/openebs/lvm-localpv/pull/37),[@iyashu](https://github.com/iyashu))
* reload lvmetad cache before querying volume groups ([#38](https://github.com/openebs/lvm-localpv/pull/38),[@iyashu](https://github.com/iyashu))


v0.3.0 / 2021-03-12
========================
* Add e2e-test for lvm volume resize support  ([#32](https://github.com/openebs/lvm-localpv/pull/32),[@w3aman](https://github.com/w3aman))
* Add e2e-test for lvm-localpv driver provisioning ([#29](https://github.com/openebs/lvm-localpv/pull/29),[@w3aman](https://github.com/w3aman))
* add volume group capacity tracking ([#21](https://github.com/openebs/lvm-localpv/pull/21),[@iyashu](https://github.com/iyashu))
* move the bdd test cases to github action ([#27](https://github.com/openebs/lvm-localpv/pull/27),[@pawanpraka1](https://github.com/pawanpraka1))
* set IOPS, BPS limit for Pod accessing a Volume ([#19](https://github.com/openebs/lvm-localpv/pull/19),[@abhranilc](https://github.com/abhranilc))
* adding bdd test cases for LVM Driver ([#26](https://github.com/openebs/lvm-localpv/pull/26),[@pawanpraka1](https://github.com/pawanpraka1))
* Add e2e-test for lvm-localpv ([#24](https://github.com/openebs/lvm-localpv/pull/24),[@w3aman](https://github.com/w3aman))
* enable pod resheduling cause of node insufficient capacity ([#23](https://github.com/openebs/lvm-localpv/pull/23),[@iyashu](https://github.com/iyashu))
* updating go mod to v0.2.0 ([#25](https://github.com/openebs/lvm-localpv/pull/25),[@pawanpraka1](https://github.com/pawanpraka1))


v0.2.0 / 2021-02-12
========================
* add support for create/delete snapshot for LVM localPV ([#12](https://github.com/openebs/lvm-localpv/pull/12),[@akhilerm](https://github.com/akhilerm))
* adding raw block volume support for LVM LocalPV ([#14](https://github.com/openebs/lvm-localpv/pull/14),[@pawanpraka1](https://github.com/pawanpraka1))
* add capacity weighted scheduler and make it default for scheduling volumes ([#20](https://github.com/openebs/lvm-localpv/pull/20),[@akhilerm](https://github.com/akhilerm))
* ensure lvm volume creation & deletion idempotent ([#16](https://github.com/openebs/lvm-localpv/pull/16),[@iyashu](https://github.com/iyashu))


v0.1.0 / 2021-01-13
========================
* adding resize support for lvm volumes  ([#2](https://github.com/openebs/lvm-localpv/pull/2),[@pawanpraka1](https://github.com/pawanpraka1))
* adding multi arch build process for LVM Driver ([#1](https://github.com/openebs/lvm-localpv/pull/1),[@pawanpraka1](https://github.com/pawanpraka1))
