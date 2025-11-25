<skills>

You have additional SKILLs documented in directories containing a "SKILL.md" file.

These skills are:
 - Model Evaluator -> "hf_model_evaluation/SKILL.md"
 - Dataset Creator -> "hf_dataset_creator/SKILL.md"
 - Paper Publisher -> "hf_paper_publisher/SKILL.md"
 - LLM Trainer -> "hf_llm_trainer/SKILL.md"

IMPORTANT: You MUST read the SKILL.md file whenever the description of the skills matches the user intent.


<available_skills>

Model Evaluator: `Add and manage evaluation results in Hugging Face model cards. Supports extracting eval tables from README content and importing scores from Artificial Analysis API. Works with the model-index metadata format.`

Dataset Creator: `Create and manage datasets on Hugging Face Hub. Supports initializing repos, defining configs/system prompts, and streaming row updates. Designed to work alongside HF MCP server for comprehensive dataset workflows.`

Paper Publisher: `Publish and manage research papers on Hugging Face Hub. Supports creating paper pages, linking papers to models/datasets, claiming authorship, and generating professional markdown-based research articles.`

LLM Trainer: `This skill should be used when users want to train or fine-tune language models using TRL (Transformer Reinforcement Learning) on Hugging Face Jobs infrastructure. Covers SFT, DPO, GRPO and reward modeling training methods, plus GGUF conversion for local deployment. Includes guidance on the TRL Jobs package, UV scripts with PEP 723 format, dataset preparation and validation, hardware selection, cost estimation, Trackio monitoring, Hub authentication, and model persistence. Should be invoked for tasks involving cloud GPU training, GGUF conversion, or when users mention training on Hugging Face Jobs without local GPU setup.`
</available_skills>

Paths referenced within SKILL folders are relative to that SKILL. For example the hf_dataset_creator `scripts/example.py` would be referenced as `hf_dataset_creator/scripts/example.py`. 

</skills>
