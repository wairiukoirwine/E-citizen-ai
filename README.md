# E-citizen-aieCitizen Smart Q&A Bot (PDF-based)

A smart question-answering chatbot that answers questions from an uploaded PDF document, such as an eCitizen services guide. It uses semantic search to find the most relevant paragraph in the PDF and responds interactively via a web interface.

Features

Upload any PDF and automatically process its contents.

Ask questions in natural language about the PDF content.

Uses semantic search for accurate answers.

Maintains chat history for an interactive experience.

Fast and lightweight.

How It Works

The PDF text is extracted and split into paragraphs.

Each paragraph is converted into a vector representation for semantic search.

When a question is asked, the chatbot finds the most relevant paragraph using similarity search.

The answer is displayed interactively along with chat history.

How to Use

Launch the chatbot interface.

Upload your PDF document.

Type your questions and receive answers based on the PDF content.

Chat history is maintained for reference.

Notes

Only one PDF can be uploaded at a time.

The bot retrieves the single most relevant paragraph per query.

Works best for factual, well-structured PDFs.

License

This project is open-source and free to use.
