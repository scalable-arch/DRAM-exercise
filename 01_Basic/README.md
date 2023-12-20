![image](https://github.com/scalable-arch/DRAM-exercise/assets/62287136/8f13b5c7-091a-491e-bfdb-759d2f2c9844)# DRAM Basics

# Author

**Dongwhee Kim** 

- [```Google Scholar```](https://scholar.google.com/citations?user=8xzqA8YAAAAJ&hl=ko&oi=ao)
- [```ORCiD```](https://orcid.org/0009-0007-1673-1931?fbclid=PAAabkpwNHesKweJ6F2eGZDnFa2sch2211hf6ZY825YKuli5V7lcN7VIfT0CA)
- [```LinkedIn```](https://www.linkedin.com/in/dongwhee-kim-5753a8290)

# Objective
- Understand the DRAM Basics (organization, operation, timing parameters, refresh, rowhammer, etc)

# Overview
![DRAM](https://cdn.ttgtmedia.com/rms/onlineImages/storage_definition-DRAM.jpg)

# To do
- Watch the YouTube of **DRAM Basics**
- Read the DRAM **JEDEC Standards (SPEC Sheets)**
- Read and analyze the **related papers (Top-tier Conference/Journal)**

# Getting Started
  # 1_DRAM Basics (YouTube)
- 1. [```How does Computer Memory Work?```](https://www.youtube.com/watch?v=7J7X7aZvMXQ)
- 2. [```Memory Cell Arrays```](https://www.youtube.com/watch?v=I-9XWtdW_Co)
- 3. [```Read and Write Cycles```](https://www.youtube.com/watch?v=x3jGqOrXXc8)
- 4. [```Binary Decoders```](https://youtu.be/xPCDiEglo98)
- 5. [```Multiplexers and Demultiplexers```](https://youtu.be/jjRTFfZwPLM)
- 6. [```DIMM Organization```](https://youtu.be/Mhqi70OPW0o)
- 7. [```DRAM Organization```](https://www.youtube.com/watch?v=HWw-6SY6VBs&t=955s)
- 8. [```DRAM Timing Constraint```](https://www.youtube.com/watch?v=7STOekOQ_sM&t=830s)

# 2_Memory System
- [```PDF```](https://books.google.co.kr/books?id=SrP3aWed-esC&printsec=copyright&redir_esc=y#v=onepage&q&f=false)
- Chapter 7. Overview of DRAMs
- Chapter 8, 10. DRAM Device Organization & DRAM Memory System Organization
- Chapter 11, 12.3 Basic DRAM Memory-Access Protocol & Modern-Commodity DRAM Devices
- Chapter 13. DRAM Memory Controller
    
 # 3_JEDEC Standards
- To do: Organize DRAM Key Timing Parameters (**nCL (CAS Latency), tRCD, tRP**, tCCD, tRRD, tFAW, tWTR_S, tWTR_L)
  
 # 4_Related papers
- 1. [```[ISCA'12] SALP```](https://dl.acm.org/doi/abs/10.1145/2366231.2337202)
- 2. [```[HPCA'13] Tiered-Latency DRAM```](https://ieeexplore.ieee.org/abstract/document/6522354)
- 3. [```[ISCA'13] Reducing Memory Access Latency with Asymmetric DRAM Bank Organizations```](https://dl.acm.org/doi/abs/10.1145/2485922.2485955)
- 4. [```[HPCA'14] Improving DRAM performance by parallelizing refreshes with accesses```](https://ieeexplore.ieee.org/abstract/document/6835946)
- 5. [```[HPCA'15] Adaptive-Latency DRAM```](https://ieeexplore.ieee.org/abstract/document/7056057)
- 6. [```[ISCA'10] Rethinking DRAM design and organization for energy-constrained multi-cores```](https://dl.acm.org/doi/abs/10.1145/1815961.1815983)
- 7. [```[HPCA'16] LISA```](https://ieeexplore.ieee.org/abstract/document/7446095)
- 8. [```[ISCA'14] PARA```](https://dl.acm.org/doi/abs/10.1145/2678373.2665726) **Rowhammer Basics**
- 9. [```[SAFARI'23] Rowhammer Story```](https://safari.ethz.ch/architecture_seminar/fall2023/lib/exe/fetch.php?media=onur-comparchseminar-fall2023-lecture3-rowhammerstory-afterlecture.pptx)
- 10. [```[HPCA'18] ERUCA```](https://ieeexplore.ieee.org/abstract/document/8327046?casa_token=8BeiJlX4ybwAAAAA:a4fL6fx8xpQItC0CHO8VB89TLi1n6HIYxoT1FXHS4Xn1judk0ZhEJM20skjWH9a2pej-KXs5teY)
- 11. [```[HPCA'21] Blockhammer```](https://ieeexplore.ieee.org/abstract/document/9407238?casa_token=Zmq65LghxmYAAAAA:wCDqnjCYVgrI-SIrqCzB8LlOxJhV1HXt4hByLIl6Le0D88I36dR-Xd8RhMerK7cTxi4QJiJ2NZ8)
- 12. [```[ISCA'10] Rethinking DRAM Design and Organization for Energy-Constrained Multi-Cores```](https://dl.acm.org/doi/abs/10.1145/1815961.1815983?casa_token=j8EpgSzYHMoAAAAA:rtfV6ve36j_oTOz65twmYaAB3WFXjDLCqF0d18EF5X9o5-7gokLCfUSYjYiDhuxNiM-2iTDXCP9GLw)
- 13. [```[ISCA'14] Half-DRAM```](https://dl.acm.org/doi/abs/10.1145/2678373.2665724?casa_token=XiRuG_FZkcUAAAAA:ICwmbryZnLjA9eb2nROxyOc4FQLllO6VAhnq5b9-0nP9AZ19-NES_zOSCTvoNFjWTrhh1YW5_m99mA)
- 14. [```[ISCA'19] CROW```](https://dl.acm.org/doi/abs/10.1145/3307650.3322231?casa_token=s7jHsni4d2EAAAAA:BaJNPiptS36erKY9aBZygXbQBAnQfqneZ8NsvDlQuV0DT2dEufVuBSHBsti5oQqWGPwmSQTXP28dPw)
- 15. [```[ISCA'20] CLR-DRAM```](https://dl.acm.org/doi/abs/10.1109/ISCA45697.2020.00061)
- 16. [```[ISCA'23] A Research Retrospective on the AMD Exascale Computing Journey```](https://dl.acm.org/doi/abs/10.1145/3579371.3589349?casa_token=3tXkFLbf8fwAAAAA:tp1AnhkL56P7LABfd9wmy7BKd7ZnKtwJrLpEGPtnJH369bORZtLl4o0Tlpa3oAGL74cwTiPam4Gohw)
- 17. [```[ISCA'23] RowPress```](https://dl.acm.org/doi/abs/10.1145/3579371.3589063?casa_token=mmmSb24-Tv4AAAAA:PZjx3_FLVTFuofe69QBwDkRBnYXzkBr4qyRX3blBUa4KrOOPDhyxJbtNlworucdN41kqINMfIPVGfA)
- 18. [```[MICRO'10] Understanding the Energy Consumption of DRAM```](https://dl.acm.org/doi/abs/10.1109/MICRO.2010.42)
- 19. [```[MICRO'11] Loh-DRAM Cache```](https://dl.acm.org/doi/abs/10.1145/2155620.2155673?casa_token=RDkt2YlR00MAAAAA:NhLSJy4M0nvyUTU1mO5915MUf5yLMd16lDGYAJa0xnxzBajBw7X9fIzOKLA6AkV64EezSaOJYnehjg)
- 20. [```[MICRO'12] Alloy-Cache```](https://dl.acm.org/doi/abs/10.1109/MICRO.2012.30)
- 21. [```[MICRO'13] RowClone```](https://dl.acm.org/doi/abs/10.1145/2540708.2540725?casa_token=QxUlB-nwgkMAAAAA:63YO5bJ3w9iC6sz2yffiVxKMAQMyILJjlZWZRMWMW1ph2XjCuSHIXlIsNLSub_zQkzQxoK2LCPnJWQ)
- 22. [```[MICRO'17] Ambit```](https://dl.acm.org/doi/abs/10.1145/3123939.3124544)
- 23. [```[MICRO'20] FIGARO```](https://ieeexplore.ieee.org/abstract/document/9251865)
- 24. [```[MICRO'22] HIRA```](https://ieeexplore.ieee.org/abstract/document/9923850?casa_token=RWo-EihE49UAAAAA:b20nJDYcVsRLXeQNo9eDCJgHEiVbaTCTHx0TxwIvkzR7-XOAEptGSzdVAXVeXOS6wVTNlmUGeXA)
- 25. [```[SC'13] Exploring DRAM organization```](https://dl.acm.org/doi/abs/10.1145/2503210.2503215?casa_token=3763j-NWAuMAAAAA:dFw4Dw1bxdi7KkmbZpy0XOdvd4R1hvBkC90wL34giW_DCFdmkYNrs9OxHBbLEMc5c1XqmNJc_U_Yiw) 
- 26. [```[HPCA'24] Agile-DRAM```] **(Will be updated later!)**

# Other useful sites
- [```[SAFARI'23] Computer Architecture - Fall 2023```](https://safari.ethz.ch/architecture/fall2023/doku.php?id=schedule)

# Refresh basics

