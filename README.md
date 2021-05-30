## How to download this project
1. `cd ~/ee115c`
2. `git clone https://github.com/vedantmathur/115C-Absolute-Value-Detector`
3. Verify all files are present
4. Append your `~/ee115c/cds.lib` with

`DEFINE tb_project ~/ee115c/115C-Absolute-Value-Detector/tb_project`

`DEFINE dt_project ~/ee115c/115C-Absolute-Value-Detector/main_project`

5. `cd ~/ee115c`
6. `tcsh`
7. `virtuoso &`
8. Suffer.


Status - 5/30/21 12PM

3bitComparator - WORKING ON Revanth

MirrorAdder - WORKING ON JC

2sComplementer - DEPENDENT ON MIRROR ADDERS

Abs_Detector - DEPENDENT ON 2sComplementer

Ab_Value_Detector - MAIN ONE, DEPENDENT ON Abs_Detector

Done: 

NAND

NOR

OR

AND

CMOS_Inv

3to1OR

3to1AND

2to1MUX

3bit_2to1MUX