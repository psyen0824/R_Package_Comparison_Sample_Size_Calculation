# R_sample_size_awesome
collect R_calculating sample size package

<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=big5">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 15">
<meta name=Originator content="Microsoft Word 15">
<link rel=File-List href="GEE%20Sample%20Size_20200525_PSY.files/filelist.xml">
<link rel=Edit-Time-Data
href="GEE%20Sample%20Size_20200525_PSY.files/editdata.mso">
<!--[if !mso]>
<style>
v\:* {behavior:url(#default#VML);}
o\:* {behavior:url(#default#VML);}
w\:* {behavior:url(#default#VML);}
.shape {behavior:url(#default#VML);}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>Yeh Kerwin</o:Author>
  <o:Template>Normal</o:Template>
  <o:LastAuthor>chiaming</o:LastAuthor>
  <o:Revision>2</o:Revision>
  <o:TotalTime>2</o:TotalTime>
  <o:Created>2020-06-02T01:43:00Z</o:Created>
  <o:LastSaved>2020-06-02T01:43:00Z</o:LastSaved>
  <o:Pages>1</o:Pages>
  <o:Words>718</o:Words>
  <o:Characters>4093</o:Characters>
  <o:Lines>34</o:Lines>
  <o:Paragraphs>9</o:Paragraphs>
  <o:CharactersWithSpaces>4802</o:CharactersWithSpaces>
  <o:Version>16.00</o:Version>
 </o:DocumentProperties>
 <o:OfficeDocumentSettings>
  <o:RelyOnVML/>
  <o:AllowPNG/>
 </o:OfficeDocumentSettings>
</xml><![endif]-->
<link rel=themeData href="GEE%20Sample%20Size_20200525_PSY.files/themedata.thmx">
<link rel=colorSchemeMapping
href="GEE%20Sample%20Size_20200525_PSY.files/colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:SpellingState>Clean</w:SpellingState>
  <w:GrammarState>Clean</w:GrammarState>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:PunctuationKerning/>
  <w:DrawingGridHorizontalSpacing>6 點</w:DrawingGridHorizontalSpacing>
  <w:DisplayHorizontalDrawingGridEvery>0</w:DisplayHorizontalDrawingGridEvery>
  <w:DisplayVerticalDrawingGridEvery>2</w:DisplayVerticalDrawingGridEvery>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>EN-US</w:LidThemeOther>
  <w:LidThemeAsian>ZH-TW</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:SpaceForUL/>
   <w:BalanceSingleByteDoubleByteWidth/>
   <w:DoNotLeaveBackslashAlone/>
   <w:ULTrailSpace/>
   <w:DoNotExpandShiftReturn/>
   <w:AdjustLineHeightInTable/>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:DontGrowAutofit/>
   <w:SplitPgBreakAndParaMark/>
   <w:EnableOpenTypeKerning/>
   <w:DontFlipMirrorIndents/>
   <w:OverrideTableStyleHps/>
   <w:UseFELayout/>
  </w:Compatibility>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="&#45;-"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="false"
  DefSemiHidden="false" DefQFormat="false" DefPriority="99"
  LatentStyleCount="375">
  <w:LsdException Locked="false" Priority="0" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 9"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="header"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footer"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index heading"/>
  <w:LsdException Locked="false" Priority="35" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of figures"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope return"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="line number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="page number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of authorities"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="macro"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="toa heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 5"/>
  <w:LsdException Locked="false" Priority="10" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Closing"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Signature"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="true"
   UnhideWhenUsed="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Message Header"/>
  <w:LsdException Locked="false" Priority="11" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Salutation"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Date"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Note Heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Block Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="FollowedHyperlink"/>
  <w:LsdException Locked="false" Priority="22" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Document Map"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Plain Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="E-mail Signature"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Top of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Bottom of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal (Web)"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Acronym"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Cite"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Code"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Definition"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Keyboard"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Preformatted"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Sample"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Typewriter"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Variable"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Table"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation subject"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="No List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Contemporary"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Elegant"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Professional"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Balloon Text"/>
  <w:LsdException Locked="false" Priority="39" Name="Table Grid"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Theme"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" QFormat="true"
   Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" QFormat="true"
   Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" QFormat="true"
   Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" QFormat="true"
   Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" QFormat="true"
   Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" QFormat="true"
   Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" SemiHidden="true"
   UnhideWhenUsed="true" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="TOC Heading"/>
  <w:LsdException Locked="false" Priority="41" Name="Plain Table 1"/>
  <w:LsdException Locked="false" Priority="42" Name="Plain Table 2"/>
  <w:LsdException Locked="false" Priority="43" Name="Plain Table 3"/>
  <w:LsdException Locked="false" Priority="44" Name="Plain Table 4"/>
  <w:LsdException Locked="false" Priority="45" Name="Plain Table 5"/>
  <w:LsdException Locked="false" Priority="40" Name="Grid Table Light"/>
  <w:LsdException Locked="false" Priority="46" Name="Grid Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="Grid Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="Grid Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="46" Name="List Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="List Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="List Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Mention"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Smart Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hashtag"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Unresolved Mention"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;
	mso-font-charset:2;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:0 268435456 0 0 -2147483648 0;}
@font-face
	{font-family:新細明體;
	panose-1:2 2 5 0 0 0 0 0 0 0;
	mso-font-alt:PMingLiU;
	mso-font-charset:136;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-1610611969 684719354 22 0 1048577 0;}
@font-face
	{font-family:細明體;
	panose-1:2 2 5 9 0 0 0 0 0 0;
	mso-font-alt:MingLiU;
	mso-font-charset:136;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:-1610611969 684719354 22 0 1048577 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-536869121 1107305727 33554432 0 415 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}
@font-face
	{font-family:"Lucida Console";
	panose-1:2 11 6 9 4 5 4 2 2 4;
	mso-font-charset:0;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:-2147482993 6144 0 0 31 0;}
@font-face
	{font-family:標楷體;
	panose-1:3 0 5 9 0 0 0 0 0 0;
	mso-font-charset:136;
	mso-generic-font-family:script;
	mso-font-pitch:fixed;
	mso-font-signature:3 135135232 22 0 1048577 0;}
@font-face
	{font-family:"\@標楷體";
	mso-font-charset:136;
	mso-generic-font-family:script;
	mso-font-pitch:fixed;
	mso-font-signature:3 135135232 22 0 1048577 0;}
@font-face
	{font-family:"\@細明體";
	panose-1:2 1 6 9 0 1 1 1 1 1;
	mso-font-charset:136;
	mso-generic-font-family:modern;
	mso-font-pitch:fixed;
	mso-font-signature:-1610611969 684719354 22 0 1048577 0;}
@font-face
	{font-family:"\@新細明體";
	panose-1:2 1 6 1 0 1 1 1 1 1;
	mso-font-charset:136;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:-1610611969 684719354 22 0 1048577 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:none;
	font-size:12.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
p.MsoCommentText, li.MsoCommentText, div.MsoCommentText
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-link:"註解文字 字元";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:none;
	font-size:12.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
p.MsoHeader, li.MsoHeader, div.MsoHeader
	{mso-style-priority:99;
	mso-style-link:"頁首 字元";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:none;
	tab-stops:center 207.65pt right 415.3pt;
	layout-grid-mode:char;
	font-size:10.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
p.MsoFooter, li.MsoFooter, div.MsoFooter
	{mso-style-priority:99;
	mso-style-link:"頁尾 字元";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:none;
	tab-stops:center 207.65pt right 415.3pt;
	layout-grid-mode:char;
	font-size:10.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
span.MsoCommentReference
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-ansi-font-size:9.0pt;
	mso-bidi-font-size:9.0pt;}
a:link, span.MsoHyperlink
	{mso-style-priority:99;
	color:blue;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{mso-style-noshow:yes;
	mso-style-priority:99;
	color:#954F72;
	mso-themecolor:followedhyperlink;
	text-decoration:underline;
	text-underline:single;}
p
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"新細明體",serif;
	mso-bidi-font-family:新細明體;}
code
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-ansi-font-size:12.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:細明體;
	mso-ascii-font-family:細明體;
	mso-fareast-font-family:細明體;
	mso-hansi-font-family:細明體;
	mso-bidi-font-family:細明體;}
p.MsoCommentSubject, li.MsoCommentSubject, div.MsoCommentSubject
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-parent:註解文字;
	mso-style-link:"註解主旨 字元";
	mso-style-next:註解文字;
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:none;
	font-size:12.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;
	font-weight:bold;}
p.MsoAcetate, li.MsoAcetate, div.MsoAcetate
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-link:"註解方塊文字 字元";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:none;
	font-size:9.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	mso-font-kerning:1.0pt;}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:24.0pt;
	margin-bottom:.0001pt;
	mso-para-margin-top:0cm;
	mso-para-margin-right:0cm;
	mso-para-margin-bottom:0cm;
	mso-para-margin-left:2.0gd;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:none;
	font-size:12.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
span.a
	{mso-style-name:"頁首 字元";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:頁首;
	mso-ansi-font-size:10.0pt;
	mso-bidi-font-size:10.0pt;}
span.a0
	{mso-style-name:"頁尾 字元";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:頁尾;
	mso-ansi-font-size:10.0pt;
	mso-bidi-font-size:10.0pt;}
span.a1
	{mso-style-name:"註解文字 字元";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:註解文字;}
span.a2
	{mso-style-name:"註解主旨 字元";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-parent:"註解文字 字元";
	mso-style-link:註解主旨;
	font-weight:bold;}
span.a3
	{mso-style-name:"註解方塊文字 字元";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:註解方塊文字;
	mso-ansi-font-size:9.0pt;
	mso-bidi-font-size:9.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:新細明體;
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;}
span.SpellE
	{mso-style-name:"";
	mso-spl-e:yes;}
span.GramE
	{mso-style-name:"";
	mso-gram-e:yes;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	font-family:"Calibri",sans-serif;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;}
 /* Page Definitions */
 @page
	{mso-page-border-surround-header:no;
	mso-page-border-surround-footer:no;
	mso-footnote-separator:url("GEE%20Sample%20Size_20200525_PSY.files/header.htm") fs;
	mso-footnote-continuation-separator:url("GEE%20Sample%20Size_20200525_PSY.files/header.htm") fcs;
	mso-endnote-separator:url("GEE%20Sample%20Size_20200525_PSY.files/header.htm") es;
	mso-endnote-continuation-separator:url("GEE%20Sample%20Size_20200525_PSY.files/header.htm") ecs;}
@page WordSection1
	{size:841.9pt 595.3pt;
	mso-page-orientation:landscape;
	margin:36.0pt 36.0pt 36.0pt 36.0pt;
	mso-header-margin:42.55pt;
	mso-footer-margin:49.6pt;
	mso-paper-source:0;
	layout-grid:18.0pt;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 @list l0
	{mso-list-id:206796026;
	mso-list-type:hybrid;
	mso-list-template-ids:-1705237802 -1845215170 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l0:level1
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:48.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level2
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level3
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:96.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level4
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:120.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level5
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:144.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level6
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:168.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level7
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:192.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level8
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:216.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l0:level9
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:240.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l1
	{mso-list-id:1025446106;
	mso-list-type:hybrid;
	mso-list-template-ids:1719940336 67698703 67698713 67698715 67698703 67698713 67698715 67698703 67698713 67698715;}
@list l1:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:24.0pt;
	text-indent:-24.0pt;}
@list l1:level2
	{mso-level-number-format:ideograph-traditional;
	mso-level-text:%2、;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:48.0pt;
	text-indent:-24.0pt;}
@list l1:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:72.0pt;
	text-indent:-24.0pt;}
@list l1:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:96.0pt;
	text-indent:-24.0pt;}
@list l1:level5
	{mso-level-number-format:ideograph-traditional;
	mso-level-text:%5、;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:120.0pt;
	text-indent:-24.0pt;}
@list l1:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:144.0pt;
	text-indent:-24.0pt;}
@list l1:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:168.0pt;
	text-indent:-24.0pt;}
@list l1:level8
	{mso-level-number-format:ideograph-traditional;
	mso-level-text:%8、;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:192.0pt;
	text-indent:-24.0pt;}
@list l1:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:216.0pt;
	text-indent:-24.0pt;}
@list l2
	{mso-list-id:1618754536;
	mso-list-type:hybrid;
	mso-list-template-ids:1209699686 67698703 67698713 67698715 67698703 67698713 67698715 67698703 67698713 67698715;}
@list l2:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:24.0pt;
	text-indent:-24.0pt;}
@list l2:level2
	{mso-level-number-format:ideograph-traditional;
	mso-level-text:%2、;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:48.0pt;
	text-indent:-24.0pt;}
@list l2:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:72.0pt;
	text-indent:-24.0pt;}
