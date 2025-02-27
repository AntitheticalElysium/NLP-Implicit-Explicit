# Goals: Cross-Sentence Implicit Argument Detection

-> Phase 1: Baseline System (Quickest to Implement, Sets a Strong Foundation)

    Implement predicate-argument extraction using a basic SRL model.
    Set up coreference resolution to track missing arguments across sentences.
    Use an off-the-shelf entailment model (e.g., DeBERTa) to validate inferred arguments.
    
    Outcome: A functioning pipeline that can detect cross-sentence implicit arguments at a basic level.

-> Phase 2: Advanced Inference Techniques (Technical Depth)

    Multi-hop retrieval model to locate supporting sentences for implicit arguments.
    Develop a custom entailment model fine-tuned for predicate-aware argument verification.
    Experiment with graph-based representations for discourse-level reasoning.
    
    Outcome: A robust system that improves argument recovery accuracy using reasoning techniques.

-> Phase 3: Hybrid Model & Future Extensions (Exploratory Research)

    Investigate LLM + structured model hybrid approaches (LLM for candidate generation, structured models for validation).
    Explore commonsense reasoning (ConceptNet, ATOMIC-2020) to infer missing arguments.
    Optimize for scalability and efficiency (e.g., using sparse attention mechanisms for long documents).
    
    Outcome: A novel hybrid approach that is scalable and interpretable.
