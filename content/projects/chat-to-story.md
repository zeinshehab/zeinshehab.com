{
  "title": "ChatToStory",
  "date": "2024-12-12",
  "link": "https://github.com/RaedFidawi/ChatToStory",
  "image": "/img/chat_to_story.png",
  "description": "An end-to-end LLM pipeline that transforms conversations into narratives, combining large language models with a fine-tuned T5 for lightweight, task-specialized story generation. GPU workloads were automated on an HPC cluster using SLURM and Bash.",
  "tags": [
    "Machine Learning",
    "Natural Language Processing",
    "LLMs",
    "Hugging Face",
    "Transformers",
    "T5",
    "SLURM",
    "HPC",
    "Python",
    "Bash"
  ],
  "fact": "",
  "featured": true,
  "weight": 150
}

ChatToStory is an end-to-end pipeline for LLM-based story generation, developed as a team project for the Advanced Machine Learning course at AUB. The system converts conversational input into coherent narratives by combining large language models with a lightweight, fine-tuned model for task-specialized inference.

I led the team and worked across the full pipeline, which combines:

- **Large language models** including NVIDIA Nemotron, GPT, Gemma, Llama, and Mistral for narrative generation.
- **Fine-tuned T5** using Hugging Face Transformers as a lightweight, task-specialized inference solution.
- **Automated parallel GPU workloads** on a Linux HPC cluster using SLURM and Bash for data partitioning, resource allocation, and batch processing.
- **End-to-end data processing** from raw conversational input to generated narrative output.
