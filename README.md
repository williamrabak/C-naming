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

public void SayHello(string name) { ... };

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

