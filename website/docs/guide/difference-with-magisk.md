profile imported: 5.4.254-qgki-ga1db71346260
<k> result: offsets imported successfully
profile imported: 5.4.254-qgki-ga1db71346260
<k> result: offsets imported successfully
payload.bin ready: /data/user/0/com.ghostlock.app/files/payload.bin
<k> extract: /data/user/0/com.ghostlock.app/files/payload.bin
error: input is not an Android boot image or arm64 Image
<k> extract exit code=2
<k> result: parse failed
payload.bin ready: /data/user/0/com.ghostlock.app/files/payload.bin
<k> extract: /data/user/0/com.ghostlock.app/files/payload.bin
error: failed to read payload metadata '/data/user/0/com.ghostlock.app/files/payload.bin': failed to open ZIP payload: payload.bin not found in ZIP archive
<k> extract exit code=2
<k> result: parse failed
payload.bin ready: /data/user/0/com.ghostlock.app/files/payload.bin
<k> extract: /data/user/0/com.ghostlock.app/files/payload.bin
error: input is not an Android boot image or arm64 Image
<k> extract exit code=2
<k> result: parse failed
boot.img ready: /data/user/0/com.ghostlock.app/files/boot.img
xbl_config.img ready: /data/user/0/com.ghostlock.app/files/xbl_config.img
uefi.img ready: /data/user/0/com.ghostlock.app/files/uefi.img
<k> extract: /data/user/0/com.ghostlock.app/files/boot.img
error: input is not an Android boot image or arm64 Image
<k> extract exit code=2
<k> result: parse failed
boot.img ready: /data/user/0/com.ghostlock.app/files/boot.img
xbl_config.img ready: /data/user/0/com.ghostlock.app/files/xbl_config.img
<k> extract: /data/user/0/com.ghostlock.app/files/boot.img
error: input is not an Android boot image or arm64 Image
<k> extract exit code=2
<k> result: parse failed
payload.bin ready: /data/user/0/com.ghostlock.app/files/payload.bin
<k> extract: /data/user/0/com.ghostlock.app/files/payload.bin
error: input is not an Android boot image or arm64 Image
<k> extract exit code=2
<k> result: parse failed
boot.img ready: /data/user/0/com.ghostlock.app/files/boot.img
<k> extract: /data/user/0/com.ghostlock.app/files/boot.img
error: input is not an Android boot image or arm64 Image
<k> extract exit code=2
<k> result: parse failed
==== start Shizuku/V20 ====
cpu pair: 4,5 · 2.40 GHz
<k> GhostLock 1.2+562 build 2026-10-07 00:29:14
<k> debug log: Download/ghostlock-debug-log/20261021-182423/ghostlock-shizuku-0.log
<k> debug dump dir: /storage/emulated/0/Download/ghostlock-debug-log/20261021-182423
<s> resolving profile
<s> profile resolved hasProfile=true blob=1892 invalid=0
<k> runtime profile written: profile.conf/profile.bin
<b> starting UserService
<s> checking Shizuku status
<s> status=READY
<b> binding UserService
<b> Shizuku UserService connected
<s> Shizuku ready: uid=2000 Seccomp=0
<s> kernel: 5.4.254-qgki-ga1db71346260
<b> starting native: /data/app/~~mGpoHZhae3pBLaF8N-DOow==/com.ghostlock.app-bFK_XPUtUj7Wmd7-j2g0vw==/lib/arm64/libghostlock.so
[*] kernel: 5.4.254-qgki-ga1db71346260
[+] resolved profile loaded: 5.4.254-qgki-ga1db71346260
[*] cpu pair: main=4 consumer=5
[*] runtime home=/data/local/tmp/ghostlock-app script=/data/local/tmp/ghostlock-app/.ghostlock_root.sh
[*] debug.execution.begin release=5.4.254-qgki-ga1db71346260
[*] debug.execution.recommended_cpus.main=4
[*] debug.execution.recommended_cpus.consumer=5
[*] debug.execution.selected_cpus.main=4
[*] debug.execution.selected_cpus.consumer=5
[*] debug.execution.heap.prepare_max_attempts=4
[*] debug.execution.heap.prepare_timeout_ms=240000
[*] debug.execution.heap.kernelsnitch_timeout_ms=60000
[*] debug.execution.race.route_wait_ms=1000
[*] debug.execution.race.setup_settle_us=50000
[*] debug.execution.race.state_poll_interval_us=1000
[*] debug.execution.stages.w1_attempts=15
[*] debug.execution.stages.w1_settle_us=100000
[*] debug.execution.stages.w1_scratch_repair_attempts=3
[*] debug.execution.stages.w2_attempts=15
[*] debug.execution.stages.w2_settle_us=100000
[*] debug.execution.stages.w3_chain_rounds=3
[*] debug.execution.stages.w3_attempts=6
[*] debug.execution.stages.w3_settle_us=50000
[*] debug.execution.routes.tcp_zerocopy.attempts=0
[*] debug.execution.routes.tcp_zerocopy.arm_sequence=0
[*] debug.execution.routes.tcp_zerocopy.post_receive_hold_iterations=0
[*] debug.execution.routes.select_stack.enter_delay_us=0
[*] debug.execution.routes.select_stack.timeout_us=0
[*] debug.execution.routes.select_stack.consumer_max_calls=1
[*] debug.execution.routes.select_stack.consumer_burst_calls=1
[*] debug.execution.handoff.pre_dispatch_settle_ms=2000
[*] debug.execution.handoff.module_poll_attempts=30
[*] debug.execution.handoff.module_poll_interval_ms=100
[*] debug.execution.handoff.enforce_poll_attempts=200
[*] debug.execution.handoff.enforce_poll_interval_ms=100
[*] debug.execution.end
[*] soc: qcom/other; kernel_phys_load=0xa8000000
[*] init_cred image=ffffffc082bfd588 alias=ffffff802abfd588
[*] root script written path=/data/local/tmp/ghostlock-app/.ghostlock_root.sh bytes=6186
[*] iomem cache: no usable dump, keeping the built-in geometry
[+] startup context pid=26829 uid=2000 euid=2000 gid=2000 egid=2000 boot_ms=78093788 attr=u:r:shell:s0 enforce=1
[+] startup limits pid=26829 NoNewPrivs=0 Seccomp=0 Seccomp_filters=?
[+] build config pid=26829 label=ghostlock_oplus slide=pselect main=pselect
[+] p0 profile pid=26829 phys_offset=0000000080000000 kernel_phys_load=00000000a8000000 delta=0000000028000000 slide_logger=ffffff802ab01e28 bootid_data=ffffff802adc6819 init_task=ffffff802ac43400 root_tg=ffffff802ad58ac0 sysctl_bootid=ffffff802adc6819
[*] p0 kernel_phys_load=00000000a8000000 delta=0000000028000000
[*] main thread running on cpu=4
[*] [T+0ms] exploit start
[*] [T+5ms] pre-W1 drain
[*] W1: SELinux attempt 1/1
[*] === W1: SELinux === target=0xffffff802adaad88 mode=1 leaf=0
[*] [T+209ms]   heap spray start
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +100ms
[*] [spray] finding futex collisions... +219ms
[*] [spray] early collision screen 7/7 at 40%
[*] [spray] futex collisions found +806ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3327ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 1/4 +3396ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +81ms
[*] [spray] finding futex collisions... +192ms
[*] [spray] early collision screen 12/7 at 31%
[*] [spray] futex collisions found +705ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3185ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 2/4 +6668ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +97ms
[*] [spray] finding futex collisions... +211ms
[*] [spray] early collision screen 7/7 at 31%
[*] [spray] futex collisions found +735ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3157ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 3/4 +9928ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +98ms
[*] [spray] finding futex collisions... +210ms
[*] [spray] early collision screen 9/7 at 31%
[*] [spray] futex collisions found +684ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +2940ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 4/4 +12969ms
[-]   heap spray failed
[-] W1: SELinux attempt 1 route failed; backing off
<b> native exited code=1
[-] Write 1 failed
<k> result: exploit failed (exit code=1)
exit code=1
==== start Shizuku/V20 ====
cpu pair: 4,5 · 2.40 GHz
<k> GhostLock 1.2+562 build 2026-10-07 00:29:14
<k> debug log: Download/ghostlock-debug-log/20261021-182450/ghostlock-shizuku-1.log
<k> debug dump dir: /storage/emulated/0/Download/ghostlock-debug-log/20261021-182450
<s> resolving profile
<s> profile resolved hasProfile=true blob=1892 invalid=0
<k> runtime profile written: profile.conf/profile.bin
<b> starting UserService
<s> checking Shizuku status
<s> status=READY
<b> binding UserService
<b> Shizuku UserService connected
<b> Shizuku UserService connected
<s> error: another GhostLock process is already running
<s> Shizuku ready: uid=2000 Seccomp=0
<s> kernel: 5.4.254-qgki-ga1db71346260
<b> starting native: /data/app/~~mGpoHZhae3pBLaF8N-DOow==/com.ghostlock.app-bFK_XPUtUj7Wmd7-j2g0vw==/lib/arm64/libghostlock.so
[*] kernel: 5.4.254-qgki-ga1db71346260
[+] resolved profile loaded: 5.4.254-qgki-ga1db71346260
[*] cpu pair: main=4 consumer=5
[*] runtime home=/data/local/tmp/ghostlock-app script=/data/local/tmp/ghostlock-app/.ghostlock_root.sh
[*] debug.execution.begin release=5.4.254-qgki-ga1db71346260
[*] debug.execution.recommended_cpus.main=4
[*] debug.execution.recommended_cpus.consumer=5
[*] debug.execution.selected_cpus.main=4
[*] debug.execution.selected_cpus.consumer=5
[*] debug.execution.heap.prepare_max_attempts=4
[*] debug.execution.heap.prepare_timeout_ms=240000
[*] debug.execution.heap.kernelsnitch_timeout_ms=60000
[*] debug.execution.race.route_wait_ms=1000
[*] debug.execution.race.setup_settle_us=50000
[*] debug.execution.race.state_poll_interval_us=1000
[*] debug.execution.stages.w1_attempts=15
[*] debug.execution.stages.w1_settle_us=100000
[*] debug.execution.stages.w1_scratch_repair_attempts=3
[*] debug.execution.stages.w2_attempts=15
[*] debug.execution.stages.w2_settle_us=100000
[*] debug.execution.stages.w3_chain_rounds=3
[*] debug.execution.stages.w3_attempts=6
[*] debug.execution.stages.w3_settle_us=50000
[*] debug.execution.routes.tcp_zerocopy.attempts=0
[*] debug.execution.routes.tcp_zerocopy.arm_sequence=0
[*] debug.execution.routes.tcp_zerocopy.post_receive_hold_iterations=0
[*] debug.execution.routes.select_stack.enter_delay_us=0
[*] debug.execution.routes.select_stack.timeout_us=0
[*] debug.execution.routes.select_stack.consumer_max_calls=1
[*] debug.execution.routes.select_stack.consumer_burst_calls=1
[*] debug.execution.handoff.pre_dispatch_settle_ms=2000
[*] debug.execution.handoff.module_poll_attempts=30
[*] debug.execution.handoff.module_poll_interval_ms=100
[*] debug.execution.handoff.enforce_poll_attempts=200
[*] debug.execution.handoff.enforce_poll_interval_ms=100
[*] debug.execution.end
[*] soc: qcom/other; kernel_phys_load=0xa8000000
[*] init_cred image=ffffffc082bfd588 alias=ffffff802abfd588
[*] root script written path=/data/local/tmp/ghostlock-app/.ghostlock_root.sh bytes=6186
[*] iomem cache: no usable dump, keeping the built-in geometry
[+] startup context pid=8806 uid=2000 euid=2000 gid=2000 egid=2000 boot_ms=78119692 attr=u:r:shell:s0 enforce=1
[+] startup limits pid=8806 NoNewPrivs=0 Seccomp=0 Seccomp_filters=?
[+] build config pid=8806 label=ghostlock_oplus slide=pselect main=pselect
[+] p0 profile pid=8806 phys_offset=0000000080000000 kernel_phys_load=00000000a8000000 delta=0000000028000000 slide_logger=ffffff802ab01e28 bootid_data=ffffff802adc6819 init_task=ffffff802ac43400 root_tg=ffffff802ad58ac0 sysctl_bootid=ffffff802adc6819
[*] p0 kernel_phys_load=00000000a8000000 delta=0000000028000000
[*] main thread running on cpu=4
[*] [T+0ms] exploit start
[*] [T+2ms] pre-W1 drain
[*] W1: SELinux attempt 1/1
[*] === W1: SELinux === target=0xffffff802adaad88 mode=1 leaf=0
[*] [T+239ms]   heap spray start
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +116ms
[*] [spray] finding futex collisions... +240ms
[*] [spray] early collision screen 8/7 at 31%
[*] [spray] futex collisions found +708ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3373ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 1/4 +3517ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +137ms
[*] [spray] finding futex collisions... +245ms
[*] [spray] early collision screen 7/7 at 44%
[*] [spray] futex collisions found +803ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3051ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 2/4 +6705ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +115ms
[*] [spray] finding futex collisions... +213ms
[*] [spray] early collision screen 8/7 at 31%
[*] [spray] futex collisions found +699ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3385ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 3/4 +10186ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +114ms
[*] [spray] finding futex collisions... +244ms
[*] [spray] early collision screen 12/7 at 31%
[*] [spray] futex collisions found +717ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +2999ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 4/4 +13276ms
[-]   heap spray failed
[-] W1: SELinux attempt 1 route failed; backing off
<b> native exited code=1
[-] Write 1 failed
<k> result: exploit failed (exit code=1)
exit code=1
==== start Shizuku/V20 ====
cpu pair: 4,5 · 2.40 GHz
<k> GhostLock 1.2+562 build 2026-10-07 00:29:14
<k> debug log: Download/ghostlock-debug-log/20261021-182524/ghostlock-shizuku-2.log
<k> debug dump dir: /storage/emulated/0/Download/ghostlock-debug-log/20261021-182524
<s> resolving profile
<s> profile resolved hasProfile=true blob=1892 invalid=0
<k> runtime profile written: profile.conf/profile.bin
<b> starting UserService
<s> checking Shizuku status
<s> status=READY
<b> binding UserService
<b> Shizuku UserService connected
<b> Shizuku UserService connected
<s> error: another GhostLock process is already running
<b> Shizuku UserService connected
<s> error: another GhostLock process is already running
<s> Shizuku ready: uid=2000 Seccomp=0
<k> result: exploit failed (exit code=1)
exit code=1
<s> kernel: 5.4.254-qgki-ga1db71346260
<b> starting native: /data/app/~~mGpoHZhae3pBLaF8N-DOow==/com.ghostlock.app-bFK_XPUtUj7Wmd7-j2g0vw==/lib/arm64/libghostlock.so
[*] kernel: 5.4.254-qgki-ga1db71346260
[+] resolved profile loaded: 5.4.254-qgki-ga1db71346260
[*] cpu pair: main=4 consumer=5
[*] runtime home=/data/local/tmp/ghostlock-app script=/data/local/tmp/ghostlock-app/.ghostlock_root.sh
[*] debug.execution.begin release=5.4.254-qgki-ga1db71346260
[*] debug.execution.recommended_cpus.main=4
[*] debug.execution.recommended_cpus.consumer=5
[*] debug.execution.selected_cpus.main=4
[*] debug.execution.selected_cpus.consumer=5
[*] debug.execution.heap.prepare_max_attempts=4
[*] debug.execution.heap.prepare_timeout_ms=240000
[*] debug.execution.heap.kernelsnitch_timeout_ms=60000
[*] debug.execution.race.route_wait_ms=1000
[*] debug.execution.race.setup_settle_us=50000
[*] debug.execution.race.state_poll_interval_us=1000
[*] debug.execution.stages.w1_attempts=15
[*] debug.execution.stages.w1_settle_us=100000
[*] debug.execution.stages.w1_scratch_repair_attempts=3
[*] debug.execution.stages.w2_attempts=15
[*] debug.execution.stages.w2_settle_us=100000
[*] debug.execution.stages.w3_chain_rounds=3
[*] debug.execution.stages.w3_attempts=6
[*] debug.execution.stages.w3_settle_us=50000
[*] debug.execution.routes.tcp_zerocopy.attempts=0
[*] debug.execution.routes.tcp_zerocopy.arm_sequence=0
[*] debug.execution.routes.tcp_zerocopy.post_receive_hold_iterations=0
[*] debug.execution.routes.select_stack.enter_delay_us=0
[*] debug.execution.routes.select_stack.timeout_us=0
[*] debug.execution.routes.select_stack.consumer_max_calls=1
[*] debug.execution.routes.select_stack.consumer_burst_calls=1
[*] debug.execution.handoff.pre_dispatch_settle_ms=2000
[*] debug.execution.handoff.module_poll_attempts=30
[*] debug.execution.handoff.module_poll_interval_ms=100
[*] debug.execution.handoff.enforce_poll_attempts=200
[*] debug.execution.handoff.enforce_poll_interval_ms=100
[*] debug.execution.end
[*] soc: qcom/other; kernel_phys_load=0xa8000000
[*] init_cred image=ffffffc082bfd588 alias=ffffff802abfd588
[*] root script written path=/data/local/tmp/ghostlock-app/.ghostlock_root.sh bytes=6186
[*] iomem cache: no usable dump, keeping the built-in geometry
[+] startup context pid=21205 uid=2000 euid=2000 gid=2000 egid=2000 boot_ms=78154721 attr=u:r:shell:s0 enforce=1
[+] startup limits pid=21205 NoNewPrivs=0 Seccomp=0 Seccomp_filters=?
[+] build config pid=21205 label=ghostlock_oplus slide=pselect main=pselect
[+] p0 profile pid=21205 phys_offset=0000000080000000 kernel_phys_load=00000000a8000000 delta=0000000028000000 slide_logger=ffffff802ab01e28 bootid_data=ffffff802adc6819 init_task=ffffff802ac43400 root_tg=ffffff802ad58ac0 sysctl_bootid=ffffff802adc6819
[*] p0 kernel_phys_load=00000000a8000000 delta=0000000028000000
[*] main thread running on cpu=4
[*] [T+0ms] exploit start
[*] [T+6ms] pre-W1 drain
[*] W1: SELinux attempt 1/1
[*] === W1: SELinux === target=0xffffff802adaad88 mode=1 leaf=0
[*] [T+190ms]   heap spray start
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +104ms
[*] [spray] finding futex collisions... +215ms
[*] [spray] early collision screen 10/7 at 31%
[*] [spray] futex collisions found +696ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3066ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 1/4 +3140ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +89ms
[*] [spray] finding futex collisions... +196ms
[*] [spray] early collision screen 10/7 at 31%
[*] [spray] futex collisions found +743ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3101ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 2/4 +6404ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +103ms
[*] [spray] finding futex collisions... +219ms
[*] [spray] early collision screen 9/7 at 31%
[*] [spray] futex collisions found +695ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3030ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 3/4 +9545ms
[*] [spray] mm spray + kernelsnitch ready (cpu=8) +100ms
[*] [spray] finding futex collisions... +217ms
[*] [spray] early collision screen 7/7 at 39%
[*] [spray] futex collisions found +796ms
[*] [spray] mm_struct leaked=0xffffffffffffffff +3352ms
[-] KernelSnitch mm_struct leak failed
[-] prepare_kernel_page retry 4/4 +13071ms
[-]   heap spray failed
[-] W1: SELinux attempt 1 route failed; backing off
<b> native exited code=1
[-] Write 1 failed
Difference with Magisk

