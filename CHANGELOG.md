# Changelog

## [1.19.0](https://www.github.com/googleapis/java-bigtable-hbase/compare/v1.18.0...v1.19.0) (2020-12-09)


### Features

* Add keepalive  in grpc channelbuilder ([#2682](https://www.github.com/googleapis/java-bigtable-hbase/issues/2682)) ([2a732d2](https://www.github.com/googleapis/java-bigtable-hbase/commit/2a732d213a6dc35d4dc5bb003009ded8dab3707e))
* adding client wrapper interfaces ([#2406](https://www.github.com/googleapis/java-bigtable-hbase/issues/2406)) ([1ad48d9](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ad48d9418e4d25180ca3dc66aaefcf80e00314b))
* enable directpath ([#2271](https://www.github.com/googleapis/java-bigtable-hbase/issues/2271)) ([d384208](https://www.github.com/googleapis/java-bigtable-hbase/commit/d384208c1d727fe99e57a10cc7ba8a5e4b75a041))
* extend RowCell to include labels field ([#2397](https://www.github.com/googleapis/java-bigtable-hbase/issues/2397)) ([80a85fe](https://www.github.com/googleapis/java-bigtable-hbase/commit/80a85fee02958d0fbe4fb32c6c809db7c0803358))
* tune default settings to align with java-bigtable ([#2439](https://www.github.com/googleapis/java-bigtable-hbase/issues/2439)) ([4aedcd9](https://www.github.com/googleapis/java-bigtable-hbase/commit/4aedcd9a572ef5ad246628654e06d31348dfd383))


### Bug Fixes

* beam warning about accessing template values ([#2400](https://www.github.com/googleapis/java-bigtable-hbase/issues/2400)) ([443a40c](https://www.github.com/googleapis/java-bigtable-hbase/commit/443a40c65f40089a5cc41b5304a1422d1f8cd7ab)), closes [#2389](https://www.github.com/googleapis/java-bigtable-hbase/issues/2389)
* deadlock scenario from BulkReadVeneerApi and fixed flaky tests ([#2484](https://www.github.com/googleapis/java-bigtable-hbase/issues/2484)) ([e4cd4ef](https://www.github.com/googleapis/java-bigtable-hbase/commit/e4cd4ef7b38777d1692a15d5f2182889271f6645))
* includes fixes for the gap between HBase and this client ([#2267](https://www.github.com/googleapis/java-bigtable-hbase/issues/2267)) ([51f0617](https://www.github.com/googleapis/java-bigtable-hbase/commit/51f0617aa8c9865b066e9bfaa25f053c7f0ad3d4))
* ReadRows not counting the rpc as the first attempt ([#2568](https://www.github.com/googleapis/java-bigtable-hbase/issues/2568)) ([c748f23](https://www.github.com/googleapis/java-bigtable-hbase/commit/c748f23b60f83d6468fcb52ac5477b74a3bab964))
* remove duplicated cell when interleave filter is applied ([#2491](https://www.github.com/googleapis/java-bigtable-hbase/issues/2491)) ([2915bfd](https://www.github.com/googleapis/java-bigtable-hbase/commit/2915bfd5527bd6beabab264a79fa764f2e6a7629))
* temporarily disable reporting to unblock releases ([#2620](https://www.github.com/googleapis/java-bigtable-hbase/issues/2620)) ([9611a91](https://www.github.com/googleapis/java-bigtable-hbase/commit/9611a912c8a61fe9cd78ad49fdb71d9051b7accc))
* the options of CreateTableHelper to be public ([#2366](https://www.github.com/googleapis/java-bigtable-hbase/issues/2366)) ([072ccc9](https://www.github.com/googleapis/java-bigtable-hbase/commit/072ccc9a0bd16efb5c4dab5900447a3d2789bac8))
* to fix deleteRowRangeByPrefix for integer values above 127 ([#2511](https://www.github.com/googleapis/java-bigtable-hbase/issues/2511)) ([1ae8c03](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ae8c03f1636b18c3fb6310db61a30f6ab7e9646)), closes [#2509](https://www.github.com/googleapis/java-bigtable-hbase/issues/2509)
* update url in pom file ([#2279](https://www.github.com/googleapis/java-bigtable-hbase/issues/2279)) ([2e2f638](https://www.github.com/googleapis/java-bigtable-hbase/commit/2e2f638add2e4eb69e6b241c98f2f420527396ab))
* updated assertions and scan for firstKeyOnlyFilter test ([#2483](https://www.github.com/googleapis/java-bigtable-hbase/issues/2483)) ([a2cbe7a](https://www.github.com/googleapis/java-bigtable-hbase/commit/a2cbe7a97c2f65bd1f2a21eaba0c8868b315d55d)), closes [#1996](https://www.github.com/googleapis/java-bigtable-hbase/issues/1996)
* validation of TimeRange ([#1890](https://www.github.com/googleapis/java-bigtable-hbase/issues/1890)) ([7f404e4](https://www.github.com/googleapis/java-bigtable-hbase/commit/7f404e4f21004f8b552f4c5b80d409496f4a7240))
* ZeroCopyByteStringUtil can return incorrect results in some cases ([#2628](https://www.github.com/googleapis/java-bigtable-hbase/issues/2628)) ([1667a40](https://www.github.com/googleapis/java-bigtable-hbase/commit/1667a403fd09b8768ef2411059733feec64da3e9))
* **build:** update return codes for build scripts ([#2583](https://www.github.com/googleapis/java-bigtable-hbase/issues/2583)) ([96e8d8e](https://www.github.com/googleapis/java-bigtable-hbase/commit/96e8d8ec38fcb9f8b3b678bcbba91de402f32c36))
* **logs:** type aligned to in log statement ([#2536](https://www.github.com/googleapis/java-bigtable-hbase/issues/2536)) ([76c41ca](https://www.github.com/googleapis/java-bigtable-hbase/commit/76c41ca37986cc703a27af971012949c425fb329))


### Reverts

* Revert "[maven-release-plugin] prepare release bigtable-client-parent-1.13.0" ([7313467](https://www.github.com/googleapis/java-bigtable-hbase/commit/7313467fd6937331def4e54ed5a6c59592d37e17))
* Revert "[maven-release-plugin] prepare for next development iteration" ([e749835](https://www.github.com/googleapis/java-bigtable-hbase/commit/e749835440c819b97bcf3ffac91c0b1f24bf3476))
* Revert "Fix: includes fixes for the gap between HBase and this client (#2267)" (#2282) ([966e1b0](https://www.github.com/googleapis/java-bigtable-hbase/commit/966e1b0d0f8fc62a9fa6778bd3d34669402b52a5)), closes [#2267](https://www.github.com/googleapis/java-bigtable-hbase/issues/2267) [#2282](https://www.github.com/googleapis/java-bigtable-hbase/issues/2282)
* Revert "fix executors on app engine (#2111)" (#2112) ([89cc282](https://www.github.com/googleapis/java-bigtable-hbase/commit/89cc2829b30498f332095a5f2211e6fa57f95b4a)), closes [#2111](https://www.github.com/googleapis/java-bigtable-hbase/issues/2111) [#2112](https://www.github.com/googleapis/java-bigtable-hbase/issues/2112)
* Revert "fix lint for test (#1978)" (#1979) ([fcf32f4](https://www.github.com/googleapis/java-bigtable-hbase/commit/fcf32f4befc00e6b9545cbc9457350f93ad36821)), closes [#1978](https://www.github.com/googleapis/java-bigtable-hbase/issues/1978) [#1979](https://www.github.com/googleapis/java-bigtable-hbase/issues/1979)
* Revert "Enable throttling in BufferedMutator by default (#1854)" (#1856) ([4eaa615](https://www.github.com/googleapis/java-bigtable-hbase/commit/4eaa6151c4bafe389be343278374765096146f1d)), closes [#1854](https://www.github.com/googleapis/java-bigtable-hbase/issues/1854) [#1856](https://www.github.com/googleapis/java-bigtable-hbase/issues/1856)
* Revert "Convert parameters in CloudBigtableConfiguration to runtime parameters (#1813)" (#1814) ([3aa75e9](https://www.github.com/googleapis/java-bigtable-hbase/commit/3aa75e922fcc7aa327b995763129bb522799e4d4)), closes [#1813](https://www.github.com/googleapis/java-bigtable-hbase/issues/1813) [#1814](https://www.github.com/googleapis/java-bigtable-hbase/issues/1814)
* Revert "Adding a Beam version of CloudBigtableIO." ([0cc334a](https://www.github.com/googleapis/java-bigtable-hbase/commit/0cc334a076fa2d1ecc2d2f376b7d2070827b49f1))
* Revert "Updating the README." ([4e323e0](https://www.github.com/googleapis/java-bigtable-hbase/commit/4e323e06f0eb69776e371345545e42bf6757e232))


### Documentation

* add javadoc for classes marked as InternalApi ([#2350](https://www.github.com/googleapis/java-bigtable-hbase/issues/2350)) ([c86d7d2](https://www.github.com/googleapis/java-bigtable-hbase/commit/c86d7d265b2816136e3d6313eeb8fa87d74f9635))
* automatically update version numbers with release ([#2476](https://www.github.com/googleapis/java-bigtable-hbase/issues/2476)) ([2ad78e9](https://www.github.com/googleapis/java-bigtable-hbase/commit/2ad78e919fada035e1c6d92f056c8dbf64771f4a))
* update CONTRIBUTING.md to include code formatting ([#534](https://www.github.com/googleapis/java-bigtable-hbase/issues/534)) ([#2542](https://www.github.com/googleapis/java-bigtable-hbase/issues/2542)) ([1c92056](https://www.github.com/googleapis/java-bigtable-hbase/commit/1c920563edd114589ff6896f396a0a2d021fd698))
* Update CONTRIBUTING.md with integration test instructions ([#2560](https://www.github.com/googleapis/java-bigtable-hbase/issues/2560)) ([9b1a6e5](https://www.github.com/googleapis/java-bigtable-hbase/commit/9b1a6e5738dd0362be8a12a2cf18f623015f5243))
* Updated readme to redirect user to veneer client ([#2288](https://www.github.com/googleapis/java-bigtable-hbase/issues/2288)) ([aa9ac47](https://www.github.com/googleapis/java-bigtable-hbase/commit/aa9ac475ca6633dd38d338192ca9ddae7a423188))


### Dependencies

* add maven-enforcer-plugin ([#2401](https://www.github.com/googleapis/java-bigtable-hbase/issues/2401)) ([1ef4b9c](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ef4b9cb23a11d630114f382080baac66fa2f26d))
* align bigtable-hbase-1.x-mapreduce to use the same hadoop version as other 1.x modules ([#2455](https://www.github.com/googleapis/java-bigtable-hbase/issues/2455)) ([60a5f82](https://www.github.com/googleapis/java-bigtable-hbase/commit/60a5f82e3e3c9affdcaf5ae2a8b79c433b5a1a1b))
* fix dependency build ([#2305](https://www.github.com/googleapis/java-bigtable-hbase/issues/2305)) ([e92fd2e](https://www.github.com/googleapis/java-bigtable-hbase/commit/e92fd2e560421059bda83a0c0fd2f11f73ba9fcd))
* fix hbaseLocalMiniClusterTestH2 tests ([#2308](https://www.github.com/googleapis/java-bigtable-hbase/issues/2308)) ([b7f48f5](https://www.github.com/googleapis/java-bigtable-hbase/commit/b7f48f5d7844af2e5466c8be3437edd7fe05e152))
* fix undeclared used dependencies ([#2419](https://www.github.com/googleapis/java-bigtable-hbase/issues/2419)) ([d9b109f](https://www.github.com/googleapis/java-bigtable-hbase/commit/d9b109f01b53924476b0d2b8cdbe5b36ef83bdad))
* manually update dependency org.mockito:mockito-core to v3.3.0 ([#2392](https://www.github.com/googleapis/java-bigtable-hbase/issues/2392)) ([918340d](https://www.github.com/googleapis/java-bigtable-hbase/commit/918340dfe3abf60411624fee6b6aa826644e24d9))
* update bigtable veneer to 1.15.0 ([#2630](https://www.github.com/googleapis/java-bigtable-hbase/issues/2630)) ([9034822](https://www.github.com/googleapis/java-bigtable-hbase/commit/90348227215039ce0370e67db7b4d0b0daf7b1ec))
* update bigtable veneer version to 1.12.2 ([#2526](https://www.github.com/googleapis/java-bigtable-hbase/issues/2526)) ([c422b07](https://www.github.com/googleapis/java-bigtable-hbase/commit/c422b07f06cb55831e2287fd6dced7ce46ea25da))
* update bigtable.version to v1.11.0 ([#2395](https://www.github.com/googleapis/java-bigtable-hbase/issues/2395)) ([50de5d7](https://www.github.com/googleapis/java-bigtable-hbase/commit/50de5d76520485ec8e13a0b481a4b88dcd3fd56c))
* update bigtable.version to v1.13.0 ([#2540](https://www.github.com/googleapis/java-bigtable-hbase/issues/2540)) ([2167870](https://www.github.com/googleapis/java-bigtable-hbase/commit/21678704f17cc5487bb280e6be56e5cd26a3a9bc))
* update bigtable.version to v1.16.1 ([#2646](https://www.github.com/googleapis/java-bigtable-hbase/issues/2646)) ([a48a456](https://www.github.com/googleapis/java-bigtable-hbase/commit/a48a45617db58872797d4384c714463403ec5eeb))
* update bigtable.version to v1.16.2 ([#2654](https://www.github.com/googleapis/java-bigtable-hbase/issues/2654)) ([ad48fb1](https://www.github.com/googleapis/java-bigtable-hbase/commit/ad48fb14f97b696727ae6dfce7963f13770227a1))
* update bigtable.version to v1.17.0 ([#2668](https://www.github.com/googleapis/java-bigtable-hbase/issues/2668)) ([15a2f39](https://www.github.com/googleapis/java-bigtable-hbase/commit/15a2f39f51389187af78a4441e78c743cc080846))
* update bigtable.version to v1.17.1 ([#2674](https://www.github.com/googleapis/java-bigtable-hbase/issues/2674)) ([7ee5f0a](https://www.github.com/googleapis/java-bigtable-hbase/commit/7ee5f0a3851bf83ef371446f589ccfd30017299f))
* update bigtable.version to v1.17.3 ([#2695](https://www.github.com/googleapis/java-bigtable-hbase/issues/2695)) ([75cf25c](https://www.github.com/googleapis/java-bigtable-hbase/commit/75cf25cded78a0a3ecb1315f0f1153c8c9cf20c3))
* update bigtable.version to v1.18.0 ([#2700](https://www.github.com/googleapis/java-bigtable-hbase/issues/2700)) ([48a60f6](https://www.github.com/googleapis/java-bigtable-hbase/commit/48a60f6ecb2451b8fd400d69703daab139a60e4c))
* update bigtable.version to v1.19.0 ([#2721](https://www.github.com/googleapis/java-bigtable-hbase/issues/2721)) ([b813bd4](https://www.github.com/googleapis/java-bigtable-hbase/commit/b813bd48d56048fe9252f3ff7692fb1275baa775))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.10.2 ([#2340](https://www.github.com/googleapis/java-bigtable-hbase/issues/2340)) ([437557f](https://www.github.com/googleapis/java-bigtable-hbase/commit/437557fd108db51273dd97d9d0eb1c9bfeecda6d))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.10.3 ([#2394](https://www.github.com/googleapis/java-bigtable-hbase/issues/2394)) ([95834d1](https://www.github.com/googleapis/java-bigtable-hbase/commit/95834d1623546c028c347ede6fe1f0169a66de00))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.11.0 ([#2505](https://www.github.com/googleapis/java-bigtable-hbase/issues/2505)) ([dd8856f](https://www.github.com/googleapis/java-bigtable-hbase/commit/dd8856f81b64249b8a9da28f0aa9350fa9887b4a))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.11.1 ([#2557](https://www.github.com/googleapis/java-bigtable-hbase/issues/2557)) ([65373ce](https://www.github.com/googleapis/java-bigtable-hbase/commit/65373ced9dd22050ce464c285d1f5d5d70f1b76d))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.11.2 ([#2603](https://www.github.com/googleapis/java-bigtable-hbase/issues/2603)) ([046affa](https://www.github.com/googleapis/java-bigtable-hbase/commit/046affab81031e616fb3f3500f7d8bc379f55c16))
* update dependency com.google.auto.value:auto-value to v1.7.2 ([#2513](https://www.github.com/googleapis/java-bigtable-hbase/issues/2513)) ([409b309](https://www.github.com/googleapis/java-bigtable-hbase/commit/409b3094846e98cbc3286057ac98cba2f3332339))
* update dependency com.google.auto.value:auto-value to v1.7.3 ([#2549](https://www.github.com/googleapis/java-bigtable-hbase/issues/2549)) ([1161524](https://www.github.com/googleapis/java-bigtable-hbase/commit/1161524ecc3335d0e824bc7045159319f9885a83))
* update dependency com.google.auto.value:auto-value to v1.7.4 ([#2571](https://www.github.com/googleapis/java-bigtable-hbase/issues/2571)) ([4dd36a7](https://www.github.com/googleapis/java-bigtable-hbase/commit/4dd36a732ce229508f2d49dcb09ed36fe0f6ede6))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.2 ([#2532](https://www.github.com/googleapis/java-bigtable-hbase/issues/2532)) ([818f435](https://www.github.com/googleapis/java-bigtable-hbase/commit/818f4354846b848307b74c4d927d73833da254e6))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.3 ([#2550](https://www.github.com/googleapis/java-bigtable-hbase/issues/2550)) ([218bcbe](https://www.github.com/googleapis/java-bigtable-hbase/commit/218bcbebecfc99ccc3a2b26d817c904e967daa3c))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.4 ([#2572](https://www.github.com/googleapis/java-bigtable-hbase/issues/2572)) ([bf79eaf](https://www.github.com/googleapis/java-bigtable-hbase/commit/bf79eaf6e229f42b4b74cf46500e06ebf932239b))
* update dependency com.google.guava:guava to v30 ([#2666](https://www.github.com/googleapis/java-bigtable-hbase/issues/2666)) ([8289a54](https://www.github.com/googleapis/java-bigtable-hbase/commit/8289a543df878a2cb861c9084fa160a35bbc1d41))
* update dependency com.google.http-client:google-http-client-jackson2 to v1.35.0 ([#2507](https://www.github.com/googleapis/java-bigtable-hbase/issues/2507)) ([73f5c5e](https://www.github.com/googleapis/java-bigtable-hbase/commit/73f5c5e6ee599db681e3c27bc96fe0664db7d45e))
* update dependency com.google.http-client:google-http-client-jackson2 to v1.36.0 ([#2559](https://www.github.com/googleapis/java-bigtable-hbase/issues/2559)) ([5567896](https://www.github.com/googleapis/java-bigtable-hbase/commit/55678969c0cf1a7ed74f34c95caef0ed2bf8291e))
* update dependency com.google.http-client:google-http-client-jackson2 to v1.37.0 ([#2652](https://www.github.com/googleapis/java-bigtable-hbase/issues/2652)) ([64ea0e1](https://www.github.com/googleapis/java-bigtable-hbase/commit/64ea0e150a25b3f48de651d941dba93718a48166))
* update dependency com.google.http-client:google-http-client-jackson2 to v1.38.0 ([#2675](https://www.github.com/googleapis/java-bigtable-hbase/issues/2675)) ([95cde54](https://www.github.com/googleapis/java-bigtable-hbase/commit/95cde54a2ccb7ef0128f7ab6696d77b27ab465ed))
* update dependency commons-codec:commons-codec to v1.14 ([#2339](https://www.github.com/googleapis/java-bigtable-hbase/issues/2339)) ([41a3d98](https://www.github.com/googleapis/java-bigtable-hbase/commit/41a3d98cb4561917ac91e1ea9207b99e1f3e0067))
* update dependency commons-codec:commons-codec to v1.15 ([#2636](https://www.github.com/googleapis/java-bigtable-hbase/issues/2636)) ([e604c3e](https://www.github.com/googleapis/java-bigtable-hbase/commit/e604c3e04fdd82add41ef3882dd6630b002e6b18))
* update dependency io.grpc:grpc-bom to v1.26.0 ([6c616c9](https://www.github.com/googleapis/java-bigtable-hbase/commit/6c616c90d1e4c280b62a74e37bd84cdb6b7ec76e))
* update dependency junit:junit to v4.13 ([#2335](https://www.github.com/googleapis/java-bigtable-hbase/issues/2335)) ([92537f0](https://www.github.com/googleapis/java-bigtable-hbase/commit/92537f088691ea10de87ef6a580ae8f22c323132))
* update dependency org.apache.commons:commons-compress to v1.20 ([#2376](https://www.github.com/googleapis/java-bigtable-hbase/issues/2376)) ([65ac9cd](https://www.github.com/googleapis/java-bigtable-hbase/commit/65ac9cdfd7a45fcf663dd49f79896494ea993ea2))
* update dependency org.mockito:mockito-core to v3.2.4 ([#2290](https://www.github.com/googleapis/java-bigtable-hbase/issues/2290)) ([2e2e4f9](https://www.github.com/googleapis/java-bigtable-hbase/commit/2e2e4f9d6df349232e16f4bebe184de973edf8d2))
* update dependency org.mockito:mockito-core to v3.3.3 ([#2414](https://www.github.com/googleapis/java-bigtable-hbase/issues/2414)) ([e82bc10](https://www.github.com/googleapis/java-bigtable-hbase/commit/e82bc102f25085f3c223073d5e142f3376b0ec55))
* update dependency org.mockito:mockito-core to v3.4.0 ([#2578](https://www.github.com/googleapis/java-bigtable-hbase/issues/2578)) ([d6a351e](https://www.github.com/googleapis/java-bigtable-hbase/commit/d6a351ecac04b58fd7b3706ff074d4af65212121))
* update dependency org.mockito:mockito-core to v3.4.6 ([#2593](https://www.github.com/googleapis/java-bigtable-hbase/issues/2593)) ([6fe4fc1](https://www.github.com/googleapis/java-bigtable-hbase/commit/6fe4fc1a306b23509e38ac7ddbd40248389c89fc))
* update dependency org.mockito:mockito-core to v3.5.13 ([#2638](https://www.github.com/googleapis/java-bigtable-hbase/issues/2638)) ([47741d7](https://www.github.com/googleapis/java-bigtable-hbase/commit/47741d71b8f0a74b007430974c7565f2afe54d95))
* update dependency org.mockito:mockito-core to v3.5.15 ([#2660](https://www.github.com/googleapis/java-bigtable-hbase/issues/2660)) ([500eed1](https://www.github.com/googleapis/java-bigtable-hbase/commit/500eed1ef0bb52dc90f170e8675ac21b5cb2d872))
* update dependency org.mockito:mockito-core to v3.5.7 ([#2609](https://www.github.com/googleapis/java-bigtable-hbase/issues/2609)) ([7c6c3c8](https://www.github.com/googleapis/java-bigtable-hbase/commit/7c6c3c82450fa76135d93ab8f78de3c14da2debc))
* update dependency org.slf4j:slf4j-api to v1.7.30 ([#2309](https://www.github.com/googleapis/java-bigtable-hbase/issues/2309)) ([8182b5d](https://www.github.com/googleapis/java-bigtable-hbase/commit/8182b5d3e492713738ef2f8589ef714c2cabfa5b))
* update jmh.version to v1.22 ([#2348](https://www.github.com/googleapis/java-bigtable-hbase/issues/2348)) ([cdec57f](https://www.github.com/googleapis/java-bigtable-hbase/commit/cdec57fc7b10bbea62c8f7def6ada389849aa970))
* update jmh.version to v1.23 ([#2370](https://www.github.com/googleapis/java-bigtable-hbase/issues/2370)) ([4959c8f](https://www.github.com/googleapis/java-bigtable-hbase/commit/4959c8f0ca119e19a7585875ba056934dda60957))
* update jmh.version to v1.27 ([#2739](https://www.github.com/googleapis/java-bigtable-hbase/issues/2739)) ([b6bf3c7](https://www.github.com/googleapis/java-bigtable-hbase/commit/b6bf3c747ad1e401957a2fa76177efbc8cd221ea))
* update shared config to 0.9.2 ([#2635](https://www.github.com/googleapis/java-bigtable-hbase/issues/2635)) ([fcdde22](https://www.github.com/googleapis/java-bigtable-hbase/commit/fcdde22099efdc0451cd4872b128169b4f61ea7a))
* **fix:** add log4j12 to mincluster h2 tests ([#2450](https://www.github.com/googleapis/java-bigtable-hbase/issues/2450)) ([bf5ef7c](https://www.github.com/googleapis/java-bigtable-hbase/commit/bf5ef7c80dd504baa56887fbdfe975677c05ab34))
