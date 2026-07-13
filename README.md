# Precise-Collaborative-Computing-Paradigms-for-Data-Intensive-Scientific-Discovery
Code for paper：Precise Collaborative Computing Paradigms for Data-Intensive Scientific Discovery
================================================================
## Environment:

GPU 0: NVIDIA GeForce RTX 3060 Ti
     Multi-Processor Count: 38
     Max Threads Per Multi-Processor: 1536
     Warp Size: 32
     Max Threads Per Block: 1024
     Compute Capability: 8.6
     Number of Multi-Processors: 38
     Number of CUDA Cores Per SM: 128
     Total Number of CUDA Cores: 4864

CPU: 12th Gen Intel(R) Core(TM) i9-12900
     Number of Physical Cores: 16
     Number of Logical Cores: 24

Visual Studio: 2022 (v143), MSC_VER: 1944
CUDA Version: 12.5
================================================================
## Dataset(input):

.\TransactionSets\chess.txt
.\TransactionSets\connect.txt
.\TransactionSets\mushroom.txt
.\TransactionSets\T10I4D100K.txt
.\TransactionSets\retail.txt
.\TransactionSets\accidents.txt
.\TransactionSets\pumsb_star.txt
.\TransactionSets\pumsb.txt
.\TransactionSets\T40I10D100K.txt
.\TransactionSets\kosarak.txt
================================================================
## The code text in the kernel.cu file:

    CString TransSet = _T("..\\TransactionSets\\chess.txt"); SupportThreshold = 0.95;
    //CString TransSet = _T("..\\TransactionSets\\connect.txt"); SupportThreshold = 0.965;
    //CString TransSet = _T("..\\TransactionSets\\mushroom.txt"); SupportThreshold = 0.52;
    //CString TransSet = _T("..\\TransactionSets\\T10I4D100K.txt"); SupportThreshold = 0.0225;
    //CString TransSet = _T("..\\TransactionSets\\retail.txt"); SupportThreshold = 0.00125;

    //CString TransSet = _T("..\\TransactionSets\\accidents.txt"); SupportThreshold = 0.5;
    //CString TransSet = _T("..\\TransactionSets\\pumsb_star.txt"); SupportThreshold = 0.275;
    //CString TransSet = _T("..\\TransactionSets\\pumsb.txt"); SupportThreshold = 0.8;
    //CString TransSet = _T("..\\TransactionSets\\T40I10D100K.txt"); SupportThreshold = 0.025;
    //CString TransSet = _T("..\\TransactionSets\\kosarak.txt"); SupportThreshold = 0.0024;
================================================================
## Results(output):

chess.txt-0.950000=Result
================================================================
## Opening:

xxx.sln
(Please switch to the "Release" mode for operation to achieve quick results.)
================================================================
## Citation:

If you use this code, please cite our paper:
Title: The title is still undecided.
DOI: Under submission, no DOI yet.
================================================================



