### Hi there 👋

#### Work

- I’m currently working on supporting remote debugging under a process-level virtualization system.
- Previously I worked on supporting sanitizers (`ASan`, `HWASan`, `TSan`, `MSan`, and `UBSan`), profile-guided optimization (`PGO`), and `QEMU` for arm toolchain. Here are my open source contributions:
  - LLVM
    - [Update macro for OFF_T so that sanitizer works on AARCH64](https://github.com/llvm/llvm-project/commit/a5a6fd3f95a9ecc3ef8732192ce0fd7749135311)
    - [Fix memory leak in `GetGDBServerRegisterInfoXMLAndProcess`](https://github.com/llvm/llvm-project/commit/1267506ea54a62e0c728215c033b256ce856db30)
  - QEMU
    - [linux-user: Add AT_EXECFN auxval](http://patchwork.ozlabs.org/project/qemu-devel/patch/20200302193153.66415-1-yuanzi@google.com/)
    - [linux-user: Update TASK_UNMAPPED_BASE for aarch64](http://patchwork.ozlabs.org/project/qemu-devel/patch/20200730193932.3654677-1-yuanzi@google.com/)
    - [gdbstub: add support to Xfer:auxv:read: packet](http://patchwork.ozlabs.org/project/qemu-devel/patch/20200730193932.3654677-1-yuanzi@google.com/)
  - GLIBC
    - [locale: align `_nl_C_LC_CTYPE_class` and `_nl_C_LC_CTYPE_class32` arrays to `uint16_t` and `uint32_t` respectively](https://patchwork.sourceware.org/project/glibc/patch/20210401193723.1224640-1-yuanzi@google.com/)


#### Hobbies

- 📚 I’m currently learning the design decisions of specific operating systems.
- ⛰️ I like to go on hikes and explore my surroundings.
- 🗣️ I am a club officer at a local toastmasters club and attend weekly meetings.
- 🎥 I like to watch movies and write reviews.

<!--
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- 📫 How to reach me: ...
-->
