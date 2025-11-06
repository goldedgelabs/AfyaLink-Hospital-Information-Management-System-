Mermaid diagram

flowchart TD
  FE[Frontend] --> API[NestJS]
  API --> DB[PostgreSQL]
  API --> Redis[Redis]
  API --> S3[S3]
  API --> AI[NeuroEdge / OpenAI]
