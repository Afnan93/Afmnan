This project extends a baseline [DeepGCN](https://github.com/lightaime/deep_gcns_torch) model by introducing an attention mechanism via a custom `GATLayer`.
With adds an attention mechanism utilizing a specific GATLayer to an existing DeepGCN architecture. 
By Using  attention coefficients, the attention module improves feature representation and is applied immediately after the first graph convolution layer. 
It maintains consistency and benchmarking, all other model parts are kept from the original DeepGCN implementation, such as the dynamic graph construction, residual blocks, and final fusion.
Part semantic segmentation task on PartNet dataset.
