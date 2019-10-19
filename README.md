# C# Coding Standards and Naming Conventions
### Terminology and Definitions for Naming Conventions:

**Camel Case** (camelCase): The first letter of the word is lower case and then each first letter of the part of the word is upper case;

**Pascal Case** (PascalCase): The first letter of the word is upper case and then each first letter of the part of the word is upper case;

**Underscore Prefix** (_underscore): The word begins with underscore char and for the rest of the word use camelCase rule;

## General Rules
1. Use Pascal Case for Class names:

Example:

```csharp
public class HelloWorld { ... };
```

2. Use Pascal Case for Method names:

Example:

```csharp
public void SayHello(string name) { ... };
```
3. Use Camel Case for variables and method parameters:

Example:

```csharp
int totalCount = 0;

void SayHello(string name)
{
     string fullMessage = "Hello " + name;
     //...
}
```

4. Avoid all upper case or all lower case names.

5. Do not use Hungarian notation.

6. Avoid abbreviations longer than 5 characters.

7. Avoid using abbreviations unless the full name is excessive:

Example:
```csharp
string addr;        //NOT GOOD
string address;     //GOOD
```

## Naming Conventions for C# Controls
In general, naming C# controls is made using **Camel Case** naming convention, where the prefix of the name is the abbreviation of the control type name.

Control Name | Prefix
------------ | ------
BackgroundWorker | _bgw_
BindingNavigator | _bdn_
BindingSource | _bds_
Button | _btn_
CheckBox | _chk_
CheckedListBox | _ckl_
ColorDialog | _cld_
ComboBox | _cbo_
ContextMenuStrip | _cms_
DataGridView | _dgv_
DataSet | _dts_
DateTimePicker | _dtp_
DirectoryEntry | _dre_
DirectorySearcher | _drs_
DomainUpDown | _dud_
ErrorProvider | _err_
EventLog | _evl_
FileSystemWatcher | _fsw_
FlowLayoutPanel | _flp_
FolderBrowserDialog | _fbd_
FontDialog | _fnd_
Form | _frm_
GroupBox | _grp_
HelpProvider | _hlp_
HScrollBar | _hsc_
ImageList | _img_
Label | _lbl_
LinkLabel | _llb_
ListBox | _lst_
ListView | _lvw_
MaskedTextBox | _mtx_
MenuStrip | _mns_
MessageQueue | _msq_
MonthCalendar | _cdr_
NotifyIcon | _icn_
NumericUpDown | _num_
OpenFileDialog | _ofd_
PageSetupDialog | _psd_
Panel | _pnl_
PerformanceCounter | _pfc_
PictureBox | _pic_
PrintDialog | _prd_
PrintDocument | _pdc_
PrintPreviewControl | _prv_
PrintPreviewDialog | _ppd_
Process | _prc_
ProgressBar | _prg_
PropertyGrid | _ppg_
RadioButton | _rdo_
RichTextBox | _rtx_
SaveFileDialog | _sfd_
SerialPort | _spt_
ServiceController | _scl_
SplitContainer | _spc_
Splitter | _spl_
StatusStrip | _ssr_
TabControl | _tab_
TableLayoutPanel | _tlp_
TextBox | _txt_
Timer | _tmr_
ToolStrip | _tsr_
ToolStripContainer | _tsc_
ToolTip | _tip_
TrackBar | _trb_
TreeView | _tvw_
VScrollBar | _vsc_
WebBrowser | _wbs_



Dec | Hex  | Char
----|------|------
0 | 0x00 | NUL (NULL)
1 | 0x01 | SOH (START OF HEADING)
2 | 0x02 | SOT (START OF TEXT)
3 | 0x03 | ETX (END OF TEXT)
4 | 0x04 | EOT (END OF TRANSMISSION)
5 | 0x05 | ENQ (ENQUIRY)
6 | 0x06 | ACK (ACKNOWLEDGE)
7 | 0x07 | BEL (BELL RING)
8 | 0x08 | BS (BACKSPACE)
9 | 0x09 | HT (HORIZONTAL TAB)
10 | 0x0A | LF (LINE FEED)
11 | 0x0B | VT (VERTICAL TAB)
12 | 0x0C | FF (FORM FEED)
13 | 0x0D | CR (CARRIAGE RETURN)
14 | 0x0E | SO (SHIFT OUT)
15 | 0x0F | SI (SHIFT IN)
16 | 0x10 | DLE (DATA LINK ESCAPE)
17 | 0x11 | DC1 (DEVICE CONTROL 1)
18 | 0x12 | DC2 (DEVICE CONTROL 2)
19 | 0x13 | DC3 (DEVICE CONTROL 3)
20 | 0x14 | DC4 (DEVICE CONTROL 4)
21 | 0x15 | NAK (NEGATIVE ACKNOWLEDGE)
22 | 0x16 | SYN (SYNCHRONOUS IDLE)
23 | 0x17 | ETB (END OF TRANSMIT BLOCK)
24 | 0x18 | CAN (CANCEL)
25 | 0x19 | EM (END OF MEDIUM)
26 | 0x1A | SUB (SUBSTITUTE)
27 | 0x1B | ESC (ESCAPE)
28 | 0x1C | FS (FILE SEPARATOR)
29 | 0x1D | GS (GROUP SEPARATOR)
30 | 0x1E | RS (RECORD SEPARATOR)
31 | 0x1F | US (UNIT SEPARATOR)
32 | 0x20 | SPACE
33 | 0x21 | !
34 | 0x22 |
35 | 0x23 |
36 | 0x24 |
37 | 0x25 |
38 | 0x26 |
39 | 0x27 |
40 | 0x28 |
41 | 0x29 |
42 | 0x2A |
43 | 0x2B |
44 | 0x2C |
45 | 0x2D |
46 | 0x2E |
47 | 0x2F |
48 | 0x30 |
49 | 0x31 |
50 | 0x32 |
51 | 0x33 |
52 | 0x34 |
53 | 0x35 |
54 | 0x36 |
55 | 0x37 |
56 | 0x38 |
57 | 0x39 |
58 | 0x3A |
59 | 0x3B |
60 | 0x3C |
61 | 0x3D |
62 | 0x3E |
63 | 0x3F |




