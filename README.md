# Repolex Knowledge Graph of ansible-collections/ansible.mysql

RDF knowledge graph data for [ansible-collections/ansible.mysql](https://github.com/ansible-collections/ansible.mysql), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download ansible-collections/ansible.mysql
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7c033ca1cc2d8458061fdb6b6b32d10d646c8651
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7c033ca1cc2d8458061fdb6b6b32d10d646c8651
│           └── chunk-001.nq.gz
└── blob
    ├── 0068a0c1d2c15a380925b223eeef395e0f9759b8.nq.gz
    ├── 00e80fae46a5ca693acb258faef184563eea146e.nq.gz
    ├── 012f0ad4fa5d0346e6ed52e3fda2126f4ffcc33f.nq.gz
    ├── 015c131cb73aedc9e28eef7bd20eaa9b6f11f5fc.nq.gz
    ├── 01ee3db7924da8198a0f6b789857a455f8f46fad.nq.gz
    ├── 0383055a04ca7b31d015b9a245d0e428baaf093c.nq.gz
    ├── 052b27918cdd34c08eaec40556a42eaebb0a68ed.nq.gz
    ├── 08ae7d8b9c8e10d213d709012ac39afaa15a9487.nq.gz
    ├── 0a40ccb3cf15409030569a80a5b7bbea4b426b82.nq.gz
    ├── 0b2e2d6290f89263029b3a560f0dc6655d08d3f7.nq.gz
    ├── 0d6f10cbe8646f26ff62d0befe5c6bcacf1d930c.nq.gz
    ├── 0e9874cb6b84cd39ebf33b6748b0ee5a084d1efe.nq.gz
    ├── 10583107a141a6c24f1b0e94a7c8c20f781fdfa3.nq.gz
    ├── 1065935fc190e6b07b877a4b1e6a322858332318.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 132109e0df98a6461e18e23ffb9fa1aefe0d8041.nq.gz
    ├── 152162df603c941a19741034324c12bd571cd0f1.nq.gz
    ├── 15ee139bd73951ec360c2f239278466f14bf4920.nq.gz
    ├── 160cfba8a14670f9d5d2ba25c8dd7a123609d7ca.nq.gz
    ├── 16e499992288eba088c8c727fd2c414ad1fbff7e.nq.gz
    ├── 1718b998239861987f6c0c5f890ee790ca6db88d.nq.gz
    ├── 18e9b5581b7a83f25918fb33278bc0d447bc3d33.nq.gz
    ├── 1a95a55bf8703a862cb473ae823d05cf45bb295a.nq.gz
    ├── 1a97ca95bb3f93f193703e8b6108fdd1110a4622.nq.gz
    ├── 1b4f28941f548d239c4ec5377880d38637a627f3.nq.gz
    ├── 1cd068b8f634f9a4e8e99951e75835d89f5390a9.nq.gz
    ├── 1e0f51b89043f7f81414ba223f1fecafb5159008.nq.gz
    ├── 1eaea61f3f8211bb18b92ab04b5f4c0435229b2f.nq.gz
    ├── 1efc07e0dfc2cb4dc837d1353a29bda76abf3188.nq.gz
    ├── 1f4c269021eb2306c529693e712ab947cce93e1e.nq.gz
    ├── 1f6d34f5743f30442089e0335228656dcf92b69e.nq.gz
    ├── 20949b40c7d85ea886b32f4d06bfe15d1fee618f.nq.gz
    ├── 20ef8dddcb45937b4fe9bc82d11a3ffc303d6211.nq.gz
    ├── 21d1e97c52164f573be46f81c9fdcfc3f7b8e2fd.nq.gz
    ├── 22e85037a55751d5cd098659c3141fec9c1bdf79.nq.gz
    ├── 245ba344c853dc0622c9d0b1a2314cd0ed897329.nq.gz
    ├── 2604b9280f983a02440ccd18acb282c463431c2c.nq.gz
    ├── 2608b79383e4759c5e3ddda9f9c729465458108e.nq.gz
    ├── 27430ddeeae1b65711f7c5c3404b740f7e89936d.nq.gz
    ├── 2bc4073fbcdde55bf926a3e33c65c38a9b2d8b88.nq.gz
    ├── 2c2115fefd7df5d47df532793542d452fb02c416.nq.gz
    ├── 2c919ae16b90b3adee3d81052e59998176aee7fe.nq.gz
    ├── 2d95234de64ae29085ff82d1685e835f7136360a.nq.gz
    ├── 2e6a41e89d63125c0f3f3f400846836b3e9be0ce.nq.gz
    ├── 2f593cae6ba61d42b3d7f8123826f4564a704ec3.nq.gz
    ├── 3083a648f63f39533f9a63d227f97b57a5047cf5.nq.gz
    ├── 30ac858c0979e1f6f59b8c1669fd5e52a0977e38.nq.gz
    ├── 313610ddbceaee40a8891f95693b89133a901c89.nq.gz
    ├── 31a46278bbdd99c82698b4061a453389329f37a7.nq.gz
    ├── 321ba4d6b8bafe63cfaf8f7b26ac967def41cfb7.nq.gz
    ├── 337a8399748fba525acd51ba61e58dd3c3a0b9ac.nq.gz
    ├── 3391fb0e0d8e5f5a5555fa6d8dac73d2f6c76940.nq.gz
    ├── 33ad6e84a6190ae9a6d57af3b1050ef2d3d80b1c.nq.gz
    ├── 3558aeb4b4d64ce7357b0c773d35f8fce67b4e00.nq.gz
    ├── 35acd7fb5ff4bee4a15091b93cb73545679cb26a.nq.gz
    ├── 3633c0d38eb1d54c4b2f22610fd998a3c388a2d8.nq.gz
    ├── 36caa217b050f7ed674746e979780dcd425f8da0.nq.gz
    ├── 37e49f50fd012b32f08b482c06d03136b016346b.nq.gz
    ├── 39872d749f3f96e08f8df6b8be5b5f2f0d4f895f.nq.gz
    ├── 39e620f3fc8fa0b2c1820abaa37a3b451bffc6bc.nq.gz
    ├── 39f3239c7352d488f8fb8f2561499fd21e5deb51.nq.gz
    ├── 3b047ea63cb14b5334ee4fc2f791ee34b4a6258e.nq.gz
    ├── 3ca71f24d492fe6e6f4d803104a3489c2a85a073.nq.gz
    ├── 3de26d76037ec51550f3499afb9c51b614f9faa7.nq.gz
    ├── 3fe20e58a2e0a883fede74bd345426cc22e08add.nq.gz
    ├── 40ac5f864c99beec7f8f0004f557b43303764bf5.nq.gz
    ├── 43748793baf0266bc622bdbe4d9444c869a11961.nq.gz
    ├── 44b25f256a5c26ee98d0a0bf491de6984916d8d2.nq.gz
    ├── 4555c9587f674cb67fd0f00206d4369f02526af6.nq.gz
    ├── 456dbf4b3d87cc2d1b1c092a060b92aa8091beae.nq.gz
    ├── 46ec499cb20012d8697963b0912a88d8440c43bf.nq.gz
    ├── 473ceceeb908d5530c32702b50d2e644aecb134c.nq.gz
    ├── 47a30b6532489774dc9f71d30407ffec57b3c559.nq.gz
    ├── 48fd5602080eebb2e4af54f65f7ad2ea3bc65e7e.nq.gz
    ├── 49531b8d742e14df34bc0e5f06f867251dcfc679.nq.gz
    ├── 49f0f346ecb2d0412aa0304e14c7ddfc20b93843.nq.gz
    ├── 4be5f587922c7f4409f983d112f0d0ca36afb547.nq.gz
    ├── 4bf70a6f9f9587425066e375f0e97f961080f44b.nq.gz
    ├── 4d495e7d000c6eda3913fbf5ce849e4f3636fe5d.nq.gz
    ├── 4eb073c11e2235ba363feca7abdcaabb17e8f515.nq.gz
    ├── 51964a0f542b201c36bb6c77e59fdfc934ab38a3.nq.gz
    ├── 544ad4d60f86caa31811e7c641e2435fec74df44.nq.gz
    ├── 554e73c099be66cd9d91c2ea5970d19127589521.nq.gz
    ├── 56209c58cae0fdfeeff58b72a1305d2b09165f90.nq.gz
    ├── 5761b3d9a178e5b11f38bbe15bc9d67eaf005419.nq.gz
    ├── 57bf9ebaed86ef4beb9a3e6b9e8f429e8c9cc5a7.nq.gz
    ├── 5a358f0aa79ef6701efa418f9e7a9bf95c895d48.nq.gz
    ├── 5b0afe36c3ce63933a4a674b47c4b2fd51ef8e62.nq.gz
    ├── 5b4711b5fa979285adaa0e2de918d8647ef44501.nq.gz
    ├── 5bd50339413c4a53307b89c5778b5837c467a7ed.nq.gz
    ├── 5bf406a27a7af3c1581fae16641bafb5d85dd737.nq.gz
    ├── 5d898abe5d2ea4185c6736bb2e535bef4e0ed94b.nq.gz
    ├── 5e32fb778d344679d8b7b7bbce82d00efac954cc.nq.gz
    ├── 5f6490b36f78605c9c52bad9fde6f2fdee90faf3.nq.gz
    ├── 60253b3ade93186deb4ddd3e5c089c0507f4d8dc.nq.gz
    ├── 62dc5f1f3cfd39f95f1329c21bc01c4a4dff5057.nq.gz
    ├── 63eff02379554809602d86ea171b959960153c54.nq.gz
    ├── 648671432f63c25cec938ed59439a277993d66a1.nq.gz
    ├── 66673d56e2c81a00a28b41cfea9c924586bb20bf.nq.gz
    ├── 67d9261e03c31fad5ac8282eac74c230c37d4d91.nq.gz
    ├── 6810e04e32878215c32b2039277d4b1809f4de4a.nq.gz
    ├── 6befdcf5dc0d33602a064d999c9910483edd6dfa.nq.gz
    ├── 6bfec614954ee6ddca98ddcc3b8b7d4095f8089c.nq.gz
    ├── 6ec954f7865630c62e142c0663f0621136de74d2.nq.gz
    ├── 6fc4fbca8332f3bc2474f30f76c85b72394033b9.nq.gz
    ├── 707d3f4c581178bab0bd740669544fd34d0f0583.nq.gz
    ├── 7198617132acf3126bf30dd496eaac2e456c8fbb.nq.gz
    ├── 71a19843002a11a9d981ab8722349b92e6785c1c.nq.gz
    ├── 73feaa42cceb0da3d594be3ebb0e8b9877fe748f.nq.gz
    ├── 7446e186e385959159bc2837a9fa5fa15565040a.nq.gz
    ├── 74d7b211fd148204109b970088f5d00005d9448a.nq.gz
    ├── 7712d1cdca5e47a06f6bef1d3ae654a2acc7a40d.nq.gz
    ├── 779eeade9a132cc6a49ae2c36067c3a461d17038.nq.gz
    ├── 77d1a1ef22c601e93e47679081741513fffd4952.nq.gz
    ├── 7a4f790e67af45390a6bc426318b1b39af7a42f4.nq.gz
    ├── 7a500f0ad833b4723699aab993675f0478bf6c31.nq.gz
    ├── 7a7e083ddd879217c9c9e5a385a9c7ac7cbc18c3.nq.gz
    ├── 7ab27ffb679c05733581c5121e196b1897db2f0c.nq.gz
    ├── 7ab80e6c6822aab0af8c580ecb094c5cab8b776b.nq.gz
    ├── 7ba57575e437822d09542d5970d782e4c438fba8.nq.gz
    ├── 7d159a21248546d54447d15418b9e26ab4e43465.nq.gz
    ├── 7d3b5a1f3e2e53266d5df1c91d00a9c9c1217b3b.nq.gz
    ├── 7f4cf5ca209a9235bb457e73c42831650cfaec33.nq.gz
    ├── 814e2844e00142a0f5e2f0a9a403df2e68658eef.nq.gz
    ├── 8176c930acfb71dbe78dd889d45c58c6a710a982.nq.gz
    ├── 827f9c9f85ec0ca421cca090ef698c2450b23f02.nq.gz
    ├── 834e03eaddc503c7c96479ab4bd573025044ae5e.nq.gz
    ├── 87fcb665760fa4df582351eb5f9ff04de1f84809.nq.gz
    ├── 894ec437cbd20d7cbc89e25a0783532c8849e172.nq.gz
    ├── 8977c10cb0e3dbe013d49b9782f1ff063bf586f7.nq.gz
    ├── 8d11e571a6aefcfc47cdf184fae5a387a6139698.nq.gz
    ├── 8e35c82831a4cb39eba39ae8ac56d2eecbb8e9c0.nq.gz
    ├── 91b5f82c7bbb86cc2b9ac6c895a07c48bca13ca8.nq.gz
    ├── 92ccd6812e7757147dc57151f384cc3ca812f6e8.nq.gz
    ├── 93ccd3504d46ab9512eb7f459736db6a36083592.nq.gz
    ├── 94731347c36ecd5e3ded9e2aae757eca4edefb18.nq.gz
    ├── 969d893327e419b460e5a2d49dd58b9485c7c0fc.nq.gz
    ├── 9868834229455653a4e3872c2bc997a2a3491ded.nq.gz
    ├── 98cb82e16ffcdfaad0d0ecdaa5335f9bb02dc699.nq.gz
    ├── 992667cbb8bfb7a75cbb1f370572ca45de157d26.nq.gz
    ├── 9a268f17f1a22ccde76cc5f11a9161904e721a09.nq.gz
    ├── 9dc74fdfc90af135f9ce50e36d35ec1e03f01e26.nq.gz
    ├── 9fad0d343c07aa82e21752481014bb870092c693.nq.gz
    ├── a09bcdba4e05b87c02b073d71841432e934f9533.nq.gz
    ├── a180706b69a6fb48c058fd078b923107177d1def.nq.gz
    ├── a1c20046a9ff095ce4446fd5b6e6d05c8f60cee8.nq.gz
    ├── a287bd75e3d2e5cb5492d7f264406b24653aaff6.nq.gz
    ├── a345988e7e2e1ed0a52f19cb84d8638b16220db6.nq.gz
    ├── a4060bd04b07e36ad551e56291a3c2c5d4a0cc31.nq.gz
    ├── a4afe6355c101c835fa7571d49be6f6c90be3439.nq.gz
    ├── a87914cbec4385aef569d77ae4cdfe3ff8dbf517.nq.gz
    ├── aa216e0378291f56491226dd450b8cabd20ac6e2.nq.gz
    ├── ab447575884a7b98b48ca4059b0e053e9834d6a6.nq.gz
    ├── ab4a0225f63b8b3b600f0ee4c772e7ba6a97fa7c.nq.gz
    ├── ac2974fc19b99c1beda479152346cdf33f702f42.nq.gz
    ├── ad1f53677afcf690d527a07367a6bc55a8255b56.nq.gz
    ├── adf017b06bfe083192d62a948b90fd873cc76780.nq.gz
    ├── aebda436be1b13fa2db5570058e098d66b5c57a3.nq.gz
    ├── b19227375ea60cd975bbba8b829841dd38a300fa.nq.gz
    ├── b1e21523edbd4ab90f68b2b081dd3d303e33bbdb.nq.gz
    ├── b255ec451e3dbb957ce0c748f17dd8d8f854d5ec.nq.gz
    ├── b39c9681932adc105f71678bf1b69119595007ae.nq.gz
    ├── b3c893e6e08cd1997f0925397e1359ffee5d7f89.nq.gz
    ├── b560a9ba08261b32b7b124747677a111c223d44c.nq.gz
    ├── b5cec1004516279d9420f084e98a238c50771940.nq.gz
    ├── b65e9ef6f8a892190d857d4b1923110400ecbf17.nq.gz
    ├── b6c4a4853af5dbad5fc231618098c0aa36a4bfd3.nq.gz
    ├── b79a1cb78ceec7fe85a9aa540189ebbc9c13e6b2.nq.gz
    ├── b7c4117cb321f726329cf1ddc910770f1dab41d7.nq.gz
    ├── b8d2f36e57870b0994ece9875577ca2c6d596422.nq.gz
    ├── b90981e55692569d65f4ed49f0275cfdfb195ad1.nq.gz
    ├── b9fb3525296f0b169c089c954e774012aee1f427.nq.gz
    ├── bafb8fa15d41694b50223607451cc5b606c3ebab.nq.gz
    ├── bc89798f583ceeff5b7d50a6ad47f57af5dc3f32.nq.gz
    ├── be331c0d8f5892aeaf92a0235e0f0e414c84e3b0.nq.gz
    ├── c07ea92daeab9e6fdf0b952c202cd4d1e162d59a.nq.gz
    ├── c194cbc56d5f8ef285984e72aa76ef3d0fc9b290.nq.gz
    ├── c27b58c559a26ffc7f9ed40f2eff8ac548df562e.nq.gz
    ├── c2b10e75fcb3c7f310f348166f5b64a847641b85.nq.gz
    ├── c391f3c48e110b85cf13b68051a506c0f60d4d3f.nq.gz
    ├── c537e083a39e1f57dbe30bfd4a180c01ca0d9a0b.nq.gz
    ├── c5a226304631487b17f97f3b60b223f4ca195354.nq.gz
    ├── c63716c91fad953f74e9404ae96d511f74b43e80.nq.gz
    ├── c68873e5eabbc3ee45a4a0ab49ff86a85f3ac913.nq.gz
    ├── c698e22c3fcdf04779137384495370bd73f88fb4.nq.gz
    ├── c6db3889314f3224604c7e448ae55c328fea2e21.nq.gz
    ├── c72b16e1f75c03440c3fef906f90157e8f79fa5b.nq.gz
    ├── c8d55821022930f42b6ccfa41e7bc43ca3390f63.nq.gz
    ├── c9388e050706841ff46fb0e0d38f0b1b821c5e9d.nq.gz
    ├── c96bab99af7140aa472190ab76d1a51599ad92e7.nq.gz
    ├── caf03cff8627b918391865262e5c9b8129c41591.nq.gz
    ├── cafec3b05b4b6c5e04e3211852c15093cbe1b233.nq.gz
    ├── cb425361bd8b444818a967e076900e882cb1e438.nq.gz
    ├── ccc91b002850e5c735cce1140840411122acf03c.nq.gz
    ├── cdd5fa72163f2e5d661d3f43539150d1230ed771.nq.gz
    ├── ce027171c774a0538c99f6ca911c12c0658dbcfa.nq.gz
    ├── d0405600c72c69aeb3226b0cce97acda270b1f9a.nq.gz
    └── d0d45aa4c3c9ae373f3378a8c4bfffcb486e68dd.nq.gz

7 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[ansible-collections/ansible.mysql](https://github.com/ansible-collections/ansible.mysql)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