@list l2:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:96.0pt;
	text-indent:-24.0pt;}
@list l2:level5
	{mso-level-number-format:ideograph-traditional;
	mso-level-text:%5、;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:120.0pt;
	text-indent:-24.0pt;}
@list l2:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:144.0pt;
	text-indent:-24.0pt;}
@list l2:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:168.0pt;
	text-indent:-24.0pt;}
@list l2:level8
	{mso-level-number-format:ideograph-traditional;
	mso-level-text:%8、;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:192.0pt;
	text-indent:-24.0pt;}
@list l2:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:216.0pt;
	text-indent:-24.0pt;}
@list l3
	{mso-list-id:2055497585;
	mso-list-type:hybrid;
	mso-list-template-ids:-106800474 -1845215170 67698691 67698693 67698689 67698691 67698693 67698689 67698691 67698693;}
@list l3:level1
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:48.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level2
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level3
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:96.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level4
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:120.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level5
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:144.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level6
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:168.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level7
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:192.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level8
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:216.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
@list l3:level9
	{mso-level-number-format:bullet;
	mso-level-text:;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:240.0pt;
	text-indent:-24.0pt;
	font-family:Wingdings;}
ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:表格內文;
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-parent:"";
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-para-margin:0cm;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
table.MsoTableGrid
	{mso-style-name:表格格線;
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-priority:39;
	mso-style-unhide:no;
	border:solid windowtext 1.0pt;
	mso-border-alt:solid windowtext .5pt;
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-border-insideh:.5pt solid windowtext;
	mso-border-insidev:.5pt solid windowtext;
	mso-para-margin:0cm;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	mso-bidi-font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-font-kerning:1.0pt;}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="2049"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=ZH-TW link=blue vlink="#954F72" style='tab-interval:24.0pt;
