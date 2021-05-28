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


Status - 5/27/21 8PM

3bitComparator - MAIN ONE, WORKING ON Revanth
MirrorAdder - WORKING ON JC
AND - WORKING ON Vedant
2to1MUX - WORKING ON Vedant

3to1AND - NEEDS REVIEW

3bit_2to1MUX - DEPENDS ON 2TO1MUX
2sComplementer - DEPENDENT ON MIRROR ADDERS
Ab_Value_Detector - MAIN ONE, DEPENDS ON 3bitComparator and Abs_Detector
Abs_Detector - DEPNEDS ON 3bit_2to1MUX and 2sComplementer

NAND - DONE
NOR -DONE
OR - DONE
CMOS_Inv - DONE
3to1OR - DONE