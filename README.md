please email <mailto:neglect@ember.software> if any of my open source projects need some love

catch me in matrix? web portal: <https://ember.dev>

i wrote rustdoc, started This Week in Rust, and a bunch of other pre-1.0 stuff [highlighted here](https://ember.dev/rust/) and [chronologged here](https://gist.github.com/emberian/6382f34b6674d1f9ec5ae93e17a27615).

## open source contribution grab-bag

Here's the reformatted list with project names first:

- **Gitalist**: [Fixed a small error message](https://github.com/broquaint/Gitalist/pull/32)
- **node-tap**: [Made it ignore certain non-executable files](https://github.com/tapjs/node-tap/pull/36)
- **sElement**: README in https://github.com/Tatsh-archive/sElement
- **pillow**: `import _imaging as core` https://github.com/peterhj/pillow/commit/f466def82dfac8f5ec73fc4726cbfc175fe19457
- **herbstluftwm**: Add help string to herbstclient https://github.com/herbstluftwm/herbstluftwm/commit/0465edbbeabd3dea07510a290b3682aab7c8282f
- **trayer-srg**: Fix bad format string https://github.com/sargon/trayer-srg/commit/fa1da88ea9a41e25cfa2b1f8be5e92a281c35f83
- **sinful.js**: Add Array.prototype.partition and rename echo to repeat in js util lib https://github.com/guipn/sinful.js/commits?author=cmr
- **jemalloc**: Ran clang-analyzer, [finding dead code](https://github.com/AndroidExternal/jemalloc/commit/35579afb55c0a53261743b3e292f60e76046ff16). Independently, also a [sysconf edge case](https://github.com/AndroidExternal/jemalloc/commit/1d553f72cbbcbacc1802d2cc96a4024315e616b3)
- **Vundle.vim**: Fixed bad repo url escaping https://github.com/VundleVim/Vundle.vim/commit/84c9a542541d4504deb8eed38f15fe5a2497b6cc
- **wsapi**: Got into lua a bit, [fPIC](https://github.com/keplerproject/wsapi/commit/0643db3b36b25132ef8e85ccf9e72e0eae09189a) and [linux support](https://github.com/keplerproject/wsapi/commit/731a43ecabc8900e8381ec947835b76e29742b4e) in a web library
- **ms.c**: Some minor stuff in a c library https://github.com/clibs/ms/commits?author=cmr
- **http-parser**: Wrote a debug tool for node's http parser, also fixed an ipv6 edge case. Also a build status badge https://github.com/nodejs/http-parser/commits?author=cmr. [Helped land some pre-HTTP/1.0 support](https://github.com/nodejs/http-parser/pull/144). [Abandoned some work supporting "generic" HTTP methods](https://github.com/nodejs/http-parser/pull/145). Added [travis ci](https://github.com/nodejs/http-parser/pull/146)
- **uap-core**: [Vom'd on a file but fixed it](https://github.com/ua-parser/uap-core/commit/1219424e390cf0374c7d413bd6f8081c0fbf1d53), also [taught a list of regex about a new UA](https://github.com/ua-parser/uap-core/commit/c59f751380a24e3466708747f5af1f3ec527040d)
- **the_silver_searcher**: [Taught ag to read gitconfig to find the excludesfile](https://github.com/ggreer/the_silver_searcher/commit/101b122504e9bdb3547c279d339224442ea981b1)
- **Utilities** & **RequestServer**: Worked on some libraries in C (later C++) with a friend for a while. He used it in some game server prototypes. https://github.com/arke-industries/Utilities/commits?author=cmr https://github.com/arke-industries/RequestServer/commits?author=cmr
- **playpen**: [Generated syscalls from headers in a sandboxing tool](https://github.com/thestinger/playpen/pull/11)
- **rust-zmq**: [Some modernization of pre-1.0 rust-zmq, started on some examples](https://github.com/erickt/rust-zmq/pull/10)
- **rustsqlite**: [Helped upgrade rusqlite when `float` was removed from rust](https://github.com/linuxfood/rustsqlite/pull/53)
- **gl-rs, sax-rs, glfw-rs, noise-rs, color-rs, cgmath, gfx-rs**: Contributions/general maintainership of several bjz repos, including [gl-rs](https://github.com/brendanzab/gl-rs/commits?author=cmr), [sax-rs](https://github.com/brendanzab/sax-rs/commits?author=cmr), [glfw-rs](https://github.com/PistonDevelopers/glfw-rs/commits?author=cmr) (now PistonDevelopers), [noise-rs](https://github.com/Razaekel/noise-rs/commits?author=cmr) (now Razaekel), [color-rs](https://github.com/brendanzab/color-rs/commits?author=cmr), [cgmath](https://github.com/rustgd/cgmath/commits?author=cmr) (now rustgd), [gfx-rs](https://github.com/gfx-rs/gfx/commits?author=cmr). gl-rs was fun, binding generation from XML API descriptions. gfx-rs has changed a lot since I worked on it, but I was once responsible for its (atrocious) texture/image API!
- **multibuilder**: For is rust slim yet, [some multibuilder fixes](https://github.com/huonw/multibuilder/pull/1)
- **apitrace**: [Fixed a bug that prevented tracing core profile apps on linux](https://github.com/apitrace/apitrace/pull/221)
- **hammer.rs**: Some work on an [old option parsing library for rust](https://github.com/wycats/hammer.rs/pull/2)
- **cargo**: [Taught cargo about per-platform config locations](https://github.com/rust-lang/cargo/pull/148) although github seems to have lost the commit range?
- **glfw**: [Enabled ASLR](https://github.com/glfw/glfw/pull/349)
- **iron** (urlencoded, persistent, logger, staticfile): Some small contributions to iron repos, [eg](https://github.com/iron/urlencoded/pull/44), [eg](https://github.com/iron/persistent/pull/28) [eg](https://github.com/iron/persistent/commit/5de64e06e8d6c7bce38fe4a66d40569c634e152c) [eg](https://github.com/iron/logger/pull/44) [eg](https://github.com/iron/staticfile/pull/12) [eg](https://github.com/iron/logger/pull/51) there are more not really worth linking!
- **lazy-static.rs**: [Doc fix](https://github.com/rust-lang-nursery/lazy-static.rs/pull/4)
- **xml-rs**: [Helped bring xml-rs into the new world](https://github.com/netvl/xml-rs/issues?utf8=✓&q=author%3Acmr)
- **hyper**: Added [If-Modified-Since header support](https://github.com/hyperium/hyper/pull/183)
- **winapi-rs**: [d3d9 support](https://github.com/retep998/winapi-rs/pull/59)
- **lapack-sys**: [LAPACK bindings](https://github.com/blas-lapack-rs/lapack-sys/commit/6fdc911254d648233d1eb2b259d8a2ae3eeccfc5)
- **blas**: [Complete BLAS bindings](https://github.com/blas-lapack-rs/blas/commits?author=cmr)
- **lapack-sys**: Designed reasonably pluggable (at the time) BLAS/[LAPACK](https://github.com/blas-lapack-rs/lapack-sys/commit/981f80cfffa480d15deefe1b3db81baba3ec597f) backends
- **pool**: Fixed some [unsafety in a data structure](https://github.com/carllerche/pool/pull/4)
- **glutin**: Abandoned some [joystick support](https://github.com/rust-windowing/glutin/pull/462)
- **bitflags**: Made a [nice bitflags Debug repr](https://github.com/bitflags/bitflags/pull/7). This got [a bit more complex over time!](https://github.com/bitflags/bitflags/blob/master/src/lib.rs#L469-L521)
- **nix**: Did some cool [ioctl work for nix (not that nix)](https://github.com/nix-rust/nix/pull/147). This replaced an [earlier crate I maintained for doing ioctl](https://github.com/cmr/ioctl) that I'm still quite proud of. It generated bindings from the kernel headers. Great for Linux, not great for others. ioctl are a mess.
- **VisualRust**: [Created VisualRust](https://github.com/PistonDevelopers/VisualRust/commits?author=cmr). Added a basic syntax highlighter using the lexer I built during my Mozilla internship. Thankfully vosen, an experienced C# dev, took over the project. Abandoned a [toolchain downloader/updater though](https://github.com/PistonDevelopers/VisualRust/pull/179)
- **Rust**: The Great Relicensing. [Wrote about this here](https://listed.to/@cmr/7767/the-great-relicensing)
- **sample**: Made the [`sample` crate, for audio processing](https://github.com/RustAudio/sample/pull/25) able to be used without an allocator/std
- **easyply**: [Some fixes to easyply, a python lex and yacc helper library](https://github.com/MHordecki/easyply/pull/4). Used it at Data61 during my co-op
- **byteorder**: Made the [`byteorder` crate](https://github.com/BurntSushi/byteorder/pull/46) usable in `no-std`
- **serde**: [`serde` `no-std`](https://github.com/serde-rs/serde/pull/316)
- **xmas-elf**: [`xmas-elf` `no-std`](https://github.com/nrc/xmas-elf/pull/25)
- **spin-rs**: Added [manual unlocking to spin-rs for FFI](https://github.com/mvdnes/spin-rs/pull/34)
- **seL4**: [Tweaked a magic number](https://github.com/seL4/seL4/pull/52)
- **ArkeOS**: Same friend as earlier doing game stuff, [this time with a fictional computer](https://github.com/Arke64/ArkeOS/commits?author=cmr). Made it run on mono in linux.