text-justify-trim:punctuation'>

<div class=WordSection1 style='layout-grid:18.0pt'>

<p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>

<div align=center>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0cm 5.4pt 0cm 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'>Package<o:p></o:p></span></p>
  </td>
  <td width=138 valign=top style='width:103.85pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'>Function<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'>Description<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1'>
  <td width=138 rowspan=14 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US style='font-size:18.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>pwr</span></span><span lang=EN-US style='font-family:
  "Arial",sans-serif'><o:p></o:p></span></p>
  </td>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=GramE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>cohen.ES(</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Conventional effects size<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>ES.<span
  class=GramE>h</span></span></span><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>(</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Effect size calculation for
  proportions<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=GramE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>ES.w</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>1(P0, P1)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Effect size calculation in the
  chi-squared test for goodness of fit<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=GramE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>ES.w</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>2(P)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Effect size calculation in the
  chi-squared test for association<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>pwr.2p.test()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculation for two proportions
  (same sample sizes)<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:6'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>pwr.2p2n.test()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculation for two proportions
  (different sample sizes)<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:7'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.anova</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>.test</span></span><span lang=EN-US style='font-size:
  10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for balanced
  one-way analysis of variance tests<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:8'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.chisq</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>.test</span></span><span lang=EN-US style='font-size:
  10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>power calculations for chi-squared
  tests<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:9'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=GramE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.f</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>2.test()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for the general
  linear model<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:10'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.norm</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>.test</span></span><span lang=EN-US style='font-size:
  10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for the mean of a
  normal distribution (known variance)<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:11'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.p.<span
  class=GramE>test</span></span></span><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>(</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for proportion
  tests (one sample)<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:12'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.r.<span
  class=GramE>test</span></span></span><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>(</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for correlation
  test<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:13'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span class=SpellE><span lang=EN-US style='font-size:10.0pt;
  mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>pwr.t.<span
  class=GramE>test</span></span></span><span class=GramE><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'>(</span></span><span
  lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:
  "Arial",sans-serif'>)<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for t-tests of
  means (one sample, two samples and paired samples)<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:14'>
  <td width=138 valign=top style='width:103.85pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>pwr.t2n.test()<o:p></o:p></span></p>
  </td>
  <td width=611 valign=top style='width:458.5pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Power calculations for two samples
  (different sizes) t-tests of means<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:15'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US style='font-family:"Arial",sans-serif'>samplesizeCMH</span></span><span
  lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Calculates the power and sample size
  for Cochran-Mantel-<span class=SpellE>Haenszel</span> tests. There are also
  several helper functions for working with probability, odds, relative risk,
  and odds ratio values.</span><span lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:16'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US>simr</span></span><span lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US>Power Analysis for <span class=SpellE>Generalised</span>
  Linear Mixed Models by Simulation</span><span lang=EN-US style='font-size:
  10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:17'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US>longpower</span></span><span lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span style='font-family:"新細明體",serif;mso-ascii-font-family:
  Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
  mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'>目前僅可計算</span><span
  lang=EN-US>GLMM</span><span style='font-family:"新細明體",serif;mso-ascii-font-family:
  Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
  mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'>的</span><span
  lang=EN-US>sample size (two level model)</span><span lang=EN-US
  style='font-size:10.0pt;mso-bidi-font-size:11.0pt;font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:18'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US style='font-family:"Arial",sans-serif'>samplesize</span></span><span
  lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Sample Size Calculation for Various
  t-Tests and Wilcoxon-Test<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:19'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US
  style='font-family:"Arial",sans-serif'><o:p>&nbsp;</o:p></span></p>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US style='font-family:"Arial",sans-serif'>clusterPower</span></span><span
  lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Calculate power for cluster randomized
  trials (CRTs) that compare two means, two proportions, or two counts using closed-form
  solutions. In addition, calculate power for cluster randomized crossover
  trials using Monte Carlo methods. For more information, see Reich et al.
  (2012)</span><span lang=EN-US style='font-family:"Arial",sans-serif'><o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:20'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span lang=EN-US>NPHMC</span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Sample Size Calculation for the
  Proportional Hazards Mixture Cure Model<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:21;mso-yfti-lastrow:yes'>
  <td width=138 valign=top style='width:103.8pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal align=center style='text-align:center'><span class=SpellE><span
  lang=EN-US>binomSamSize</span></span></p>
  </td>
  <td width=750 colspan=2 valign=top style='width:562.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt'>
  <p class=MsoNormal><span lang=EN-US style='font-size:10.0pt;mso-bidi-font-size:
  11.0pt;font-family:"Arial",sans-serif'>Confidence Intervals and Sample Size
  Determination for a Binomial Proportion under Simple Random Sampling and
  Pooled Sampling<o:p></o:p></span></p>
  </td>
 </tr>
</table>

</div>

<p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal style='margin-left:24.0pt;text-indent:-24.0pt'><span
lang=EN-US><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>1.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span class=SpellE><u><span lang=EN-US
style='font-family:"Times New Roman",serif;background:lime;mso-highlight:lime'>longpower</span></u></span><u><span
lang=EN-US style='font-family:"Times New Roman",serif'> </span></u><span
lang=EN-US style='font-family:"Times New Roman",serif'>package</span><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>當中</span><span class=SpellE><u><span
lang=EN-US style='font-family:"Times New Roman",serif'>lmmpower</span></u></span><u><span
lang=EN-US style='font-family:"Times New Roman",serif'> function</span></u><u><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>可計算</span></u><u><span lang=EN-US
style='font-family:"Times New Roman",serif'>GEE sample size</span></u><u><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>－</span></u><u><span lang=EN-US
style='font-family:"Times New Roman",serif'>two level model</span></u><span
lang=EN-US style='font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US><a
href="https://cran.r-project.org/web/packages/longpower/longpower.pdf"><span
style='font-family:"Times New Roman",serif'>https://cran.r-project.org/web/packages/longpower/longpower.pdf</span></a></span><span
lang=EN-US style='font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>2.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-family:"Times New Roman",serif'>GEE
Calculator Shiny App – Paired Data (Twins)<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US><a href="https://djprice.shinyapps.io/gee_calculator/"><span
style='font-family:"Times New Roman",serif'>https://djprice.shinyapps.io/gee_calculator/</span></a></span><span
lang=EN-US style='font-family:"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US style='font-family:"Times New Roman",serif'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>3.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-family:"Times New Roman",serif'>2018_Li_Sample
size Determination for GEE Analyses of <u>Stepped Wedge Cluster Randomized
Trial</u> (</span><span style='font-family:"新細明體",serif;mso-ascii-font-family:
"Times New Roman";mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:
"Times New Roman";mso-bidi-font-family:"Times New Roman"'>有提供</span><span
lang=EN-US style='font-family:"Times New Roman",serif'>R Code</span><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>及</span><span lang=EN-US
style='font-family:"Times New Roman",serif'>Supplementary)<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6461045/"><span
style='font-family:"Times New Roman",serif'>https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6461045/</span></a></span><span
class=MsoHyperlink><span lang=EN-US style='font-family:"Times New Roman",serif'><o:p></o:p></span></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Times New Roman",serif'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>4.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span class=SpellE><span lang=EN-US
style='font-family:"Times New Roman",serif'>Simr</span></span><span lang=EN-US
style='font-family:"Times New Roman",serif'> package</span><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>的</span><span class=SpellE><span
lang=EN-US style='font-family:"Times New Roman",serif'>powercurve</span></span><span
lang=EN-US style='font-family:"Times New Roman",serif'> function </span><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>可計算</span><span lang=EN-US
style='font-family:"Times New Roman",serif'>Generalized Linear Mixed Models </span><span
style='font-family:"新細明體",serif;mso-ascii-font-family:"Times New Roman";
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:"Times New Roman";
mso-bidi-font-family:"Times New Roman"'>中</span><span style='font-family:"Times New Roman",serif'>
<span lang=EN-US>sample size <o:p></o:p></span></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US><a href="https://cran.r-project.org/web/packages/simr/simr.pdf">https://cran.r-project.org/web/packages/simr/simr.pdf</a></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US style='font-family:"Times New Roman",serif'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>5.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US>Package <span class=SpellE><span
style='background:lightgrey;mso-highlight:lightgrey'>samplesize</span></span> <a
href="https://cran.r-project.org/web/packages/samplesize/samplesize.pdf">(<span
lang=EN-US style='font-family:"新細明體",serif;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'><span
lang=EN-US>有提供</span></span>Example Code<span lang=EN-US style='font-family:
"新細明體",serif;mso-ascii-font-family:Calibri;mso-ascii-theme-font:minor-latin;
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:
minor-latin'><span lang=EN-US>與</span></span><span lang=EN-US><span lang=EN-US>
</span></span><span lang=EN-US style='font-family:"新細明體",serif;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'><span
lang=EN-US>參數說明</span></span>)</a></span><span lang=EN-US style='font-family:
"Times New Roman",serif'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l0 level1 lfo3'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings'><span style='mso-list:Ignore'>w<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Abstract</span><span style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'>：</span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體;color:#0070C0'>Computes sample size for Student's t-test and for the
Wilcoxon-<span class=SpellE>MannWhitney</span> test for categorical data</span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>. The t-test function allows paired and unpaired (balanced / unbalanced)
designs as well as homogeneous and heterogeneous variances. The Wilcoxon
function allows for ties.<o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd'><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>6.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US>Package <span class=SpellE><span
style='background:lightgrey;mso-highlight:lightgrey'>pwr</span></span><a
href="https://cran.r-project.org/web/packages/pwr/pwr.pdf">(<span lang=EN-US
style='font-family:"新細明體",serif;mso-ascii-font-family:Calibri;mso-ascii-theme-font:
minor-latin;mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:Calibri;
mso-hansi-theme-font:minor-latin'><span lang=EN-US>有</span></span><span
lang=EN-US style='font-family:"新細明體",serif;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'><span
lang=EN-US>提供</span></span>Example Code<span lang=EN-US style='font-family:
"新細明體",serif;mso-ascii-font-family:Calibri;mso-ascii-theme-font:minor-latin;
mso-fareast-theme-font:minor-fareast;mso-hansi-font-family:Calibri;mso-hansi-theme-font:
minor-latin'><span lang=EN-US>與</span></span><span lang=EN-US><span lang=EN-US>
</span></span><span lang=EN-US style='font-family:"新細明體",serif;mso-ascii-font-family:
Calibri;mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'><span
lang=EN-US>參數說明</span></span>)</a></span><span lang=EN-US style='font-family:
"Times New Roman",serif;mso-fareast-font-family:標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd'><span
lang=EN-US><a
href="https://cran.r-project.org/web/packages/pwr/vignettes/pwr-vignette.html"><span
style='font-family:"Times New Roman",serif;mso-fareast-font-family:標楷體'>(</span><span
lang=EN-US style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'><span
lang=EN-US>來源</span></span><span style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'>2)</span></a></span><span lang=EN-US
style='font-family:"Times New Roman",serif;mso-fareast-font-family:標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l0 level1 lfo3'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings'><span style='mso-list:Ignore'>w<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Abstract</span><span style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'>：</span><span
lang=EN-US style='font-size:10.0pt;font-family:"Arial",sans-serif;color:black'>The
basic idea of calculating power or sample size with functions in the <span
class=SpellE>pwr</span> package is to&nbsp;<em><span style='font-family:"Arial",sans-serif'>leave
out</span></em>&nbsp;the argument that you want to calculate. If you want to
calculate power, then leave the&nbsp;</span><code><span lang=EN-US
style='font-size:9.0pt;font-family:"Lucida Console";color:black'>power</span></code><span
lang=EN-US style='font-size:10.0pt;font-family:"Arial",sans-serif;color:black'>&nbsp;argument
out of the function. If you want to calculate sample size, leave&nbsp;</span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Lucida Console";color:black'>n</span></code><span
lang=EN-US style='font-size:10.0pt;font-family:"Arial",sans-serif;color:black'>&nbsp;out
of the function. Whatever parameter you want to calculate is determined from
the <span class=SpellE><span class=GramE>others.You</span></span> select a
function based on the statistical test you plan to use to analyze your data. If
you plan to use a two-sample t-test to compare two means, you would use
the&nbsp;</span><span class=SpellE><code><span lang=EN-US style='font-size:
9.0pt;font-family:"Lucida Console";color:black'>pwr.t.test</span></code></span><span
lang=EN-US style='font-size:10.0pt;font-family:"Arial",sans-serif;color:black'>&nbsp;function
for estimating sample size or power. All functions for power and sample size
analysis in the <span class=SpellE>pwr</span> package begin with&nbsp;</span><code><span
lang=EN-US style='font-size:9.0pt;font-family:"Lucida Console";color:black'>pwr</span></code><span
lang=EN-US style='font-size:10.0pt;font-family:"Arial",sans-serif;color:black'>.
Functions are available for the following statistical tests:</span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l0 level1 lfo3'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings'><span style='mso-list:Ignore'>w<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><span
style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";mso-hansi-font-family:
"Times New Roman";mso-bidi-font-family:"Times New Roman"'>支援這些檢定的計算樣本數</span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>:<o:p></o:p></span></p>

<p class=MsoNormal align=center style='margin-left:24.0pt;text-align:center'><span
lang=EN-US style='mso-no-proof:yes'><v:shapetype id="_x0000_t75" coordsize="21600,21600"
 o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f"
 stroked="f">
 <v:stroke joinstyle="miter"/>
 <v:formulas>
  <v:f eqn="if lineDrawn pixelLineWidth 0"/>
  <v:f eqn="sum @0 1 0"/>
  <v:f eqn="sum 0 0 @1"/>
  <v:f eqn="prod @2 1 2"/>
  <v:f eqn="prod @3 21600 pixelWidth"/>
  <v:f eqn="prod @3 21600 pixelHeight"/>
  <v:f eqn="sum @0 0 1"/>
  <v:f eqn="prod @6 1 2"/>
  <v:f eqn="prod @7 21600 pixelWidth"/>
  <v:f eqn="sum @8 21600 0"/>
  <v:f eqn="prod @7 21600 pixelHeight"/>
  <v:f eqn="sum @10 21600 0"/>
 </v:formulas>
 <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>
 <o:lock v:ext="edit" aspectratio="t"/>
</v:shapetype><v:shape id="圖片_x0020_1" o:spid="_x0000_i1025" type="#_x0000_t75"
 style='width:388.5pt;height:171pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="GEE%20Sample%20Size_20200525_PSY.files/image001.png"
  o:title=""/>
</v:shape></span><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>7.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US>Package <span style='background:
lightgrey;mso-highlight:lightgrey'>NPHMC</span> <a
href="https://cran.r-project.org/web/packages/NPHMC/NPHMC.pdf">(Example Code<span
lang=EN-US style='font-family:"新細明體",serif;mso-ascii-font-family:Calibri;
mso-ascii-theme-font:minor-latin;mso-fareast-theme-font:minor-fareast;
mso-hansi-font-family:Calibri;mso-hansi-theme-font:minor-latin'><span
lang=EN-US>與參數說明</span></span>)</a></span><span lang=EN-US style='font-family:
"Times New Roman",serif;mso-fareast-font-family:標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l3 level1 lfo4'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings'><span style='mso-list:Ignore'>w<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Abstract</span><span style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'>：</span><span
lang=EN-US>calculating sample size of a survival trial with or without cure
fractions</span><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>8.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'>Package <span class=SpellE><span style='background:
lightgrey;mso-highlight:lightgrey'>samplesizeCMH</span></span> </span><span
lang=EN-US><a
href="https://cran.r-project.org/web/packages/samplesizeCMH/samplesizeCMH.pdf"><span
style='font-family:"Times New Roman",serif;mso-fareast-font-family:標楷體'>(Example
Code </span><span lang=EN-US style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'><span
lang=EN-US>與</span></span><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><span lang=EN-US> </span></span><span lang=EN-US
style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";mso-hansi-font-family:
"Times New Roman";mso-bidi-font-family:"Times New Roman"'><span lang=EN-US>參數說明</span></span><span
style='font-family:"Times New Roman",serif;mso-fareast-font-family:標楷體'>)</span></a></span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l3 level1 lfo4'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings'><span style='mso-list:Ignore'>w<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Abstract</span><span style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'>：</span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Sample Size Calculation for the Cochran-Mantel-<span class=SpellE>Haenszel</span>
Test<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-left:24.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l2 level1 lfo2'><![if !supportLists]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
"Times New Roman"'><span style='mso-list:Ignore'>9.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'>Package </span><span class=SpellE><span
lang=EN-US style='background:lightgrey;mso-highlight:lightgrey'>binomSamSize</span></span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'> </span><span lang=EN-US><a
href="https://cran.r-project.org/web/packages/binomSamSize/binomSamSize.pdf"><span
style='font-family:"Times New Roman",serif;mso-fareast-font-family:標楷體'>(Example
Code </span><span lang=EN-US style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'><span
lang=EN-US>與</span></span><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><span lang=EN-US> </span></span><span lang=EN-US
style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";mso-hansi-font-family:
"Times New Roman";mso-bidi-font-family:"Times New Roman"'><span lang=EN-US>參數說明</span></span><span
style='font-family:"Times New Roman",serif;mso-fareast-font-family:標楷體'>)</span></a></span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'><o:p></o:p></span></p>

<p class=MsoListParagraph style='margin-left:48.0pt;mso-para-margin-left:0gd;
text-indent:-24.0pt;mso-list:l3 level1 lfo4'><![if !supportLists]><span
lang=EN-US style='font-family:Wingdings;mso-fareast-font-family:Wingdings;
mso-bidi-font-family:Wingdings'><span style='mso-list:Ignore'>w<span
style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp; </span></span></span><![endif]><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Abstract</span><span style='font-family:標楷體;mso-ascii-font-family:"Times New Roman";
mso-hansi-font-family:"Times New Roman";mso-bidi-font-family:"Times New Roman"'>：</span><span
lang=EN-US style='font-family:"Times New Roman",serif;mso-fareast-font-family:
標楷體'>Confidence Intervals and Sample Size Determination for a Binomial
Proportion under Simple Random Sampling and Pooled Sampling<o:p></o:p></span></p>

<p class=MsoNormal><span lang=EN-US style='font-family:"Times New Roman",serif;
mso-fareast-font-family:標楷體'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>

