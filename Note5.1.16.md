# Project 010_

### Working Directories
SUE/20Feb2015/OUTPUT/010_COMBnSORT

### FILES
010_COMBData.csv:     merged data after duplicate (by Number) deleted<br />
010_LofStimuli.csv:   levels of Stimuli after wrong data deleted<br />
010_Rdata.csv:        merged data without duplicates deleted

### Include the following Subjects
M03
M07
M11
M13
M19
M20
M22
O01
O08
O09
O10
O11
O12
O14
O15
O16
O17
O18
O20
O21
O23
O24
O25
O28
O29
O30
O31
O32
O33
O34
O35
O36
O38
O39
O40
O41
O42
O43
O44
O45
O46
O47
O48
O49
O50
O51
O53
O54
O56
P59
P58
Y03
Y09
Y10
Y11
Y12
Y16
Y17
Y21
Y22
Y23
Y32
Y36
Y39
Y40
Y42
Y44
Y45
Y46
Y53
Y58
Y59
Y60
Y61

### Folders that contain data
Kset: KS1_AOI2  KS2_AOI2 KS3_AOI2 KS4_AOI2<br />
Gset: GS1_AOI2  GS2_AOI2 GS3_AOI2 GS4_AOI2<br />
include all FixationDetails*

### Delete data that include 
sp in KSET<br />
validation,_face, _scale, 193_fixation.jpg in stimulus

### Sorting 
sort by Subject

### Add columns
SET: K1 K2 K3 K4 G1 G2 G3 G4 <br />
SETID: filled with K, G <br />
Emotion: filled with emotions traced from Stimulus <br />
Agegrp: Take Subject column, replace Y, M, P with Young and  O with Old

### Delete duplicate data based on Number
Duplicate titles:<br />
Trial<br />
Subject<br />
Color<br />
Stimulus<br />
Number

