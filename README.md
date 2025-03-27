# How to Execute the codes

All code files(Task_1.ipynb, Task_2.ipynb, Task_3.ipynb) has to be executed in Google colab.

## Subtask-1 (Classification Task):

(i) Upload the dataset(target_4_December_release.zip) from this folder into Google colab and rename the dataset to **train.zip**.

(ii) Now run all the cells in **Task_1.ipynb** file and see the results.


## Subtask-2 (Narrative & Sub-narrative Classification):

(i) Upload the dataset(target_4_December_release.zip) and NARRATIVE-TAXONOMIES.pdf file from this folder into Google colab and rename the dataset to **train.zip**.

(ii) Now run all the cells in **Task_2.ipynb** file and see the results.


## Subtask-3 (Explanation Generation):

(i) Upload the dataset(target_4_December_release.zip) from this folder into Google colab and rename the dataset to **train.zip**.

(ii) Now run all the cells in **Task_3.ipynb** file and see the results.

## NOTE: 
### Update on Project and further implementations in Phase 3:

### Subtask-1:
- **Implementation Status:** Fully completed, including accuracy metrics, predictions, and visualizations.
- **Current Results:** Leaderboard position in the top 50.
- **Next Steps (Phase-3):** Enhance performance by refining the fine-tuned XLM-R model (e.g., adding layers).

### Subtask-2:
- **Implementation Status:**
  - ✅ **Completed:** Preprocessing, model training, and narrative predictions (achieved strong F1-scores)
  - ⏳ **Pending:** Sub-narrative handling due to dataset complexity and ambiguous labeling
- **Next Steps (Phase-3):** Resolve sub-narrative challenges and optimize the XLM-R architecture.

### Subtask-3:
- **Implementation Status:** End-to-end pipeline completed (preprocessing, model training, and evaluation)
- **Evaluation Metric:** Semantic similarity scores show decent performance across languages
- **Next Steps (Phase-3):** Improve similarity scores via T5/mT5/XLM-R fine-tuning or alternative models

---

### Key Focus for Phase-3
1. **Model Optimization:** Layer augmentation and hyperparameter tuning for XLM-R/T5
2. **Data Refinement:** Address sub-narrative labeling ambiguities in Subtask-2
3. **Metric Enhancement:** Boost semantic similarity scores for generative tasks
