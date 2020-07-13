# epic-musl

epic-musl is a fork of the [musl](http://www.musl-libc.org/) libc modifed to work on the [EPIC OS](https://github.com/nufflee/epic). Currently based on musl 1.2.0.

This should generally not be used on its own but as a part (submodule) of the [EPIC OS](https://github.com/nufflee/epic) repository.

<br/>

Current modifications:
  - Always use `int $0x80` for syscalls instead of vDSO and the TLS