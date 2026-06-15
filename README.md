# :rocket: QuerySphere AI

**An Intelligent Retrieval-Augmented Generation (RAG) Platform for Document Understanding and Knowledge Discovery**

QuerySphere AI is an AI-powered research assistant that enables users to interact with large collections of documents using natural language. The platform combines Large Language Models (LLMs), semantic search, vector databases, and agentic workflows to provide accurate, context-aware, and source-grounded answers.

---

## :pushpin: Project Overview

QuerySphere AI simplifies information retrieval from unstructured documents such as research papers, clinical trial reports, scientific literature, and technical documentation.

The system processes uploaded documents, generates embeddings, stores them in a vector database, retrieves the most relevant information, and augments LLM responses with factual context from the retrieved documents.

---

## :sparkles: Features

### :page_facing_up: Document Management
- Upload and process PDF documents.
- Automatic text extraction and preprocessing.
- Document chunking for efficient retrieval.
- Metadata storage and document tracking.

### :mag: Semantic Search
- Embedding-based document retrieval.
- Similarity search using vector embeddings.
- Context-aware information discovery.
- More accurate than traditional keyword search.

### :speech_balloon: Conversational AI
- Chat-based interface for document interaction.
- Context-grounded responses.
- Multi-turn conversation support.
- Real-time answer generation.

### :robot_face: Agentic Workflow
- Planner Agent for query understanding.
- Retrieval Agent for relevant document fetching.
- Response Agent for answer generation.
- Coordinated workflow orchestration.

### :books: Explainable AI
- Source citation support.
- Retrieved chunk visualization.
- Transparent answer generation process.

---

# :desktop_computer: Frontend Development

## Responsibilities

### User Interface Development
- Developed a responsive React-based web application.
- Designed intuitive dashboards for document management and querying.
- Implemented modern UI/UX principles for seamless user interaction.

### Document Upload Module
- Built document upload functionality.
- Displayed document processing status.
- Managed uploaded document listings and metadata.

### Chat Interface
- Developed ChatGPT-style conversational interface.
- Enabled users to ask questions about uploaded documents.
- Displayed chat history and AI-generated responses.

### Search Results Visualization
- Displayed retrieved document chunks.
- Showed supporting citations and references.
- Visualized retrieval results for transparency.

### API Integration
- Connected frontend components with backend services.
- Handled asynchronous API requests.
- Implemented error handling and loading states.

## Frontend Tech Stack

- React.js
- JavaScript / TypeScript
- HTML5
- CSS3
- Tailwind CSS
- Axios

---

# :gear: Backend Development

## Responsibilities

### RAG Pipeline Development
- Built an end-to-end Retrieval-Augmented Generation architecture.
- Integrated retrieval and generation workflows.
- Improved response accuracy through contextual augmentation.

### Document Ingestion Pipeline
- Extracted text from uploaded PDF documents.
- Performed text preprocessing and cleaning.
- Implemented chunking strategies for efficient retrieval.

### Embedding Generation
- Generated vector embeddings for document chunks.
- Converted user queries into embeddings.
- Enabled semantic understanding of documents and queries.

### Vector Database Integration
- Integrated Pinecone Vector Database.
- Stored and managed document embeddings.
- Implemented similarity search for retrieval.

### Semantic Retrieval
- Retrieved top relevant document chunks.
- Used vector similarity search techniques.
- Optimized retrieval quality and response relevance.

### LLM Integration
- Integrated Large Language Models for answer generation.
- Passed retrieved context to LLMs.
- Generated grounded and context-aware responses.

### Agent-Based Query Processing
- Developed Planner Agent for workflow orchestration.
- Implemented Retrieval Agent for information gathering.
- Designed Response Agent for final answer synthesis.

### Workflow Automation
- Automated ingestion and indexing processes using n8n.
- Reduced manual intervention in document processing.
- Streamlined backend operations.

### API Development
- Built REST APIs for:
  - Document Upload
  - Query Processing
  - Search Retrieval
  - Chat History Management
  - Metadata Management

### Database Management
- Managed document metadata using MongoDB.
- Stored indexing information and document status.
- Maintained efficient data organization.

## Backend Tech Stack

- Node.js
- Express.js
- MongoDB
- MongoDB Vector Database
- OpenAI APIs / LLM APIs
- n8n
- REST APIs

---

# :building_construction: System Architecture

```text
User Query
    │
    ▼
Frontend (React)
    │
    ▼
Backend API (Node.js)
    │
    ▼
Planner Agent
    │
    ├── Retrieval Agent
    │         │
    │         ▼
    │    Mongo Vector DB
    │
    ▼
LLM Response Generation
    │
    ▼
Context-Aware Response
    │
    ▼
Frontend Display + Citations
