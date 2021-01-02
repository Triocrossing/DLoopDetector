DLoopDetector
=============

## Overview
See origin repository for more details [dorian3d/DLoopDetector](https://github.com/dorian3d/DLoopDetector)
Modified version of DLoopDetector for reading binary BRIEF voacbulary. 
More details refer to VINS-MONO relocalization.([Binary Vocabulary File](https://github.com/HKUST-Aerial-Robotics/VINS-Mono/tree/master/support_files))

Compare to original version 3 files are modified:
```
TemplatedVocabulary.h : loadBin(...) added and conversion to native BRIEF (unlike in VINS-MONO))
BinaryVocabulary.hpp
BinaryVocabulary.cpp : files copied from VINS-MONO for reading bin vocs
```

## Usage:

Put the file TemplatedVocabulary.h or copy the contents into the auto-installed DBoW2 (if this is the case).

