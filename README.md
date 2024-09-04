
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
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

You can start editing the application by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Technologies Used

- **Next.js**: A React framework for building fast and scalable web applications.
- **ShadCN UI**: A modern UI library for creating responsive and elegant user interfaces.
- **Pinecone**: A vector database for handling database operations with high performance and scalability.
- **Mixedbread AI**: [mxbai-embed-large-v1](https://huggingface.co/mixedbread-ai/mxbai-embed-large-v1) for leveraging a knowledge base to provide default diagnoses.
- **Gemini AI**: [gemini-1.5-pro-latest](https://huggingface.co/models) for generating personalized treatment suggestions.

## Learn More

To learn more about the technologies used in this project, explore the following resources:

- [Next.js Documentation](https://nextjs.org/docs)
- [ShadCN UI Documentation](https://shadcn.dev/docs)
- [Pinecone Documentation](https://docs.pinecone.io/docs)
- [Mixedbread AI on Hugging Face](https://huggingface.co/mixedbread-ai/mxbai-embed-large-v1)
- [Gemini AI on Hugging Face](https://huggingface.co/models)

## Deploy on Vercel

Deploying your Next.js application is easiest through the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme). Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
