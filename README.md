# Red Dragonfly (redragonfly)
Red Dragonfly is a modern data pipeline for Geospatial Open-Source Intelligence (GEO-OSINT) analysis of global terrorism organizations.

## Main Points of Project
1. Collect intial set of data
2. Network Graphs
    - Social Networks
    - Geographical Networks
    - Social to Geographic bridges
3. Analytic Dashboard
    - Statistical Graphs
    - Basic info panels
    - Interactive maps
        - Timeline
    - Temporal Socio-geographic networks

## Data Engineerig
### Stages
- Generation
    - Source Systems
        - Base social data
            - Census data
            - Cultural group areas
        - Events
            - Historic
                - Global Terorism Database (download excel file)
                    - intial ingestion
                    - update
            - Current
                - News Feed RSSes
                - Social media streams
        - Organizations
            - Wikipedia scrape
                - initial ingestion
                - update
        - People
            - Wikipedia scrape
                - initial ingestion
                - update
- Storage
- Ingestion
- Transformation
- Serving Data

### Considerations
- Security
- Data management
- DataOps
- Data architecture
- Orchestration
- software engineering