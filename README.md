# rebuttal_tables

|              | VG_Relation | VG_Attribution | COCO_Order | Flickr30k_Order | Avg. |
| ------------ | ----------- | -------------- | ---------- | --------------- | ---- |
| Chance Level | 50          | 50             | 20         | 20              | -    |
| VLM Baseline |             |                |            |                 |      |
| CLIP         | 51          | 55             | 50         | 62              | 54.5 |
| BLIP         | 57          | 83             | 37         | 44              | 55.3 |
| X-VLM        | 65          | 89             | 35         | 56              | 61.3 |
| LVLM         |             |                |            |                 |      |
| BLIP2        | 45          | 96             | 21         | 45              | 51.8 |
| InstructBLIP | 73          | 83             | 31         | 44              | 57.8 |
| LA-V2        | 60          | 70             | 47         | 55              | 58.0 |
| LLaVA        | 42          | 47             | 60         | 31              | 45.0 |
| MiniGPT-4    | 63          | 63             | 42         | 27              | 48.8 |
| mPLUG-Owl    | 37          | 64             | 11         | 9               | 30.3 |
| Otter        | 5           | 45             | 12         | 16              | 19.5 |
| VPGTrans     | 47          | 69             | 33         | 20              | 42.3 |



|                                | BLIP2     | InstructBLIP | LA-V2 | LLaVA | MiniGPT-4 | mPLUG-Owl | Otter |
| ------------------------------ | --------- | ------------ | ----- | ----- | --------- | --------- | ----- |
| baseline (prompt in the paper) | *24.05*   | **24.4**     | 19.17 | 18.17 | 16.37     | 20.37     | 14.47 |
| mean (80 prompts)              | **26.52** | *24.30*      | 18.34 | 17.47 | 13.8      | 18.16     | 13.78 |
| std (80 prompts)               | 3.28      | 2.47         | 1.35  | 1.38  | 2.31      | 2.74      | 0.73  |



|                  | BLIP2   | InstructBLIP | LA-V2 | LLaVA | MiniGPT-4 | mPLUG-Owl | Otter |
| ---------------- | ------- | ------------ | ----- | ----- | --------- | --------- | ----- |
| Mean (10 rounds) | *23.87* | **24.40**    | 21.87 | 18.64 | 16.86     | 14.47     | 15.92 |
| Std (10 rounds)  | 0.01    | 0.01         | 0.20  | 0.30  | 0.46      | 0.02      | 0.42  |



|             | BLIP2 | InstructBLIP | LA-V2 | LLaVA | MiniGPT-4 | mPLUG-Owl | Otter |
| ----------- | ----- | ------------ | ----- | ----- | --------- | --------- | ----- |
| Single-turn | 72    | 80           | 72    | 58    | 56        | 48        | 60    |
| Multi-turn  | 74    | 80           | 76    | 74    | 66        | 80        | 68    |



| Model Name             | BLIP2 | InstructBLIP | LA-V2 | LLaVA | MiniGPT-4 | mPLUG-Owl | Otter | VPGTrans |
| ---------------------- | ----- | ------------ | ----- | ----- | --------- | --------- | ----- | -------- |
| Average Score          | 0.771 | 0.879        | 0.846 | 0.794 | 0.500     | 0.345     | 0.514 | 0.451    |
| Previous Average Score | 0.758 | 0.900        | 0.835 | 0.768 | 0.481     | 0.324     | 0.523 | 0.462    |



| Paper (634)  |            | Web (1770)   |            | Latest (2750) |            |
| ------------ | ---------- | ------------ | ---------- | ------------- | ---------- |
| Model Name   | Elo rating | Model Name   | Elo rating | Model Name    | Elo rating |
| mPLUG-Owl    | 1027.0     | LA-V2        | 1023       | LA-V2         | 1038.74    |
| MiniGPT-4    | 1021.3     | LLaVA        | 1019.9     | MiniGPT-4     | 1009.87    |
| Otter        | 1013.2     | VPGTrans     | 1012.1     | LLaVA         | 1002.76    |
| LA-V2        | 1010.2     | MiniGPT-4    | 1011.9     | VPGTrans      | 999.63     |
| LLaVA        | 1009.7     | InstructBLIP | 999.5      | InstructBLIP  | 995.45     |
| InstructBLIP | 1003.7     | mPLUG-Owl    | 996.3      | mPLUG-Owl     | 985.60     |
| VPGTrans     | 974.3      | Otter        | 981.5      | Otter         | 972.11     |
| BLIP2        | 949.4      | BLIP2        | 955.8      | BLIP2         | 948.8      |



| Task Type  | BLIP2 | InstructBLIP | LA-V2 | LLaVA | MiniGPT-4 | mPLUG-Owl | Otter | VPGTrans |
| ---------- | ----- | ------------ | ----- | ----- | --------- | --------- | ----- | -------- |
| ImgCls     | 0.893 | 0.976        | 0.881 | 0.618 | 0.779     | 0.814     | 0.538 | 0.475    |
| OC         | 0.805 | 0.834        | 0.716 | 0.510 | 0.521     | 0.391     | 0.972 | 0.480    |
| MCI        | 0.925 | 1.000        | 0.803 | 0.720 | 0.846     | 0.326     | 0.628 | 0.598    |
| OCR        | 0.958 | 1.000        | 0.355 | 0.319 | 0.268     | 0.261     | 0.193 | 0.605    |
| KIE        | 0.681 | 0.738        | 0.611 | 0.502 | 0.333     | 0.150     | 0.498 | 0.627    |
| Captioning | 0.960 | 0.980        | 0.582 | 0.038 | 0.086     | 0.003     | 0.189 | 0.603    |



| Paper (634)  |            | Web (1770)   |            | Latest (2750) |            |
| ------------ | ---------- | ------------ | ---------- | ------------- | ---------- |
| Model Name   | Elo rating | Model Name   | Elo rating | Model Name    | Elo rating |
| mPLUG-Owl    | 1027.0     | LA-V2        | 1023       | LA-V2         | 1038.74    |
| MiniGPT-4    | 1021.3     | LLaVA        | 1019.9     | MiniGPT-4     | 1009.87    |
| Otter        | 1013.2     | VPGTrans     | 1012.1     | LLaVA         | 1002.76    |
| LA-V2        | 1010.2     | MiniGPT-4    | 1011.9     | VPGTrans      | 999.63     |
| LLaVA        | 1009.7     | InstructBLIP | 999.5      | InstructBLIP  | 995.45     |
| InstructBLIP | 1003.7     | mPLUG-Owl    | 996.3      | mPLUG-Owl     | 985.60     |
| VPGTrans     | 974.3      | Otter        | 981.5      | Otter         | 972.11     |
| BLIP2        | 949.4      | BLIP2        | 955.8      | BLIP2         | 948.8      |



```Python
# PyTorch-like pseudo code
prompt = "{prompt}"
prompt_token_ids = tokenizer(prompt)
option = "{option}"
option_token_ids = tokenizer(option)
token_ids = prompt_token_ids + option_token_ids

inputs = token_ids[:-1]
targets = token_ids[1:]
logits = llm(inputs) # [len(inputs), vocab_size]

# only keep continuation for the prompt
logits = logits[-len(option_token_ids):]
logprobs = F.log_softmax(logits)
logprobs_option = torch.gather(logprobs, 1, option_token_ids)

logprobs_option_sum = logprobs_option.sum()
# optionally perform normalization
logprobs_option_sum_normalized = logprobs_option_sum / len(option_token_ids)
```




