# Repolex Knowledge Graph of astropy/photutils-benchmarks

RDF knowledge graph data for [astropy/photutils-benchmarks](https://github.com/astropy/photutils-benchmarks), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/photutils-benchmarks
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8a9ae29a4fb2a49d30ce5a7f727ae4371c73cb7e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8a9ae29a4fb2a49d30ce5a7f727ae4371c73cb7e
│           └── chunk-001.nq.gz
└── blob
    ├── 02e4baa61ac8157fc21fd3e1ec2032a42d34f0e9.nq.gz
    ├── 030629156e52ba65a87c23f1a660729ba48f863b.nq.gz
    ├── 052a2bc15196d4920676e7e92d7a374eb8e59de8.nq.gz
    ├── 052e14df6304a51da9df11fa73528b8f63fc7d1c.nq.gz
    ├── 05f87b97c3ca9c143f40c63387c0e28cc8ff14b2.nq.gz
    ├── 06c287b1e28d86a3a3540ddb300dfe861a1979da.nq.gz
    ├── 0705fd182994a9c4b3997c775bf8d0cb6037b74a.nq.gz
    ├── 07fc7bd93e4985a26827187ce09064874ada170b.nq.gz
    ├── 088a6d2657e0a32dbcf54541dd8330c73d336f86.nq.gz
    ├── 0abfcff0c5ac5076404914595eedd5d2860131ae.nq.gz
    ├── 0b8dffa38826fd38c5175697c0d66044ac6b0c79.nq.gz
    ├── 0c6a882d140d4511d71a813200509313dbf21c57.nq.gz
    ├── 0d44311f03740228e5c1612e89bb749a7e57bfca.nq.gz
    ├── 0dd96f73ed7eefc172ffe4ef678fb7cd340bf1fa.nq.gz
    ├── 0e9787632b87804a20e43fbf630223de4a57ce3d.nq.gz
    ├── 0efcaca48f8c64101f7a1d7b52f0e518f4d89454.nq.gz
    ├── 106ef10d5725af44caf1f907b6de0d38d358420e.nq.gz
    ├── 110ff3be0c7a0dfc95f4d02c3af9a83111ee42d4.nq.gz
    ├── 132f6731c5e787865f080325b9c0a8a91f69869e.nq.gz
    ├── 133bf9121a5ad2caab8d586adafef6d5f0e455e2.nq.gz
    ├── 14eab55fb6c29f0196252629d0f5d03626564b10.nq.gz
    ├── 16f4a59ee2299545ad866189204ad583c2b1214d.nq.gz
    ├── 173476fe03e40dccc57f682526846d4e1254861e.nq.gz
    ├── 18c56a395cb85cda08aa0a112e76ac3312d84ae5.nq.gz
    ├── 18ef2c9b95c831031a3bc440d21313bab34011e3.nq.gz
    ├── 195df26efbb12b5a3322738cde5cebabdfd270e0.nq.gz
    ├── 199c12dc9020a540ec5f7366ada10f2bc17a9159.nq.gz
    ├── 1aaf9cfd1ddd5c1255283879807ae751c74c1ad4.nq.gz
    ├── 1bd9f91f434e7a246f359a494e1908de0710d037.nq.gz
    ├── 1c0bbfebe80ffd8afab77b70ea3b27bbff553506.nq.gz
    ├── 1d0df78d9c02c4f1d629b459e6260b90db1c52cd.nq.gz
    ├── 1e0ddab602cd1ae3b0dd9eb2d72f5aeb8498a095.nq.gz
    ├── 1ee9fca30f8a6e74805c1433b424ffb88cc9ab48.nq.gz
    ├── 203c3a11a8e62911fb91659e42c6aa7f5cb63bc0.nq.gz
    ├── 219e576d89f13f2f787a14bcf2fcfe2a6918da9d.nq.gz
    ├── 221826c5af35a92ca2815d9a09056eeb2804fcf7.nq.gz
    ├── 24b40fc7c4a23a9deefb71ddc1ce4ddf69d1d9d8.nq.gz
    ├── 250f69486e454cc5ef22ef08434dc823af66a3f2.nq.gz
    ├── 2578e04c3fe11afd108a00bbd06d22146e3c8532.nq.gz
    ├── 25d91d5e4afd982f33beffd0050c5726629f7460.nq.gz
    ├── 261d3de973e42ab4afb66fff5c2b4654573b749f.nq.gz
    ├── 264436a44240a61deeeebc227787ef90b1c8dbf8.nq.gz
    ├── 287dbb2e1635bb115ab07242e4425ebde63d665f.nq.gz
    ├── 295a73b19a6230f48033406cd72e45719fc64028.nq.gz
    ├── 2991e8589396a895a426246254b1b8bfea00bdf6.nq.gz
    ├── 2a2419f313c342b74e1391f51c3e6243c39fd585.nq.gz
    ├── 2a4f0fb5efe389d05b27928c9765dc2a5bf06b6a.nq.gz
    ├── 2e48f8913f79360f11a582edcfa5449ac86298a0.nq.gz
    ├── 2ed7401acba6d03e083a466187d67ed89099e470.nq.gz
    ├── 2f4f326a698e0e1df3e680c8d52ca6b861101b40.nq.gz
    ├── 2f7aaa02f3b4679a98aa08bcac2e800ee190fd43.nq.gz
    ├── 2fe0868908f05417c8868819ca8a18d37bcaa368.nq.gz
    ├── 329ad17675606a835955ec8f75a874e343a571a0.nq.gz
    ├── 35aabb1bbd02a2a292cec3020646022399811613.nq.gz
    ├── 3687fd8c9affa24d396585457c322ff292043045.nq.gz
    ├── 378e67abe22f8faa4cb78df13aaf00d2e9b62d2d.nq.gz
    ├── 37f4b4721f2eb9269226973fa5e3940ccdbede89.nq.gz
    ├── 38078399dffb4f12c1330bb061ed87c0a18e0662.nq.gz
    ├── 383000fe1dc78e3eb27b872ae8b1eab97bf7d485.nq.gz
    ├── 3b5f2ec0d43a93c549759b100fd2730c3946f652.nq.gz
    ├── 3ba21f33240be96413834319f8ba7e0cca3691af.nq.gz
    ├── 3bea8f0f3ea765fdeedde30f00ecabe0c023a1c3.nq.gz
    ├── 3bfb18c7b2fe7cefb8ffccf139da15aff7f3f030.nq.gz
    ├── 3ec676cd73bd7893c47780dcade723908339e84f.nq.gz
    ├── 3f012cbae3c4545d8a414af16c806b2dea6d7ce6.nq.gz
    ├── 40195587ffddd4fc4f4b00056f220f2bef063731.nq.gz
    ├── 409a92ed014402886f5127112ebd5d8cca632adc.nq.gz
    ├── 415631917926197fefaa5343d9e4265c253f7d23.nq.gz
    ├── 419dd0170b421bb40e34506b621e7703918c04d2.nq.gz
    ├── 4220763ea3b324a04f8173141b702d1e39bf7d70.nq.gz
    ├── 42b4d15da6993f0cef3181ba17cc6ef2e2aaf5d2.nq.gz
    ├── 4482e957643ce542b708f5dc878e0ed4033edea3.nq.gz
    ├── 44d6d13d1529935b4d087d0caa5d4213eeb174b2.nq.gz
    ├── 456df53001d3fc86f9dc6e48656e1de1a7919bf7.nq.gz
    ├── 4635d7624f37139e33171cc4e06046fae410b295.nq.gz
    ├── 470d6692c3b10ad0ca59cdb5176c4f36af99eb33.nq.gz
    ├── 47c969ab5b4ab2ba95fbcdbbab829f69e019a68c.nq.gz
    ├── 4bf9b887bcd376c8f1b688a7788526347a8faf44.nq.gz
    ├── 4c3c5a11bc18de414ab2f89e2c7e2769cac68d50.nq.gz
    ├── 4cb34d76053ca7c262c042d415ec056ad2bb1994.nq.gz
    ├── 4f0b8cd067daa13b6c64f58008bfb201aae9b0cf.nq.gz
    ├── 4fe83f5b518f68a2433c7d0694fc716bf5236845.nq.gz
    ├── 500645135a1255c38dd60dface4061804d86b321.nq.gz
    ├── 5051a8415adf2fe327f25ff098766e8c981352e5.nq.gz
    ├── 50993123b322a474d407a50020e3b1674cdf7e9f.nq.gz
    ├── 51819985fbe38b3dafeee727ad2232624a477396.nq.gz
    ├── 53ba473d338aee62981b0cb0b3e226685b1cbdbb.nq.gz
    ├── 552573220d5d736c06886a8e02807e9727de75f7.nq.gz
    ├── 58074dcff22cffdfafb5416697c85a8b07cb5b08.nq.gz
    ├── 585257f122ff95405032dcdc5739bf8a1a972993.nq.gz
    ├── 5c16e5aaf7ea8e902c680861fb4f7f9298d15395.nq.gz
    ├── 5d643f109490aaf21039fcf1f9ba8ed45c80af86.nq.gz
    ├── 5e109a35b0eb2dc4490841e96fa7cafa3767e46e.nq.gz
    ├── 5e2d45261f9d76fb7bf6bc113fe5c726ed24f1c7.nq.gz
    ├── 5e83ea673ba18499d87a8a80eeb6438ddf067507.nq.gz
    ├── 615ea7b14c40ecf0489bf9b35d59ced1bb49e94b.nq.gz
    ├── 6182ba15f37c51cf4d6329460aaa962fe1f56866.nq.gz
    ├── 620b8172e88826a8ecf85f9e7e94d0e96ac227fe.nq.gz
    ├── 623907e7260c773b088098f7580ae1479a0d36f4.nq.gz
    ├── 626626f71e22011b9bfbd1016fae294bb46bdc1f.nq.gz
    ├── 644b846cfa0f1fc81bb0d2439536bc2465e08490.nq.gz
    ├── 647706b6f6917831c3abcbee47aad0ce932fbe02.nq.gz
    ├── 656af331a167489359447f5954b23e076d8eb2a1.nq.gz
    ├── 66dd7efeb7c434985d3b7ad86393f67dce462699.nq.gz
    ├── 683ef5965e78b5559888b469eb19daf06000d4dc.nq.gz
    ├── 68955b69ce98e4c6fa775a05da88e5877d43d8dc.nq.gz
    ├── 68f43208ec78e665126c43ec687a3943523e43c7.nq.gz
    ├── 6a67871badfe59652fde645dc536168827ac6af1.nq.gz
    ├── 6bbfbe8655a5d855bc35a92fd595b892809f4dff.nq.gz
    ├── 6d955a4aad74a93112de4d49b8c87ba22d5d9bee.nq.gz
    ├── 7106dc34ed5e72e68265abfaac786fff1d731129.nq.gz
    ├── 713ebabac29e4349caddc5e8fb31aad9e986beb8.nq.gz
    ├── 71f175a28b283ad25cf743e28309606204c95542.nq.gz
    ├── 71f7aeedfa481c31e12a41ce8f0444fd093b1241.nq.gz
    ├── 72e3bb334916943c347d557bf68bdc8d471c0280.nq.gz
    ├── 76822a3de2dc2f3ac73740dbca2db5146520568a.nq.gz
    ├── 77231c5834e2cc34aa0c6de62b092dbf84620dea.nq.gz
    ├── 782ed95350819fbbddb04ffd11737dc78499fa31.nq.gz
    ├── 79543b0fa6301d57daef8bdd1303cb446fab5e69.nq.gz
    ├── 7a57d1edda8f799fb86973d682576ba67bfba143.nq.gz
    ├── 7bfa89527a652a7ab623566dffed810393878347.nq.gz
    ├── 7c1261bab96f145c4cb29672f7ad980afd26d26a.nq.gz
    ├── 7cb50e4415fbdf33e165b6a8c682fd6ebf4bd53b.nq.gz
    ├── 7cf51bcb58c19e4fb90d7f55b279dba1b9ea7869.nq.gz
    ├── 7dce653e50412f4820b06f342a12904db74f6417.nq.gz
    ├── 7dcf38b62e9bca5b9122a04b7bb69be85d28831e.nq.gz
    ├── 7f22d08923cd86fe93f412bd3654be9735c2df91.nq.gz
    ├── 7f56750183df4e44d7a9e1919bab231d2d11a354.nq.gz
    ├── 7f7c5ba5e730a29b1c1520a457c7e33b033ddfff.nq.gz
    ├── 7fdb9e4021dd439ce716c8b06acb179c5a2565f7.nq.gz
    ├── 8010d2f09b20aefc235a60dac427e4e3cbf5bc66.nq.gz
    ├── 803d74399d8e7d2665fd335a6bd277abe9bfde2f.nq.gz
    ├── 8147b74ad239f125ce4b79fdae928def6134dcab.nq.gz
    ├── 82b83817726c618c90ae400567c4fbc00084441f.nq.gz
    ├── 8323a86dc16bb11dfdaf056883e65b6d4245dfae.nq.gz
    ├── 833fa823a1f0da61f381b776547c1cb5ce5ae854.nq.gz
    ├── 83ce4a92d49cbc9cd0f75d323ba6d6873e937f2d.nq.gz
    ├── 8451fea5954101f0328b4772ad4cc38ac33525c1.nq.gz
    ├── 84cf42c1ce2ccb1b6a5f75c6cf7532e8060d1be9.nq.gz
    ├── 88432a7e890dceb163254154d0ad20a75f388154.nq.gz
    ├── 8b57a251bcd81e81d3170cfbfbbda2f6cc6cce78.nq.gz
    ├── 8c266016d82dcb1f62ee73481568da6dac42929d.nq.gz
    ├── 8d3d391e8d8f94f49303c24eea528b3d77cc6d60.nq.gz
    ├── 8dc16bb4f12a9fea1350b7eac56fff55ed272d86.nq.gz
    ├── 8e2937f36787bd80350e2d7f5dbd338946216811.nq.gz
    ├── 9275b9d9752175d061a12d4451b68b0e9e3de7e7.nq.gz
    ├── 92f5d8bfa0054914e0b55b9861f1df99f189104c.nq.gz
    ├── 94133ee42fa88595b4d2a2de3bb6e9a6dd5af186.nq.gz
    ├── 946a60aa2475b23453db180436a342ee2ef51a7e.nq.gz
    ├── 94ce02e95090d48aa43feccb48e551df48c9de23.nq.gz
    ├── 94d5c45145202f51fa94425ff785ce436d04aa6a.nq.gz
    ├── 99e2669c18afc1bdb89c1fdd231921a9f4196744.nq.gz
    ├── 9a3842a930d2ad845a20c35a2ffc0211f8de1ede.nq.gz
    ├── 9b14d0188f1885d1e37c104b4e67e2d4cc0a83a2.nq.gz
    ├── 9b29a90ab4ae22d942c467bbc2c35ed3a82934de.nq.gz
    ├── 9bb44f9c70c953f898246b9e1d830e533136d2d6.nq.gz
    ├── 9c14c5843ed69460c65ede409cf90190be082ab2.nq.gz
    ├── 9cf9e1399df25bd45dbe2586ba80bf15c7f6b4b2.nq.gz
    ├── 9dc9206a18cbe43a28860b79b3d106f42d3f23ec.nq.gz
    ├── 9e9990e2d5cd06ed1382c7fc31c60b676eb54c01.nq.gz
    ├── a085d2c0ed6fd2fd2a60dad7ad2244af478f6140.nq.gz
    ├── a27c4a559e545be52656241661046900aeb0a8c2.nq.gz
    ├── a4a3515b0dc40f1846b3943d578a03abe3c1130c.nq.gz
    ├── a5a3e01f5affec3d09114dfb07b79d685e28c7ce.nq.gz
    ├── a78e49bb611d0d2541e4d03f883a87dfca2f7595.nq.gz
    ├── a7d7cee6f4f644a6602ab155a748ee2f6aacd49f.nq.gz
    ├── a7eab89873d97af373186daaace8dda2458d0fb6.nq.gz
    ├── a9ec5286cc5544dc3cd18fbc29462451fa4308c6.nq.gz
    ├── aa6a39555ba4f9ae6b246320325bdb5c9050011c.nq.gz
    ├── ab3254847903b5d3f3929cadeb24a45c83d0fd60.nq.gz
    ├── abd9cbdd68047385b2e044fa593a8756ed9b7024.nq.gz
    ├── af8f6386c3ee0a8328e4921cd99f5aeadb55ef1f.nq.gz
    ├── b03064fe54e248c89201a6482877ae43e8330d42.nq.gz
    ├── b1341e1a06c8b447e13e40acf805d31fab7fff5e.nq.gz
    ├── b13e4315dd0da6d09bbc4c9ba854af1072aec7d2.nq.gz
    ├── b1b3daa8ff0c2b0fbad98a5a3e382bf4cdb88c05.nq.gz
    ├── b3ef6a931dc177125d32c035be157fc9cc8fc625.nq.gz
    ├── b5ab3b028161ca01335d0f8833d6fe66674f9a62.nq.gz
    ├── ba90a99db9e8c971bae8961b54e24a092484b0ff.nq.gz
    ├── bad91c4743f0db57d6ffd453f9a3b02f478a1a43.nq.gz
    ├── bb49bc945075a6d4eb9f5664b433056eb6902e57.nq.gz
    ├── bcda7f79a2a6c27bc10a8b7751496e77993e28dd.nq.gz
    ├── bd08d4aea5a38f9db116096281dc4e92a53b8d01.nq.gz
    ├── bdf58a657704c6ab1210b13724268938531ce474.nq.gz
    ├── bec81cdefb9455d14b1b1fd81243a3cccda83f5b.nq.gz
    ├── bef1e9184c1288a73e694b13c922f183b71c7e0b.nq.gz
    ├── c162a1c46aeca25bda6273668dc99117aad31a4d.nq.gz
    ├── c3d594f0e42a5b6a24b2304ef68c5ed81f3dd06c.nq.gz
    ├── c3ebee1a4ef5de3d369e208cce8d022437e56155.nq.gz
    ├── c6a06a8dc422e5229aee3a70d8a70d599467e992.nq.gz
    ├── c72de922197d165bc364f8abcd23e9c3cd118125.nq.gz
    ├── c7cf31a73128fcfa64edaf7cf3d8315d1c5b16d5.nq.gz
    ├── c824a85f9fda9453e17f29ccbd05d34a5366fe70.nq.gz
    ├── c92ff7804ac83e69c735de58e5ec713d43dd5a5d.nq.gz
    ├── cb2f208d8a8bb7aefec399983d32343d5fccc60a.nq.gz
    ├── cb711f5789bb2f749de2100aed04f0225723c84d.nq.gz
    ├── cba145072bd926d61653694fc10a55e92835130b.nq.gz
    └── cbfde6e33023eb77d61ab550fa77cdff8a522103.nq.gz

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

[astropy/photutils-benchmarks](https://github.com/astropy/photutils-benchmarks)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
