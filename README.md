# Fine-Tuning Q&A Prompt for PDFs
This is a notebook to fine-tune an LLM to a series of PDFs

# Use
Since I had a lot of PDF content, I made a simple loader that would ingest the PDFs as one giant "Combined.pdf" and then run it through a Teacher and Student Q&A to create JSON output that could be used for the Instruction, Input, Output fine-tuning of an LLM (in this case Mixtral 7B).

# Warning
I'm a pretty average Python user and so you have been forewarned.
