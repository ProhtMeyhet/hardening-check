# hardening-check
hardening-check from debian checks binarys for Pie (Position Independent Executeable), stack protection, fortify source and immediate binding.

See [Debian wiki for documentation of Hardening](https://wiki.debian.org/Hardening)

Example:

```bash
hardening-check /usr/lib64/firefox/firefox
/usr/lib64/firefox/firefox:
 Position Independent Executable: yes
 Stack protected: yes
 Fortify Source functions: yes (some protected functions found)
 Read-only relocations: yes
 Immediate binding: yes
```
