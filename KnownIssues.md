This is the set of rules which is used to associate build failures with roundup issues.

It is parsed automatically by the bbreport tool to generate the [PythonBuildbotReport](PythonBuildbotReport.md).

| **Issue** | **Test** | **Message** | **Builder** | **Comment** |
|:----------|:---------|:------------|:------------|:------------|
| 6462 | `test_bsddb3` | `$` | `x86 Windows7 (2.6|2.7)` |  |
| 8265 | `test_float` |  | `ARMv4 Debian (2.6|3.1)` | closed as "won't fix" |
| 8391 | `test_subprocess` |  | `x86 debian parallel (3.1|3.x)` |  |
| 8423 | `test_pep277` |  | `x86 Tiger (2.7|3.x)` |  |
| 8429 | `test_subprocess` | `hung` |  | found on x86 FreeBSD 7.2 3.1 `r84451` |
| 8431 |  | `hung` | `(ARM|.* debian parallel)` |  |
| 8432 | `test_subprocess` |  | `.* (2.7|3.x)` | on 2.7: FreeBSD 7.2, FreeBSD, alpha Debian, ... |
| 8445 | `test_ttk_guionly` |  | `.* (Tiger|FreeBSD.*) (2.7|3.1|3.x)` |  |
| 8448 | `test_subprocess` | `$` | `sparc Debian 3.1` | found with `build #24, r84615` |
| 8458 | `test_cmd_line` |  | `.* Tiger (3.x|3.1)` |  |
| 8589 | `test_warnings` | `$` | `PPC Tiger 3.x` |  |
| 8845 | `test_sqlite` |  | `(PPC Leopard|PPC Tiger|sparc Debian) 3.x` |  |
| 9295 | `test_(file|file2k|bsddb3)` | `(something crashed|hung)` | `x86 XP-[45] (2.6|2.7)` |  |
| 9772 | `test_pep277` | `$` | `AMD64 debian parallel (2.7|3.x)` |  |
| 9773 | `test_tarfile` | `$` | `AMD64 debian parallel (2.7|3.1|3.x)` |  |
| 9774 | `test_smtpnet` | `$` | `AMD64 debian parallel (2.7|3.1|3.x)` |  |
| 5930 | `test_multiprocessing` |  | `(x86 FreeBSD 7.2|ARMv4 Debian) 3.1` |  |
| 9592 | `test_multiprocessing` | `$` | `x86 XP-5 3.1` | found on XP-5 3.1 `r83994` (build 581) |
| 8428 | `test_multiprocessing` |  | `(PPC Leopard|x86 FreeBSD 7.2) (2.7|3.x)` | see also: 5930, 9572, 9592|
| 8428 | `test_multiprocessing` |  | `sparc solaris10 gcc (2.7|3.x)` |  |
| 8428 | `test_multiprocessing` |  | `x86 (XP-4 3.x|Windows7 3.1)` |  |
| 9931 | `test_ttk_guionly` | `hung` | `x86 XP-5 3.x` |  |
| 10337 | `test_math` |  | `NetBSD 5 i386 3.[x1]` |  |
| 10337 | `test_cmath` |  | `NetBSD 5 i386 3.[x1]` |  |
| 10338 | `test_lib2to3` |  | `x86 debian parallel 3.x` |  |

Other known failures:

| **Reason** | **Test** | **Message** | **Builder** | **Comment** |
|:-----------|:---------|:------------|:------------|:------------|
| outdated | `test_(curses|gdb)` | `$` | `ia64 Ubuntu 2.7` | old failures `r82747`, now fixed |

<a href='Hidden comment: 
# not failing, still opened (2010-09-11)
#8449: test_dbm|test_dbm_ndbm::ia64 Ubuntu 3.1
'></a>