Although KernelSU and Magisk modules have many similarities, there are inevitably some differences due to their completely different implementation mechanisms. If you want your module to work on both Magisk and KernelSU, it's essential to understand these differences.

## Similarities

- Module file format: Both use the ZIP format to organize modules, and the module format is practically the same.
- Module installation directory: Both are located at `/data/adb/modules`.
- Systemless: Both support modifying `/system` in a systemless way through modules.
- post-fs-data.sh: Execution time and semantics are exactly the same.
- service.sh: Execution time and semantics are exactly the same.
- system.prop: Completely the same.
- sepolicy.rule: Completely the same.
- BusyBox: Scripts are run in BusyBox with "Standalone Mode" enabled in both cases.

## Differences

Before understanding the differences, it's important to know how to identify whether your module is running in KernelSU or Magisk. You can use the environment variable `KSU` to differentiate it in all places where you can run module scripts (`customize.sh`, `post-fs-data.sh`, `service.sh`). In KernelSU, this environment variable will be set to `true`.

Here are some differences:

- KernelSU modules cannot be installed in Recovery mode.
- KernelSU modules don't have built-in support for Zygisk, but you can use Zygisk modules through [ZygiskNext](https://github.com/Dr-TSNG/ZygiskNext).
- **Module mounting architecture**: KernelSU uses a [metamodule system](metamodule.md) where mounting is delegated to pluggable metamodules (e.g., `meta-overlayfs`), while Magisk has mounting built into its core. KernelSU requires installing a metamodule to enable module mounting.
- The method for replacing or deleting files in KernelSU modules is completely different from Magisk. KernelSU doesn't support the `.replace` method. Instead, you need to create a same-named file with `mknod filename c 0 0` to delete the corresponding file.
- The directories for BusyBox are different. The built-in BusyBox in KernelSU is located at `/data/adb/ksu/bin/busybox`, while in Magisk it is at `/data/adb/magisk/busybox`. **Note that this is an internal behavior of KernelSU and may change in the future!**
- KernelSU doesn't support `.replace` files, but it supports the `REMOVE` and `REPLACE` variables to remove or replace files and folders.
- KernelSU adds the `boot-completed` stage to run scripts after the boot process is finished.
- KernelSU adds the `post-mount` stage to run scripts after module mounting is complete.
