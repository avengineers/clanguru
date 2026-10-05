# Changelog

## v0.1.0-rc.1 (2026-10-05)

### Bug fixes

- Split compilation database command strings with shell quoting rules ([`cb076ef`](https://github.com/avengineers/clanguru/commit/cb076efdccdb87c9d87ebc9d2847f32a1a2db8dc))
- Parsing fails because of invalid options from compile commands file ([`4eab9cf`](https://github.com/avengineers/clanguru/commit/4eab9cfb10d5a46692bc1f8ffc1fe5254ca26bbb))
- Global symbols are not found in mac os ([`96aa83f`](https://github.com/avengineers/clanguru/commit/96aa83f221655d8d04ff4da3ee3539be827ad37e))
- Directory filter not shown properly when selecting nodes ([`d007e39`](https://github.com/avengineers/clanguru/commit/d007e3989d737328b8cebd9c3ed1d4271980a859))
- Same symbols are mocked multiple times ([`a31c50f`](https://github.com/avengineers/clanguru/commit/a31c50f17ed2462ef2158e7970bd6dff9858897a))
- Links in pypi are wrong ([`4f962df`](https://github.com/avengineers/clanguru/commit/4f962df315e212d087c1c0877a5d5cf1d72733e4))
- Pyyaml dependency is missing ([`2111a97`](https://github.com/avengineers/clanguru/commit/2111a970d894b3303fdd338d966a47f0f179cbd3))
- No code block generated for classes sections ([`e992f26`](https://github.com/avengineers/clanguru/commit/e992f2687f1fc84d312f1a0cf82ff27e1ba98802))
- Wrong comment allocated to class declaration ([`23b9532`](https://github.com/avengineers/clanguru/commit/23b9532f25f4f13f48aa0674bef58365fdd04f6f))
- Comments are not correct if the source has windows newlines ([`0fd676f`](https://github.com/avengineers/clanguru/commit/0fd676fc07ea149b86c3de2ca87472af815df3a0))
- Function bodies are not correct if the source has windows newlines ([`31b4eb2`](https://github.com/avengineers/clanguru/commit/31b4eb2176a4166e09ef3cf1ef008820890a51f0))
- Compile commands json export is invalid ([`ff13606`](https://github.com/avengineers/clanguru/commit/ff136067da32298093d3f0a53951b5a19af2f381))
- Explicit jinja2 dependency missing ([`a820d94`](https://github.com/avengineers/clanguru/commit/a820d944adf6265e70b6062a2cd38195d44ab291))
- No apps associated with package clanguru ([`414f697`](https://github.com/avengineers/clanguru/commit/414f69701e8fe07f890fed951888768ecdb7e6bb))

### Features

- Try to find the correct nm executor for the compiler ([`9898e83`](https://github.com/avengineers/clanguru/commit/9898e835f34eb84c52d1f5233f8f7c9c86f7d6a0))
- Use token caching to drastically reduce parsing times ([`b952172`](https://github.com/avengineers/clanguru/commit/b95217279df25a0bf7659f993c09a25b4ab2cc64))
- Add option to generate jinja raw tags for code blocks ([`b458c7c`](https://github.com/avengineers/clanguru/commit/b458c7c9ce3257c75de571129c31c7d02dc9817b))
- Support placeholders for source code docs ([`1a0c3a9`](https://github.com/avengineers/clanguru/commit/1a0c3a9a5f351c643659ed676615525207ef1264))
- Support docs tags in source file comments ([`395176f`](https://github.com/avengineers/clanguru/commit/395176ff343b53f0691b0a0e2dfa769c82525c35))
- Add help for the object analyzer report ([`3c3ef49`](https://github.com/avengineers/clanguru/commit/3c3ef4904bedc90c153dd8a69039fe5d38ccaf7b))
- Select nodes and edges ([`0bbbff9`](https://github.com/avengineers/clanguru/commit/0bbbff97e39303c2e5d45714c90228b1e2f42c3d))
- Double click on nodes highlights filter ([`0bbbff9`](https://github.com/avengineers/clanguru/commit/0bbbff97e39303c2e5d45714c90228b1e2f42c3d))
- Add directory filter for object analyzer ([`2ced0cc`](https://github.com/avengineers/clanguru/commit/2ced0cc83a401ba4e76ff7a947a980c179371e3f))
- Add search field to html report ([`38f93ca`](https://github.com/avengineers/clanguru/commit/38f93ca420800cc6559e431f1e5ed45280427f55))
- Add option to exclude irrelevant objects ([`22cccda`](https://github.com/avengineers/clanguru/commit/22cccdab6beac525a1c27a2f1fd3080524f55644))
- Display source files in the object analysis html report ([`2d4c27d`](https://github.com/avengineers/clanguru/commit/2d4c27d9a2c5f48a2abe4ed3bb34a4749ee1ef24))
- Add option to exclude symbols for object analysis report ([`b210312`](https://github.com/avengineers/clanguru/commit/b2103123453b626e3111184ac2347960b0186506))
- Add option to disable objects traceability matrix ([`0dcec99`](https://github.com/avengineers/clanguru/commit/0dcec9960be79fa452933affe1c93d273db455fc))
- Show error message when file can not be parsed ([`970efbf`](https://github.com/avengineers/clanguru/commit/970efbf75afb4e98ae92d2f5589d007289c8fd7b))
- Get code block location in source file ([`53541e9`](https://github.com/avengineers/clanguru/commit/53541e9bb4bf4927d6b2aed82ca2d938930bc62f))
- Rename docs command and support myst markdown formatter ([`7b1b4ab`](https://github.com/avengineers/clanguru/commit/7b1b4abe0be46acd8fe7dad120565cb74b4de742))
- Add table formatter for docs generator ([`b235405`](https://github.com/avengineers/clanguru/commit/b2354056aaa718cc21b3bf6584dc426bd950c7cf))
- Filter compile database for source files ([`635831f`](https://github.com/avengineers/clanguru/commit/635831fe9fb1dd667569e7664dd24e1bb851843a))
- Add mock configuration file option ([`6b993fa`](https://github.com/avengineers/clanguru/commit/6b993faef1e2e1453d2cc9c521943dea800ede02))
- Add mock exclude patterns ([`9e51ec6`](https://github.com/avengineers/clanguru/commit/9e51ec6b60466d143e13a915eac4e9b217c96478))
- Add mock partial link object argument ([`05a5735`](https://github.com/avengineers/clanguru/commit/05a5735f92233b69966c0bef0fd9d6b47a951a89))
- Generate mock log file per execution ([`9e67022`](https://github.com/avengineers/clanguru/commit/9e6702296b1277a5cc9a9f19c32bc4165c54e82e))
- Add mock generate command for gmock files ([`830a442`](https://github.com/avengineers/clanguru/commit/830a4426eec5f4fb61d0970f8c3ac3b7dbd0f645))
- Find symbols in translation units ([`1cfebcc`](https://github.com/avengineers/clanguru/commit/1cfebcc97e0c5f456dc06789798f6b3d579ee880))
- Add column for dependencies to the excel report objects sheet ([`a869a9e`](https://github.com/avengineers/clanguru/commit/a869a9e8e31adf0f8d047dc87a6fca2f318073e3))
- Fixed headers while scrolling in excel report ([`8567caf`](https://github.com/avengineers/clanguru/commit/8567caf244b3f854701eb74cea32e0bc166c2232))
- Add objects data excel report generator ([`e9adab2`](https://github.com/avengineers/clanguru/commit/e9adab2aa5cb953e7c07296dcc78c0c7ad957b53))
- Create objects parent structure ([`9bf7b3a`](https://github.com/avengineers/clanguru/commit/9bf7b3ae95985022d869f1873c51c0e20aca5299))
- Support morel nm symbol types ([`f08ffda`](https://github.com/avengineers/clanguru/commit/f08ffda8d77f0735d5e6c3a5ae55534d57622db6))
- Add objects analyzer report ([`118a1ab`](https://github.com/avengineers/clanguru/commit/118a1ab6b23569d5b5a0e63854fd204c0c3a3e5a))
- Collect variables ([`07f507d`](https://github.com/avengineers/clanguru/commit/07f507da310f04a2abb369092b1e20b7edab8975))
- Add basic doc generator ([`97cd5eb`](https://github.com/avengineers/clanguru/commit/97cd5eb10ea6db65082acb9021c1feaa3657e303))

### Documentation

- Add instructions for ai agents ([`8683db1`](https://github.com/avengineers/clanguru/commit/8683db1b2c844f94749840f6f4560460bffb4d23))

### Build system

- Fix semantic release versioning ([`23230ca`](https://github.com/avengineers/clanguru/commit/23230cae9dc31bbd4ad0df876485a7f685cac08c))
