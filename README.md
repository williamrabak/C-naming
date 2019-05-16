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
BackgroundWorker | bgw
BindingNavigator | bdn
BindingSource | bds
Button | btn
CheckBox | chk
CheckedListBox | ckl
ColorDialog	cld
ComboBox	cmb
ContextMenuStrip	cms
DataGridView	dgv
DataSet	dts
DateTimePicker	dtp
DirectoryEntry	dre
DirectorySearcher	drs
DomainUpDown	dud
ErrorProvider	err
EventLog	evl
FileSystemWatcher	fsw
FlowLayoutPanel	flp
FolderBrowserDialog	fbd
FontDialog	fnd
Form	frm
GroupBox	grp
HelpProvider	hlp
HScrollBar	hsc
ImageList	img
Label	lbl
LinkLabel	llb
ListBox	lst
ListView	lvw
MaskedTextBox	mtx
MenuStrip	mns
MessageQueue	msq
MonthCalendar	cdr
NotifyIcon	icn
NumericUpDown	nud
OpenFileDialog	ofd
PageSetupDialog	psd
Panel	pnl
PerformanceCounter	pfc
PictureBox	pic
PrintDialog	prd
PrintDocument	pdc
PrintPreviewControl	prv
PrintPreviewDialog	ppd
Process	prc
ProgressBar	prg
PropertyGrid	prg
RadioButton	rdo
RichTextBox	rtx
SaveFileDialog	sfd
SerialPort	spt
ServiceController	scl
SplitContainer	spl
Splitter	spl
StatusStrip	ssr
TabControl	tab
TableLayoutPanel	tlp
TextBox	txt
Timer	tmr
ToolStrip	tsr
ToolStripContainer	tsc
ToolTip	tip
TrackBar	trb
TreeView	tvw
VScrollBar	vsc
WebBrowser	wbs

