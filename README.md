# hp-wmi fix: HP 245 14 inch G10 Notebook PC

Fixes noisy hp-wmi warnings on systems where HPWMI thermal profile query (0x4c)
and legacy fan speed max control are not supported by BIOS.

See the patch file in this repo. Intended for upstream submission to
platform-driver-x86@vger.kernel.org.
