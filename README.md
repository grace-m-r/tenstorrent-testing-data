# Tenstorrent Testing Data
- This data is referenced and analysed in the following report: (doi: )
- The ML models were run as non-optimised out-of-the-box models. 
- TT results are obtained by running the models on six Tenstorrent Blackhole p150a cards. 
- CPU results are obtained by running the models on eight cores of an AMD EPYC 9124 16-Core processor. 
- GPU results are obtained by running the models on the NVIDIA H100. 

## `REPORT_MLPF_TT_CPU_results`
- Includes TT and CPU results. 
- These results are obtained by running the MLPF model using `float32` and without FlashAttention. 

## `REPORT_MLPF_TT_CPU_results_bfloat16`
- Includes TT and CPU results. 
- These results are obtained by running the MLPF model using `bfloat16` and without FlashAttention. 

## `REPORT_MLPF_TT_CPU_results_bfloat16_FA`
- Includes TT and CPU results. 
- These results are obtained by running the MLPF model using `bfloat16` and FlashAttention. 

## `REPORT_MLPF_TT_GPU_results`
- Includes TT and GPU results. 
- These results are obtained by running the MLPF model using `bfloat16` and FlashAttention. 

## `REPORT_AnomalyDetect_TT_results`
- Includes TT results. 
- These results are obtained by running the Anomaly Detection Model for CMS L1 Scouting. 

## `REPORT_AnomalyDetect_GPU_results`
- Includes GPU results. 
- These results are obtained by running the Anomaly Detection Model for CMS L1 Scouting. 
