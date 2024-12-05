graph TD
    A[User Query] --> B[Retriever Module]
    B --> C[Knowledge Base]
    C --> D[Relevant Information]
    D --> E[Generator Module]
    E --> F[Final Response]

    subgraph Retrieval
        B
        C
    end

    subgraph Generation
        E
    end
