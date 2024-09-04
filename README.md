# GeminiHealth

GeminiHealth is an advanced medical records application designed to streamline healthcare management and enhance patient care. Built using [Next.js](https://nextjs.org/) and [ShadCN UI](https://shadcn.dev/), this platform leverages cutting-edge AI technologies to provide accurate diagnoses and personalized treatment suggestions.

## Features

- **Medical Records Management**: Efficiently manage and access patient medical records with a user-friendly interface.
- **AI-Powered Diagnosis**: Utilizes [mixedbread-ai/mxbai-embed-large-v1](https://huggingface.co/mixedbread-ai/mxbai-embed-large-v1) as a knowledge base for providing default diagnoses based on patient data.
- **Personalized Treatment Suggestions**: Integrates [gemini-1.5-pro-latest](https://huggingface.co/models) to offer optimal treatment suggestions tailored to individual patients.
- **Robust Database Operations**: Powered by [Pinecone](https://www.pinecone.io/) for fast, scalable, and reliable database operations.
- **Modern UI**: Developed with ShadCN UI, providing a sleek, responsive, and intuitive user interface.

## Getting Started

To get started with GeminiHealth, clone the repository and run the development server:

```bash
git clone https://github.com/Rish-it/GeminiHealth.git
cd GeminiHealth
npm install
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
