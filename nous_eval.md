|                                         Model                                          |AGIEval|GPT4All|TruthfulQA|Bigbench|Average|
|----------------------------------------------------------------------------------------|------:|------:|---------:|-------:|------:|
|[occiglot-7b-de-en-instruct](https://huggingface.co/occiglot/occiglot-7b-de-en-instruct)|   34.1|  69.15|     49.38|   39.06|  47.92|

### AGIEval
|             Task             |Version| Metric |Value|   |Stderr|
|------------------------------|------:|--------|----:|---|-----:|
|agieval_aqua_rat              |      0|acc     |22.05|±  |  2.61|
|                              |       |acc_norm|22.05|±  |  2.61|
|agieval_logiqa_en             |      0|acc     |31.34|±  |  1.82|
|                              |       |acc_norm|33.95|±  |  1.86|
|agieval_lsat_ar               |      0|acc     |21.30|±  |  2.71|
|                              |       |acc_norm|20.00|±  |  2.64|
|agieval_lsat_lr               |      0|acc     |37.06|±  |  2.14|
|                              |       |acc_norm|36.27|±  |  2.13|
|agieval_lsat_rc               |      0|acc     |49.07|±  |  3.05|
|                              |       |acc_norm|43.87|±  |  3.03|
|agieval_sat_en                |      0|acc     |58.74|±  |  3.44|
|                              |       |acc_norm|54.37|±  |  3.48|
|agieval_sat_en_without_passage|      0|acc     |40.29|±  |  3.43|
|                              |       |acc_norm|35.92|±  |  3.35|
|agieval_sat_math              |      0|acc     |31.82|±  |  3.15|
|                              |       |acc_norm|26.36|±  |  2.98|

Average: 34.1%

### GPT4All
|    Task     |Version| Metric |Value|   |Stderr|
|-------------|------:|--------|----:|---|-----:|
|arc_challenge|      0|acc     |47.95|±  |  1.46|
|             |       |acc_norm|50.51|±  |  1.46|
|arc_easy     |      0|acc     |78.28|±  |  0.85|
|             |       |acc_norm|74.20|±  |  0.90|
|boolq        |      1|acc     |85.66|±  |  0.61|
|hellaswag    |      0|acc     |59.50|±  |  0.49|
|             |       |acc_norm|77.74|±  |  0.42|
|openbookqa   |      0|acc     |32.00|±  |  2.09|
|             |       |acc_norm|44.00|±  |  2.22|
|piqa         |      0|acc     |79.27|±  |  0.95|
|             |       |acc_norm|80.58|±  |  0.92|
|winogrande   |      0|acc     |71.35|±  |  1.27|

Average: 69.15%

### TruthfulQA
|    Task     |Version|Metric|Value|   |Stderr|
|-------------|------:|------|----:|---|-----:|
|truthfulqa_mc|      1|mc1   |32.80|±  |  1.64|
|             |       |mc2   |49.38|±  |  1.51|

Average: 49.38%

### Bigbench
|                      Task                      |Version|       Metric        |Value|   |Stderr|
|------------------------------------------------|------:|---------------------|----:|---|-----:|
|bigbench_causal_judgement                       |      0|multiple_choice_grade|57.37|±  |  3.60|
|bigbench_date_understanding                     |      0|multiple_choice_grade|65.31|±  |  2.48|
|bigbench_disambiguation_qa                      |      0|multiple_choice_grade|46.90|±  |  3.11|
|bigbench_geometric_shapes                       |      0|multiple_choice_grade|30.08|±  |  2.42|
|                                                |       |exact_str_match      | 0.00|±  |  0.00|
|bigbench_logical_deduction_five_objects         |      0|multiple_choice_grade|24.60|±  |  1.93|
|bigbench_logical_deduction_seven_objects        |      0|multiple_choice_grade|17.00|±  |  1.42|
|bigbench_logical_deduction_three_objects        |      0|multiple_choice_grade|41.67|±  |  2.85|
|bigbench_movie_recommendation                   |      0|multiple_choice_grade|38.00|±  |  2.17|
|bigbench_navigate                               |      0|multiple_choice_grade|50.00|±  |  1.58|
|bigbench_reasoning_about_colored_objects        |      0|multiple_choice_grade|55.35|±  |  1.11|
|bigbench_ruin_names                             |      0|multiple_choice_grade|34.38|±  |  2.25|
|bigbench_salient_translation_error_detection    |      0|multiple_choice_grade|24.95|±  |  1.37|
|bigbench_snarks                                 |      0|multiple_choice_grade|61.33|±  |  3.63|
|bigbench_sports_understanding                   |      0|multiple_choice_grade|50.00|±  |  1.59|
|bigbench_temporal_sequences                     |      0|multiple_choice_grade|27.10|±  |  1.41|
|bigbench_tracking_shuffled_objects_five_objects |      0|multiple_choice_grade|21.84|±  |  1.17|
|bigbench_tracking_shuffled_objects_seven_objects|      0|multiple_choice_grade|15.60|±  |  0.87|
|bigbench_tracking_shuffled_objects_three_objects|      0|multiple_choice_grade|41.67|±  |  2.85|

Average: 39.06%

Average score: 47.92%

Elapsed time: 03:24:55
