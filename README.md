# LogixLibraries

Collections of UDIs, UDTs, and sample programs written in Studio 5000 v35.

Source edit protection is enabled, but the code is viewable (it may make sense to fully unlock it but I'm also learning Git, so bear with me).

With the exception of complementary FactoryTalk View files, this repository contains only .L5X (Logix XML) files.

The structured text language is generally used for add-on-instruction definitions for ease of portability between IEC 61131-3 platforms.

Type and instruction dependencies will be documented where possible.

Some add-on-instructions make use of unsigned (USINT/UINT/UDINT/ULINT) and 64-bit (ULINT/LINT) types, limiting their use to current-generation hardware (CompactLogix 5380, CompactLogix 5480, and ControlLogix 5580 families) and future releases. CompactLogix 5370, ControlLogix 5570 and earlier families are unfortunately artificially limited to signed types (SINT/INT/DINT/LINT), so instructions will need to be modified to accomodate where necessary.
